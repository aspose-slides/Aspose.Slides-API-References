---
title: Read()
second_title: Aspose.Slides for C++ API Referansı
description: Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.
type: docs
weight: 144
url: /tr/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) yöntemi


Belirtilen sayıda baytı akıştan okur ve bunları belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi |
| offset | **int32_t** | **buffer** içinde yazmaya başlanacak 0 tabanlı bir konum |
| count | **int32_t** | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan bayt sayısı

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) yöntemi


Belirtilen sayıda baytı akıştan okur ve bunları belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizi görünümü |
| offset | **int32_t** | **buffer** içinde yazmaya başlanacak 0 tabanlı bir konum |
| count | **int32_t** | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan bayt sayısı

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [UnmanagedMemoryStream](../)
* Ad Alanı [System::IO](../../)
* Library [Aspose.Slides](../../../)