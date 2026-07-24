---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen nesneyi arar ve tüm listedeki son ortaya çıkışın sıfır tabanlı indeksini döndürür.
type: docs
weight: 469
url: /tr/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const metod

Belirtilen nesneyi arar ve tüm listedeki son ortaya çıkışın sıfır tabanlı dizinini döndürür.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | const T\& | Listedeki bulunacak nesne |

### Dönüş Değeri

item'ın [List](../) içinde tüm kapsamda son ortaya çıkışının sıfır tabanlı dizini, bulunursa; aksi takdirde -1.

## List::LastIndexOf(const T\&, int32_t) const metod

[List](../) içindeki öğeler aralığında, ilk öğeden belirtilen indekse kadar uzanan, belirtilen nesneyi arar ve son ortaya çıkışın sıfır tabanlı dizinini döndürür.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | const T\& | Listedeki bulunacak nesne |
| index | **int32_t** | Geriye doğru aramanın sıfır tabanlı başlangıç indeksi. |

### Dönüş Değeri

item'ın [List](../) içinde, ilk öğeden index'e kadar uzanan öğeler aralığında son ortaya çıkışının sıfır tabanlı dizini, bulunursa; aksi takdirde -1.

## List::LastIndexOf(const T\&, int32_t, int32_t) const metod

[List](../) içindeki öğeler aralığında, count sayısı kadar öğe içeren ve index'te sona eren, belirtilen nesneyi arar ve son ortaya çıkışın sıfır tabanlı dizinini döndürür.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | const T\& | [List](../) içinde bulunacak nesne |
| index | **int32_t** | Geriye doğru aramanın sıfır tabanlı başlangıç indeksi. |
| count | **int32_t** | Aranacak bölümdeki öğe sayısı. |

### Dönüş Değeri

item'ın [List](../) içinde, count sayısı kadar öğe içeren ve index'te sona eren öğeler aralığında son ortaya çıkışının sıfır tabanlı dizini, bulunursa; aksi takdirde -1.

## İlgili

* Sınıf [List](../)
* Ad alanı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)