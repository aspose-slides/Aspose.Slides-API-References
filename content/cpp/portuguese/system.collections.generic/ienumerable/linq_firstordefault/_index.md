---
title: LINQ_FirstOrDefault()
second_title: Referência da API Aspose.Slides for C++
description: Retorna o primeiro elemento de uma sequência, ou um valor padrão se a sequência estiver vazia.
type: docs
weight: 66
url: /pt/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() método

Retorna o primeiro elemento de uma sequência, ou um valor padrão se a sequência estiver vazia.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```

### Valor de Retorno

Primeiro elemento na sequência ou valor construído por padrão se a sequência estiver vazia.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) método

Retorna o primeiro elemento da sequência que satisfaz uma condição ou um valor padrão se nenhum elemento for encontrado.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Uma função para testar cada elemento em busca de uma condição. |

### Valor de Retorno

default(T) se a origem estiver vazia ou se nenhum elemento passar no teste especificado por predicate; caso contrário, o primeiro elemento em source que passar no teste especificado por predicate.

## Veja Também

* Classe [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)