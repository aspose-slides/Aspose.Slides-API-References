---
title: VerifySignature()
second_title: Справочник API Aspose.Slides для C++
description: Проверить подпись DSA для указанных данных.
type: docs
weight: 14
url: /ru/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) метод

Проверьте подпись [DSA](../) для указанных данных.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) подписан с помощью **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) подпись. |

### Возвращаемое значение

true - если **rgb_signature** совпадает с подписью [DSA](../), вычисленной по **rgb_hash**, иначе - false.

## Смотрите также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Класс [DSA](../)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)