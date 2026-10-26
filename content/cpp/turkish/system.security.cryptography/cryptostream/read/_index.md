---
title: Read()
second_title: Aspose.Slides for C++ API Referansı
description: Akıştan veri okur.
type: docs
weight: 14
url: /tr/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Akıştan veri okur.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Hedef veri tamponu. |
| offset | **int32_t** | Hedef tampondaki ofset. |
| count | **int32_t** | Okunacak bayt sayısı. |

### Dönüş Değeri

Gerçekte okunan bayt sayısı.

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Akıştan veri okur.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Hedef veri tamponu. |
| offset | **int32_t** | Hedef tampondaki ofset. |
| count | **int32_t** | Okunacak bayt sayısı. |

### Dönüş Değeri

Gerçekte okunan bayt sayısı.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [CryptoStream](../)
* Ad alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)