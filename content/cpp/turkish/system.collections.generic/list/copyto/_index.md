---
title: CopyTo()
second_title: Aspose.Slides for C++ API Referansı
description: Liste öğelerini mevcut dizi öğelerine kopyalar.
type: docs
weight: 209
url: /tr/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) metodu


Liste öğelerini mevcut dizi öğelerine kopyalar.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | Hedef dizi. |
| arrayIndex | int | Hedef dizi başlangıç indeksi. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) metodu


Tüm öğeleri mevcut dizi öğelerine kopyalar.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) öğelerini kopyalamak için. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) metodu


Belirtilen indeksten başlayarak öğeleri mevcut dizi öğelerine kopyalar.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Mevcut nesne tarafından temsil edilen listedeki elemanın 0 tabanlı indeksi, kopyalamaya başlanacak. |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) öğelerini kopyalamak için. |
| arrayIndex | int | Hedef dizi içindeki başlangıç konumu. |
| count | int | Kopyalanacak eleman sayısı. |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)