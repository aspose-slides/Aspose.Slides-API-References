---
title: Read()
second_title: Aspose.Slides for C++ API Referansı
description: Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.
type: docs
weight: 79
url: /tr/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) yöntemi

Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi |
| offset | **int32_t** | **buffer** içinde 0 tabanlı bir konum, yazmaya başlanacak |
| count | **int32_t** | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan bayt sayısı

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) yöntemi

Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizi görünümü |
| offset | **int32_t** | **buffer** içinde 0 tabanlı bir konum, yazmaya başlanacak |
| count | **int32_t** | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan bayt sayısı

## Ayrıca Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [MemoryStream](../)
* Ad Alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)