---
title: Write()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen bayt dizisini akışa yazar.
type: docs
weight: 404
url: /tr/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) method

Belirtilen bayt dizisini akışa yazar.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Yazılacak bayt dizisi. |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Yazılacak baytları içeren dizi |
| offset | **int32_t** | **buffer** içinde yazılacak alt aralığın başladığı 0 tabanlı indeks |
| count | **int32_t** | Yazılacak alt aralıktaki eleman sayısı |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) method

Belirtilen bayt dizisini akışa yazar.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Yazılacak bayt dizisi. |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Yazılacak baytları içeren dizi |
| offset | **int32_t** | **buffer** içinde yazılacak alt aralığın başladığı 0 tabanlı indeks |
| count | **int32_t** | Yazılacak alt aralıktaki eleman sayısı |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [SslStream](../)
* Ad alanı [System::Net::Security](../../)
* Kütüphane [Aspose.Slides](../../../)