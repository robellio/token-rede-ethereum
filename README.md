# DIOToken

## Descrição

<p>
  Este projeto foi desenvolvido durante o Bootcamp <strong>Blockchain Developer with Solidity</strong> da <strong>Binance</strong> em parceria com a <a href="https://www.dio.me/"><strong>DIO<strong></a>.
  É um projeto simples de um <strong>Token ERC20</strong>, chamado <strong>DIOToken</strong> com um símbolo <strong>DIO</strong>.
</p>

### Funcionalidades 

- **Total Supply:** Retorna o total de tokens emitidos.
- **Balance Of:** Retorna o saldo de tokens de uma conta específica.
- **Transfer:** Permite transferir tokens para outras contas.
- **Approve:** Autoriza outra conta a gastar uma certa quantidade de tokens.
- **Allowance:** Verifica quanto uma conta está autorizada a gastar em nome de outra.
- **Transfer From:** Permite que uma conta autorizada transfira tokens de outra conta.

## Requisitos

Antes de começar, você precisa ter o seguinte instalado em sua máquina:

- [Node.js](https://nodejs.org/)
- [Truffle](https://www.trufflesuite.com/truffle) ou [Hardhat](https://hardhat.org/) (para testes e migrações locais)
- [Ganache](https://www.trufflesuite.com/ganache) ou outro ambiente de blockchain local
- [Solidity](https://docs.soliditylang.org/en/v0.8.0/) (v0.8.x ou superior)

## Como Usar

### É necessário clonar o projeto para a sua máquina

## Utilize: 

git clone <a>https://github.com/robellio/token-rede-ethereum.git</a> 

## Instalando dependências

<p>
Se estiver utilizando o<strong>truffle<strong>, execute no terminal:
<strong>npm install</strong>
</p>

## Compilando o Contrato

<p>
Se estiver utilizando o<strong>truffle<strong>, execute no terminal:
<strong>truffle compile</strong>
</p>

<p>
Caso esteja utilizando o<strong>Hardhat<strong>, execute no terminal:
<strong>npx hardhat compile</strong>
</p>

## Implantando o Contrato 

<p>
Para implementar o contrato em uma <strong>Blockchain local</strong> Vamos utilizar o<strong>Ganache</strong>
<p>

<p>
Se estiver utilizando o<strong>truffle<strong>, execute no terminal:
<strong>truffle migrate</strong>
</p>

## Testando o Contrato

<p>
Se estiver utilizando o<strong>truffle<strong>, execute no terminal:
<strong>truffle test</strong>
</p>

<p>
Caso esteja utilizando o<strong>Hardhat<strong>, execute no terminal:
<strong>npx hardhat test</strong>
</p>