---
title: Sort()
second_title: Referencia de API de Aspose.Slides para C++
description: Ordena los elementos en la lista.
type: docs
weight: 521
url: /es/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) método

Ordena los elementos en la lista.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Comparador a usar. |

## List::Sort() método

Ordena los elementos en la lista usando el comparador predeterminado.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) método

Ordena los elementos en el segmento de la lista.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de inicio del segmento. |
| count | int | Tamaño del segmento. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | Comparador a usar. |

## List::Sort(Comparison\<T\>, bool) método

Ordena los elementos en la lista.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) a usar. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IComparer](../../icomparer/)
* Clase [List](../)
* Clase [Comparison](../../../system/comparison/)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)