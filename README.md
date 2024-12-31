# Azure Verificador de Docs

Este projeto permite que o usuário faça upload de imagens para o Azure Blob Storage, encapsuladas em um conteiner, e realize a validação de informações relacionadas a um cartão de crédito. Ele utiliza o framework Streamlit para criar uma interface web simples e interativa.

## Funcionalidades

Upload de Arquivos
Envia o arquivo para o Azure Blob Storage.
Exibe a imagem enviada diretamente na interface.
Validação de Cartão de Crédito:
Mostra se os dados do cartão são válidos ou inválidos.
Exibe informações como nome do titular, banco emissor e data de validade (se disponíveis).

## Tecnologias Utilizadas

Python
Streamlit
Azure Blob Storage



## Como Executar

Execute o seguinte comando no terminal para iniciar o aplicativo Streamlit:

streamlit run app.py

Acesse o aplicativo no navegador através do link fornecido pelo Streamlit.

## Como Configurar o Azure Blob Storage

Crie uma conta de armazenamento no Azure.

Configure um container para armazenar as imagens enviadas.

Atualize a aplicação com suas credenciais e configurações:

 Nome da conta

 Chave da conta

 URL do container


