---
title: Sort()
second_title: Referência da API Aspose.Slides para C++
description: Ordena os elementos no array especificado usando o comparador padrão.
type: docs
weight: 742
url: /pt/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) método

Ordena os elementos no array especificado usando o comparador padrão.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Array alvo |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) método

Ordena um intervalo de elementos no array especificado usando o comparador padrão.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Array alvo |
| startIndex | int | O índice que designa o início do intervalo de elementos a ordenar |
| count | int | O tamanho do intervalo de elementos a ordenar |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) método

Ordena os elementos no array especificado usando o comparador especificado.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Array alvo |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | Objeto IComparer<T> usado para comparar os elementos do array |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) método

NÃO IMPLEMENTADO.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```

## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) método

Ordena os elementos no array especificado usando a comparação especificada.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) método

Ordena dois arrays, um contendo chaves e o outro - itens correspondentes, com base nos valores do array que contém as chaves, cujos elementos são comparados usando o operador<.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TKey | O tipo dos elementos no array **keys** |
| TValue | O tipo dos elementos no array **items** |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) que contém valores de chave |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) que contém itens que são mapeados para os valores de chave no array **keys** |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) método

Ordena dois arrays, um contendo chaves e o outro - itens correspondentes, com base nos valores do array que contém as chaves, cujos elementos são comparados usando o comparador padrão.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TKey | O tipo dos elementos no array **keys** |
| TValue | O tipo dos elementos no array **items** |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) que contém valores de chave |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) que contém itens que são mapeados para os valores de chave no array **keys** |
| index | int | O índice que designa o início do intervalo a ordenar |
| length | int | O número de elementos no intervalo a ordenar |

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Comparison](../../comparison/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)