---
title: VerifyHash()
second_title: Aspose.Slides для C++ справочник API
description: Проверяет подпись данных.
type: docs
weight: 118
url: /ru/system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash(ByteArrayPtr, ByteArrayPtr) method

Проверяет подпись данных.

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Хеш, вычисленный для полученных данных. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Подпись как получена. |

### Возвращаемое значение

Истина, если подпись действительна, иначе ложь.

## См. также

* Тип-определение [ByteArrayPtr](../../../system/bytearrayptr/)
* Класс [ECDsa](../)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)