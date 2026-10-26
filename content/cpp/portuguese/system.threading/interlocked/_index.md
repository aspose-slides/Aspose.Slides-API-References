---
title: Interlocked
second_title: Referência da API Aspose.Slides para C++
description: Fornece API para operações seguras entre threads. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por nenhum meio.
type: docs
weight: 131
url: /pt/system.threading/interlocked/
---
## Interlocked class

Fornece API para operações seguras entre threads. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por nenhum meio.

```cpp
class Interlocked
```

## Métodos

| Método | Descrição |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | Aumenta o valor de forma atômica. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | Aumenta o valor de forma atômica. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Troca-compare o valor na variável: verifica se a variável é igual a um valor específico e armazena o novo valor somente se o valor armazenado corresponder ao esperado. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Troca-compare o valor na variável: verifica se a variável é igual a um valor específico e armazena o novo valor somente se o valor armazenado corresponder ao esperado. Não implementado. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | Troca-compare o valor na variável: verifica se a variável é igual a um valor específico e armazena o novo valor somente se o valor armazenado corresponder ao esperado. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | Decrementa o valor de forma atômica. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | Decrementa o valor de forma atômica. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Troca o valor na variável: armazena o novo valor e retorna o valor que a variável possuía imediatamente antes da troca. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Troca o valor na variável: armazena o novo valor e retorna o valor que a variável possuía imediatamente antes da troca. Não implementado. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | Aumenta o valor de forma atômica via procedimento de troca-adição. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | Aumenta o valor de forma atômica via procedimento de troca-adição. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | Incrementa o valor de forma atômica. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | Incrementa o valor de forma atômica. |
| static **int64_t** [Read](./read/)(**int64_t**\&) | Retorna um valor de 64 bits, carregado como uma operação atômica. |

## Veja Também

* Espaço de nomes [System::Threading](../)
* Biblioteca [Aspose.Slides](../../)