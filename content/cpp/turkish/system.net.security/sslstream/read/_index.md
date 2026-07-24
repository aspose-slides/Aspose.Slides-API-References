---
title: Read()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen sayıda baytı akıştan okur ve bunları belirtilen bayt dizisine yazar.
type: docs
weight: 391
url: /tr/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi |
| offset | **int32_t** | **buffer** içinde 0 temelli bir konum, yazmaya başlanacak yer |
| count | **int32_t** | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan bayt sayısı

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod

Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi |
| offset | **int32_t** | **buffer** içinde 0 temelli bir konum, yazmaya başlanacak yer |
| count | **int32_t** | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan bayt sayısı

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [SslStream](../)
* AdAlanı [System::Net::Security](../../)
* Kütüphane [Aspose.Slides](../../../)