# 📊 Case de Análise de Dados Ifood

## 📌 Descrição
Este projeto consiste na análise de dados utilizando o Google Colab e Google Drive. Os dados do case devem ser armazenados no Google Drive e lidos diretamente do notebook.

## 📂 Estrutura dos Dados
Os arquivos devem ser nomeados e armazenados no Google Drive da seguinte forma:
- `pedido.csv`
- `usuario.csv`
- `restaurante.csv`
- `teste_ab.csv`

## 🚀 Como Executar

### **1️⃣ Salvar os Arquivos no Google Drive**
1. Faça upload dos arquivos `pedido.csv`, `usuario.csv`, `restaurante.csv` e `teste_ab.csv` para uma pasta no seu Google Drive.

### **2️⃣ Acessar e Executar o Notebook**
1. Abra o notebook no [Google Colab]
2. Execute a célula de autorização do Google Drive.
3. Substitua os caminhos dos arquivos pelo caminho do Drive da pessoa que está executando o código.
   - Exemplo de código para montar o Drive e definir os caminhos:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')

   # Substitua o caminho pelo caminho correto da pasta onde salvou os arquivos
   caminho_base = '/content/drive/My Drive/SuaPasta/'
   
   pedido = caminho_base + 'pedido.csv'
   usuario = caminho_base + 'usuario.csv'
   restaurante = caminho_base + 'restaurante.csv'
   teste_ab = caminho_base + 'teste_ab.csv'
