---
title: VerifyHash()
second_title: Справочник API Aspose.Slides для C++
description: Проверяет, действительна ли подпись указанного хэша.
type: docs
weight: 170
url: /ru/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) метод

Проверяет, действительна ли подпись указанного хэша.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Значение хэша подписанных данных. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Данные подписи. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеширования. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Режим заполнения. возвращает true, если подпись действительна, иначе - false. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)