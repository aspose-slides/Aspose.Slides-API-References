---
title: Sort()
second_title: Aspose.Slides für C++ API-Referenz
description: Sortiert die Elemente in der Liste.
type: docs
weight: 521
url: /de/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) Methode

Sortiert die Elemente in der Liste.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Zu verwendender Comparator. |

## List::Sort() Methode

Sortiert die Elemente in der Liste mit dem Standardvergleich.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) Methode

Sortiert die Elemente im Listenschnitt.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Startindex des Abschnitts. |
| count | int | Größe des Abschnitts. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | Zu verwendender Comparator. |

## List::Sort(Comparison\<T\>, bool) Methode

Sortiert die Elemente in der Liste.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) zur Verwendung. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IComparer](../../icomparer/)
* Klasse [List](../)
* Klasse [Comparison](../../../system/comparison/)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)