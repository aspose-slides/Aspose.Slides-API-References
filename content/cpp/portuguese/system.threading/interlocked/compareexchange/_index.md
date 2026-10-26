---
title: CompareExchange()
second_title: Aspose.Slides para C++ Referência da API
description: "Troca o valor na variável: verifica se a variável é igual a um valor específico e armazena o novo valor apenas se o valor armazenado corresponder ao esperado."
type: docs
weight: 79
url: /pt/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T\&, T, T) método

Troca o valor na variável: verifica se a variável é igual a um valor específico e armazena o novo valor apenas se o valor armazenado corresponder ao esperado.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo da variável. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| location1 | T\& | Referência da variável a ser alterada. |
| value | T | Valor a ser armazenado. |
| comparand | T | Valor para comparar com o valor da variável antes da troca. |

### Valor de retorno

Valor da variável no início da operação, independentemente de ter sido alterado ou não.

## Interlocked::CompareExchange(T\&, T, T) método

Troca o valor na variável: verifica se a variável é igual a um valor específico e armazena o novo valor apenas se o valor armazenado corresponder ao esperado. Não implementado.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo da variável. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| location1 | T\& | Referência da variável a ser alterada. |
| value | T | Valor a ser armazenado. |
| comparand | T | Valor para comparar com o valor da variável antes da troca. |

### Valor de retorno

Valor da variável no início da operação, independentemente de ter sido alterado ou não.

## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) método

Troca o valor na variável: verifica se a variável é igual a um valor específico e armazena o novo valor apenas se o valor armazenado corresponder ao esperado.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| location1 | **int32_t**\& | Referência da variável a ser alterada. |
| value | **int32_t** | Valor a ser armazenado. |
| comparand | **int32_t** | Valor para comparar com o valor da variável antes da troca. |
| succeeded | **bool**\& | Referência à variável que é definida como true se a troca ocorreu e a false caso contrário. |

### Valor de retorno

Valor da variável no início da operação, independentemente de ter sido alterado ou não.

## Veja também

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)