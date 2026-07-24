---
title: BinarySearch()
second_title: Aspose.Slides für C++ API-Referenz
description: Sucht das Element in einer sortierten Liste.
type: docs
weight: 339
url: /de/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const Methode

Sucht nach dem Element in einer sortierten Liste.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | const T\& | Zu suchendes Element. |

### Rückgabewert

[Index](../../../system/index/) des Elements in einer sortierten Liste oder das Komplement des nächsten Indexes.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const Methode

Sucht nach dem Element in einer sortierten Liste.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | const T\& | Zu suchendes Element. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) zum Verwenden. |

### Rückgabewert

[Index](../../../system/index/) des Elements in einer sortierten Liste oder das Komplement des nächsten Indexes.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const Methode

Sucht nach dem Element in einer sortierten Liste.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) Anfang. |
| count | int | [Range](../../../system/range/) Größe. |
| item | const T\& | Zu suchendes Element. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) zum Verwenden. |

### Rückgabewert

[Index](../../../system/index/) des Elements in einer sortierten Liste oder das Komplement des nächsten Indexes.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../)
* Class [IComparer](../../icomparer/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)