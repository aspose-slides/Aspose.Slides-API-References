---
title: VerifySignature()
second_title: Справочник API Aspose.Slides для C++
description: Проверка подписи DSA для указанных данных.
type: docs
weight: 118
url: /ru/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) метод

Проверить подпись [DSA](../../dsa/) для указанных данных.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) подписана с помощью **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) подпись. |

### Возвращаемое значение

true - если **rgb_signature** соответствует подписи [DSA](../../dsa/), вычисленной на **rgb_hash**, иначе - false.

## См. также

* Тип [ByteArrayPtr](../../../system/bytearrayptr/)
* Класс [DSACryptoServiceProvider](../)
* Пространство имен [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)