# Myfinance - Citibank

Esse é um script para importar o arquivo de extrato em formato XLS do Citibank para o [MyFinance](http://myfinance.com.br).

## Por que?

Por que o Citibank não possui exportação do extrato OFX.

## Configuração

Coloque as variáveis de ambiente abaixo com as informações do MyFinance.

```
$ export MYFINANCE_ENTITY=99 MYFINANCE_DEPOSIT_ACCOUNT=99 MYFINANCE_ACCOUNT_ID=99 MYFINANCE_TOKEN=SEUTOKENAQUI
```

## Uso

Para importar um arquivo de extrato:

```
$ bundle exec bin/myfinance-citibank import -f exemplo.xml
```

## Licença

Esse código é livre para ser usado dentro dos termos da licença [MIT license](http://www.opensource.org/licenses/mit-license.php).

## Bugs, Issues, Agradecimentos, etc

Comentários são bem-vindos. Envie seu feedback através do [issue tracker do GitHub](http://github.com/rafaelp/myfinance-citibank/issues)

## Autor

[**Rafael Lima**](http://github.com/rafaelp) trabalhando no [Boleto Simples](http://boletosimples.com.br)

Blog: [http://rafael.adm.br](http://rafael.adm.br)

Twitter: [http://twitter.com/rafaelp](http://twitter.com/rafaelp)

### Gostou?

[Me recomende Working With Rails](http://workingwithrails.com/recommendation/new/person/14248-rafael-lima)