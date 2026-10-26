---
title: SignHash()
second_title: Справочник API Aspose.Slides для C++
description: Вычисляет подпись для указанного значения хеша.
type: docs
weight: 196
url: /ru/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) метод

Вычисляет подпись для указанного значения хеша.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Значение хеша. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Алгоритм хеширования. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Режим заполнения. возвращает [RSA](../../rsa/) подпись для указанного хеша. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) метод

Вычисляет подпись указанного входного значения. Не реализовано.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Значение хеша данных для подписи. |
| str | const [String](../../../system/string/)\& | Идентификатор алгоритма хеширования, используемый для создания хеша. |

### Возвращаемое значение

[RSA](../../rsa/) подпись для указанных данных.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Class [String](../../../system/string/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)