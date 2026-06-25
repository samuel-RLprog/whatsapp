# Whatsappalot

📲 WhatsApp Bulk Sender — Automação de Envio de Mensagens

Sistema desenvolvido em Python para automatizar o envio de mensagens via WhatsApp para múltiplos contatos, com base em dados armazenados em uma planilha Excel.

A proposta do projeto é eliminar o trabalho manual e repetitivo de enviar mensagens uma a uma, permitindo que o usuário gerencie sua lista de contatos de forma simples, direto na planilha, sem precisar tocar em uma linha de código.


✨ Funcionalidades:
✅ Leitura automática de uma planilha Excel (.xlsx)
✅ Extração de nome, número de telefone e mensagem para cada contato
✅ Envio automatizado das mensagens via WhatsApp
✅ Planilha 100% editável — o usuário pode adicionar, editar ou remover contatos a qualquer momento
✅ Processo dinâmico: não é necessário alterar o código para atualizar a lista de envios


🗂️ Como funciona:
O usuário preenche a planilha Excel com as colunas: Nome, Telefone e Mensagem.
O sistema lê esses dados automaticamente.
Para cada linha da planilha, o script abre o WhatsApp e envia a mensagem correspondente ao número cadastrado.
Ao final, todos os contatos da lista recebem sua mensagem personalizada — sem intervenção manual.

📄 planilha (lista_contatos_ficticios.xlsx)


Nome            Telefone                  Mensagem
João Silva   ! +55 11 91234-5678Olá ! João, sua proposta está pronta
!Maria Souza ! +55 21 99876-5432Olá ! Maria, segue a confirmação...


💡 Basta adicionar ou remover linhas na planilha para atualizar quem receberá as mensagens — o sistema sempre lê a versão mais recente do arquivo.

🚀 Tecnologias utilizadas
Python
PyWhatKit
time
openpyxl


📌 Requisitos:
Python 3.8 ou superior
Conta ativa no WhatsApp Web
Planilha Excel preenchida no formato esperado pelo sistema



🎯 Possíveis aplicações:
Envio de comunicados e avisos em massa
Confirmação de pedidos, agendamentos ou propostas
Campanhas de relacionamento com clientes
Automação de cobranças e lembretes



🔮 Melhorias futuras:
 Interface gráfica (GUI) para facilitar o uso por pessoas não técnicas
 Log de envios (mensagens enviadas com sucesso/erro)
 Suporte a envio de imagens e arquivos
 Agendamento de disparos


📄 Licença:
Este projeto está sob a licença MIT. Sinta-se livre para utilizar, modificar e distribuir.


👨‍💻 Desenvolvido por:
Samuel R Lopes — www.linkedin.com/in/samuelrl | (https://github.com/samuel-RLprog)


