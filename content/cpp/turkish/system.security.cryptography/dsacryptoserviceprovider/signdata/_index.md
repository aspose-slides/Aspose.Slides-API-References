---
title: SignData()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen girdi değerinin imzasını hesaplar.
type: docs
weight: 183
url: /tr/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) metot


Belirtilen girdi değerinin imzasını hesaplar.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) giriş verilerini okumak için. |

### Dönüş Değeri

[DSA](../../dsa/) belirtilen veri için imza.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) metot


Belirtilen girdi değerinin imzasını hesaplar.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | İmzalanan veriyi okumak için akış. |

### Dönüş Değeri

[DSA](../../dsa/) belirtilen veri için imza.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) metot


Belirtilen girdi değerinin imzasını hesaplar.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) giriş verilerini okumak için. |
| offset | **int32_t** | Giriş tampon diliminin başlangıç indeksi. |
| count | **int32_t** | Giriş tampon diliminin boyutu. |

### Dönüş Değeri

[DSA](../../dsa/) belirtilen veri için imza.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metot


Belirtilen hash algoritması kullanılarak belirtilen veri dizisinin hash değerini hesaplar ve sonucu imzalar.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Giriş veri dizisi. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. [DSA](../../dsa/) imzasını giriş verisi için döndürür. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metot


Belirtilen hash algoritması kullanılarak belirtilen veri dizisinin hash değerini hesaplar ve sonucu imzalar.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Giriş veri dizisi. |
| offset | **int32_t** | **data** içindeki konum. |
| count | **int32_t** | Giriş verisi olarak kullanılacak bayt sayısı. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. [DSA](../../dsa/) imzasını giriş verisi için döndürür. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) metot


Belirtilen hash algoritması kullanılarak belirtilen ikili akışın hash değerini hesaplar ve sonucu imzalar.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | İkili akış. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. [DSA](../../dsa/) imzasını giriş verisi için döndürür. |

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSACryptoServiceProvider](../)
* Class [Stream](../../../system.io/stream/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)