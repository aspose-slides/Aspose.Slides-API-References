---
title: Sort()
second_title: Referencia de la API de Aspose.Slides para C++
description: Ordena los elementos del array especificado usando el comparador predeterminado.
type: docs
weight: 742
url: /es/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) método

Ordena los elementos en el array especificado usando el comparador predeterminado.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Array objetivo |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) método

Ordena un rango de elementos en el array especificado usando el comparador predeterminado.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Array objetivo |
| startIndex | int | El índice que designa el comienzo del rango de elementos a ordenar |
| count | int | El tamaño del rango de elementos a ordenar |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) método

Ordena los elementos en el array especificado usando el comparador especificado.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Array objetivo |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | Objeto IComparer<T> usado para comparar los elementos del array |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) método

NO IMPLEMENTADO.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```

## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) método

Ordena los elementos en el array especificado usando la comparación especificada.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) método

Ordena dos arrays, uno que contiene claves y el otro los elementos correspondientes, según los valores del array que contiene claves, cuyos elementos se comparan usando el operador<.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TKey | El tipo de los elementos en el array **keys** |
| TValue | El tipo de los elementos en el array **items** |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) que contiene los valores de clave |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) que contiene los elementos que están mapeados a los valores de clave en el array **keys** |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) método

Ordena dos arrays, uno que contiene claves y el otro los elementos correspondientes, según los valores del array que contiene claves, cuyos elementos se comparan usando el comparador predeterminado.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TKey | El tipo de los elementos en el array **keys** |
| TValue | El tipo de los elementos en el array **items** |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) que contiene los valores de clave |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) que contiene los elementos que están mapeados a los valores de clave en el array **keys** |
| index | int | El índice que designa el comienzo del rango a ordenar |
| length | int | El número de elementos en el rango a ordenar |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Comparison](../../comparison/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)