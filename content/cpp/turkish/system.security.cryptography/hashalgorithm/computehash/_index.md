---
title: ComputeHash()
second_title: Aspose.Slides için C++ API Referansı
description: Tamponu hash'ler.
type: docs
weight: 14
url: /tr/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) metodu

Tamponu hash'ler.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kaynak tampon. |

### Dönüş Değeri

Hesaplanmış hash değeri.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) metodu

Tampon dilimini hash'ler.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kaynak tampon. |
| offset | int | Kaynak tampondaki ofset. |
| count | int | Kaynak tampondan kullanılacak bayt sayısı. |

### Dönüş Değeri

Hesaplanmış hash değeri.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) metodu

Akışı sonuna kadar okur ve okunan verinin hash'ini hesaplar.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | Verileri okumak için akış. |

### Dönüş Değeri

Tüm akış verisi için hesaplanmış hash değeri.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)