---
title: BinarySearch()
second_title: Aspose.Slides for C++ API Referansı
description: Sıralı bir listede öğeyi arar.
type: docs
weight: 339
url: /tr/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const yöntem

Sıralı bir listede öğeyi arar.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | const T\& | Aranacak öğe. |

### Dönüş Değeri

[Index](../../../system/index/) sıralı listede öğenin konumu ya da en yakın indeksin tamamlayıcısı.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const yöntem

Sıralı bir listede öğeyi arar.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | const T\& | Aranacak öğe. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) kullanmak için. |

### Dönüş Değeri

[Index](../../../system/index/) sıralı listede öğenin konumu ya da en yakın indeksin tamamlayıcısı.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const yöntem

Sıralı bir listede öğeyi arar.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) başlangıcı. |
| count | int | [Range](../../../system/range/) boyutu. |
| item | const T\& | Aranacak öğe. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) kullanmak için. |

### Dönüş Değeri

[Index](../../../system/index/) sıralı listede öğenin konumu ya da en yakın indeksin tamamlayıcısı.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [List](../)
* Sınıf [IComparer](../../icomparer/)
* İsim Alanı [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)