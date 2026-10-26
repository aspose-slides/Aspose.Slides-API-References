---
title: FindIndex()
second_title: Aspose.Slides for C++ API Referansı
description: Belirli bir koşula uyan öğeyi arar.
type: docs
weight: 404
url: /tr/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) metot


Belirli bir koşula uyan öğeyi arar.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Öğeleri kontrol etmek için koşul. |

### Dönüş Değeri

[Index](../../../system/index/) eşleşen öğenin indeksi veya bulunamazsa -1.

## List::FindIndex(int, System::Predicate\<T\>) metot


Belirli bir koşula uyan öğeyi arar.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) aramaya başlanacak yer. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Öğeleri kontrol etmek için koşul. |

### Dönüş Değeri

[Index](../../../system/index/) eşleşen öğenin indeksi veya bulunamazsa -1.

## List::FindIndex(int, int, System::Predicate\<T\>) metot


Belirli bir koşula uyan öğeyi arar.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) aramaya başlanacak yer. |
| count | int | İncelenecek öğe sayısı. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Öğeleri kontrol etmek için koşul. |

### Dönüş Değeri

[Index](../../../system/index/) eşleşen öğenin indeksi veya bulunamazsa -1.

## Ayrıca

* Typedef [Predicate](../../../system/predicate/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)