---
title: HashSet()
second_title: Referência da API Aspose.Slides para C++
description: Informações RTTI.
type: docs
weight: 1
url: /pt/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() construtor

Informações RTTI.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## Observações

Cria conjunto vazio. 

## HashSet::HashSet(int) construtor

Cria conjunto vazio com capacidade especificada.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) construtor

Cria conjunto vazio que usa o comparador de igualdade especificado.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) objeto a ser associado ao hashset. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) construtor

Cria hashset com base em valores enumeráveis.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [HashSet](../)
* Classe [IEqualityComparer](../../iequalitycomparer/)
* Classe [IEnumerable](../../ienumerable/)
* Namespace [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)