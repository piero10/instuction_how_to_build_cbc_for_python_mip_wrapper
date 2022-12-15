# Eng
This instruction describes how to build dll's of [cbc решателя](https://github.com/coin-or/Cbc) solver for [python-mip](https://www.python-mip.com/) wrapper

## Why you might need it
Package [python-mip](https://www.python-mip.com/) supplied only with a specific set of cbc dll's. If you whant to use alternative version of cbc, you have to build dll's yourself
It could be useful if you want to use the latest version of cbc-solver throught python-mip, but python-mip does not yet support the latest version of the cbc.

At the moment the manual is only in Russian, please use a translator. 



# Rus
Эта инструкция о том как собрать dll [cbc решателя](https://github.com/coin-or/Cbc) для python обертки [python-mip](https://www.python-mip.com/)

## Зачем это нужно
Обертка [python-mip](https://www.python-mip.com/) поставляется с набором dll конкретной версии решателя cbc, если вы хотите использовать альтернативную версию cbc необходимо собрать этот набор библиотек вручную.
Это может быть нужно, в том случае если вы хотите использовать последнюю версию cbc-решателя, а python-mip для нее еще не собран
