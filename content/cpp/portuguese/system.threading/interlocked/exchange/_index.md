---
title: Exchange()
second_title: Referência da API Aspose.Slides para C++
description: "Troca o valor de uma variável: armazena o novo valor e retorna o valor que a variável possuía imediatamente antes da gravação."
type: docs
weight: 66
url: /pt/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) método


Troca o valor de uma variável: armazena o novo valor e retorna o valor que a variável possuía imediatamente antes da gravação.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo da variável. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| location1 | T\& | Referência da variável a ser alterada. |
| value | T | Valor a ser armazenado. |

### Valor de retorno

Valor da variável imediatamente antes de ser alterada.

## Interlocked::Exchange(T\&, T) método


Troca o valor de uma variável: armazena o novo valor e retorna o valor que a variável possuía imediatamente antes da gravação. Não implementado.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo da variável. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| location1 | T\& | Referência da variável a ser alterada. |
| value | T | Valor a ser armazenado. |

### Valor de retorno

Valor da variável imediatamente antes de ser alterada.

## Veja também

* Classe [Interlocked](../)
* Espaço de nomes [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)