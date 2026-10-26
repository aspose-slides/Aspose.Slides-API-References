---
title: SignData()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen giriş değerinin imzasını hesaplar.
type: docs
weight: 183
url: /tr/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) metot

Belirtilen giriş değerinin imzasını hesaplar.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) giriş verilerini okumak için. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Kullanılacak hash algoritması. |

### Dönüş Değeri

[RSA](../../rsa/) belirtilen veri için imza.

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) metot

Belirtilen giriş değerinin imzasını hesaplar.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | İmzalanan verileri okumak için akış. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Kullanılacak hash algoritması. |

### Dönüş Değeri

[RSA](../../rsa/) belirtilen veri için imza.

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) metot

Belirtilen giriş değerinin imzasını hesaplar.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) giriş verilerini okumak için. |
| offset | **int32_t** | Giriş tampon diliminin başlangıç indeksi. |
| count | **int32_t** | Giriş tampon diliminin boyutu. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Kullanılacak hash algoritması. |

### Dönüş Değeri

[RSA](../../rsa/) belirtilen veri için imza.

## İlgili

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [RSACryptoServiceProvider](../)
* Sınıf [Stream](../../../system.io/stream/)
* AdAlanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)