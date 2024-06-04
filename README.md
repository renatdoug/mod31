# RFV Segmentação de Clientes

RFV significa recência, frequência, valor e é utilizado para segmentação de clientes baseado no comportamento de compras dos clientes e agrupa eles em clusters parecidos. Utilizando esse tipo de agrupamento podemos realizar ações de marketing e CRM melhores direcionadas, ajudando assim na personalização do conteúdo e até a retenção de clientes.

![RFV](https://img.shields.io/badge/Recência-Frequência-Valor-blue)

## Índice
1. [Descrição](#descrição)
2. [Instalação](#instalação)
3. [Uso](#uso)
4. [Contribuição](#contribuição)
5. [Créditos](#créditos)
6. [Licença](#licença)
7. [Link para Acesso](#link-para-acesso)

## Descrição

Para cada cliente é preciso calcular cada uma das componentes abaixo:

- **Recência (R)**: Quantidade de dias desde a última compra.
- **Frequência (F)**: Quantidade total de compras no período.
- **Valor (V)**: Total de dinheiro gasto nas compras do período.

E é isso que iremos fazer abaixo.

## Instalação

### Requisitos
- Python 3.8+
- pip

### Passos
1. Clone o repositório:
   ```bash
   git clone https://github.com/usuario/rfv-segmentacao.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

## Uso

Para iniciar a aplicação Streamlit, execute:
```bash
streamlit run app.py
```

Você verá a aplicação rodando em `http://localhost:8501`.

## Contribuição

Faça um fork do projeto.

Crie uma nova branch (`git checkout -b feature/MinhaNovaFeature`).

Faça commit das suas mudanças (`git commit -am 'Adicionei uma nova feature'`).

Faça push para a branch (`git push origin feature/MinhaNovaFeature`).

Abra um Pull Request.

## Créditos

Lucas Serra - Professor orientador
Renato Douglas - Desenvolvedor Principal.

## Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

## Link para Acesso

Você pode acessar a aplicação online [aqui](https://apprfv.onrender.com/).
```
