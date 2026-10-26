---
title: Read()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sayıda baytı temel akıştan okur ve belirtilen bayt dizisine yazar.
type: docs
weight: 53
url: /tr/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) yöntemi

Belirtilen sayıdaki baytı temel akıştan okur ve belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi |
| offset | **int32_t** | **buffer** içinde 0 tabanlı konum, yazmanın başlayacağı yer |
| count | **int32_t** | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan bayt sayısı

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) yöntemi

Belirtilen sayıdaki baytı temel akıştan okur ve belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi |
| offset | **int32_t** | **buffer** içinde 0 tabanlı konum, yazmanın başlayacağı yer |
| count | **int32_t** | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan bayt sayısı

## Ayrıca Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [BufferedStream](../)
* İsim Uzayı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)