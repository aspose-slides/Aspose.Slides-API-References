---
title: Sort()
second_title: Aspose.Slides için C++ API Referansı
description: Listedeki öğeleri sıralar.
type: docs
weight: 521
url: /tr/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) metot


Listedeki öğeleri sıralar.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Kullanılacak karşılaştırıcı. |

## List::Sort() metot


Listedeki öğeleri varsayılan karşılaştırıcı ile sıralar.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) metot


Listedeki dilim öğelerini sıralar.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Dilim başlangıç indeksi. |
| count | int | Dilim boyutu. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | Kullanılacak karşılaştırıcı. |

## List::Sort(Comparison\<T\>, bool) metot


Listedeki öğeleri sıralar.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) kullanmak için. |

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IComparer](../../icomparer/)
* Sınıf [List](../)
* Sınıf [Comparison](../../../system/comparison/)
* İsim Uzayı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)