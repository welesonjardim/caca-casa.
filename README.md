# Caça Casa — protótipo iPhone

Este pacote é a primeira interface do app pessoal para a busca de Réveillon em Cabo Frio.

## O que já está incluído
- Interface responsiva para iPhone.
- Filtros pré-preenchidos: Cabo Frio, 30/12/2026 a 04/01/2027, 2 adultos + 3 crianças.
- Orçamento total de R$ 3.000, piscina e casa inteira como requisitos.
- Salvar preferências no dispositivo.
- Atalhos para sites de temporada.
- Teste de notificação local, quando suportado pelo navegador.

## O que ainda não está ligado
Este protótipo NÃO pesquisa automaticamente os sites, NÃO verifica disponibilidade/preço e NÃO envia alertas reais de novos anúncios. Para isso, é necessário:
1. Hospedar esta aplicação em HTTPS.
2. Criar um serviço backend agendado de hora em hora.
3. Integrar fontes que permitam acesso automatizado ou APIs autorizadas.
4. Configurar notificações push (incluindo service worker e servidor push).
5. Guardar segredos e chaves no servidor, nunca no app.

## Como adicionar ao iPhone
Depois de hospedar em HTTPS, abra o endereço no Safari do iPhone → Compartilhar → Adicionar à Tela de Início.

## Limitações importantes
- O iOS não garante execução horária de um app local em segundo plano; o agendamento deve acontecer num servidor.
- Cada plataforma tem suas próprias regras e limitações para coleta de anúncios.
- Os preços finais precisam ser confirmados no site de origem.
