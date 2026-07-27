---
title: FindIndex()
second_title: Referência da API Aspose.Slides para C++
description: Procura um elemento que atenda a um predicado específico.
type: docs
weight: 404
url: /pt/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) método

Procura um elemento que atenda ao predicado específico.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predicado para verificar os elementos. |

### Valor de Retorno

[Index](../../../system/index/) do elemento correspondente ou -1 se não encontrado.

## List::FindIndex(int, System::Predicate\<T\>) método

Procura um elemento que atenda ao predicado específico.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) para iniciar a busca a partir de. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predicado para verificar os elementos. |

### Valor de Retorno

[Index](../../../system/index/) do elemento correspondente ou -1 se não encontrado.

## List::FindIndex(int, int, System::Predicate\<T\>) método

Procura um elemento que atenda ao predicado específico.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) para iniciar a busca a partir de. |
| count | int | Número de elementos a percorrer. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predicado para verificar os elementos. |

### Valor de Retorno

[Index](../../../system/index/) do elemento correspondente ou -1 se não encontrado.

## Veja Também

* Typedef [Predicate](../../../system/predicate/)
* Classe [List](../)
* Espaço de nomes [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)