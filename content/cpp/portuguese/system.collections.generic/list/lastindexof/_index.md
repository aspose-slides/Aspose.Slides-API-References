---
title: LastIndexOf()
second_title: Referência da API Aspose.Slides para C++
description: Procura o objeto especificado e retorna o índice baseado em zero da última ocorrência em toda a lista.
type: docs
weight: 469
url: /pt/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const método

Procura o objeto especificado e retorna o índice baseado em zero da última ocorrência em toda a lista.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | const T\& | O objeto a localizar na lista |

### Valor de Retorno

O índice baseado em zero da última ocorrência de item dentro de todo o [List](../), se encontrado; caso contrário, -1.

## List::LastIndexOf(const T\&, int32_t) const método

Procura o objeto especificado e retorna o índice baseado em zero da última ocorrência dentro do intervalo de elementos no [List](../) que se estende do primeiro elemento até o índice especificado.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | const T\& | O objeto a localizar na lista |
| index | **int32_t** | O índice baseado em zero de início da pesquisa retroativa. |

### Valor de Retorno

O índice baseado em zero da última ocorrência de item dentro do intervalo de elementos no [List](../) que se estende do primeiro elemento até index, se encontrado; caso contrário, -1.

## List::LastIndexOf(const T\&, int32_t, int32_t) const método

Procura o objeto especificado e retorna o índice baseado em zero da última ocorrência dentro do intervalo de elementos no [List](../) que contém o número especificado de elementos e termina no índice especificado.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | const T\& | O objeto a localizar no [List](../) |
| index | **int32_t** | O índice baseado em zero de início da pesquisa retroativa. |
| count | **int32_t** | O número de elementos na seção a pesquisar. |

### Valor de Retorno

O índice baseado em zero da última ocorrência de item dentro do intervalo de elementos no [List](../) que contém count número de elementos e termina em index, se encontrado; caso contrário, -1.

## Veja Também

* Classe [List](../)
* Namespace [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)