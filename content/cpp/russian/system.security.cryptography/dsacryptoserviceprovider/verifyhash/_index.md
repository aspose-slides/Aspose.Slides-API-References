---
title: VerifyHash()
second_title: Справка API Aspose.Slides для C++
description: Проверяет подпись данных.
type: docs
weight: 222
url: /ru/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) method

Проверяет подпись данных.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Хэш, рассчитанный для полученных данных. |
| str | const [String](../../../system/string/)\& | Имя используемого алгоритма хеширования. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Подпись, полученная. |

### Возвращаемое значение

True если подпись действительна, false в противном случае.

## Смотрите также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)