---
title: Sort()
second_title: Aspose.Slides für C++ API-Referenz
description: Sortiert Elemente im angegebenen Array mit dem Standardvergleich.
type: docs
weight: 742
url: /de/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) method

Sortiert Elemente im angegebenen Array mit dem Standardvergleich.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Zielarray |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) method

Sortiert einen Bereich von Elementen im angegebenen Array mit dem Standardvergleich.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Zielarray |
| startIndex | int | Der Index, der den Beginn des zu sortierenden Elementbereichs bezeichnet |
| count | int | Die Größe des zu sortierenden Elementbereichs |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method

Sortiert Elemente im angegebenen Array mit dem angegebenen Vergleich.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Zielarray |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | IComparer<T>-Objekt, das zum Vergleichen der Elemente des Arrays verwendet wird |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) method

NICHT IMPLEMENTIERT.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```

## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) method

Sortiert Elemente im angegebenen Array mit der angegebenen Vergleichsfunktion.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) method

Sortiert zwei Arrays, von denen eines Schlüssel enthält und das andere die entsprechenden Elemente, basierend auf den Werten des Arrays mit den Schlüsseln, wobei die Elemente mit dem Operator < verglichen werden.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TKey | Der Typ der Elemente im **keys**-Array |
| TValue | Der Typ der Elemente im **items**-Array |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) die Schlüsselwerte enthält |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) die Elemente enthält, die den Schlüsselwerten im **keys**-Array zugeordnet sind |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) method

Sortiert zwei Arrays, von denen eines Schlüssel enthält und das andere die entsprechenden Elemente, basierend auf den Werten des Arrays mit den Schlüsseln, wobei die Elemente mit dem Standardvergleich verglichen werden.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TKey | Der Typ der Elemente im **keys**-Array |
| TValue | Der Typ der Elemente im **items**-Array |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) die Schlüsselwerte enthält |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) die Elemente enthält, die den Schlüsselwerten im **keys**-Array zugeordnet sind |
| index | int | Der Index, der den Beginn des zu sortierenden Bereichs bezeichnet |
| length | int | Die Anzahl der Elemente im zu sortierenden Bereich |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Methode [Type](../../object/type/)
* Klasse [Array](../)
* Klasse [IComparer](../../../system.collections.generic/icomparer/)
* Klasse [Comparison](../../comparison/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)