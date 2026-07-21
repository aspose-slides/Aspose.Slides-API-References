---
title: VerifyHash()
second_title: Aspose.Slides для C++ справочник API
description: Проверяет подпись данных.
type: docs
weight: 183
url: /ru/system.security.cryptography/ecdsabotan/verifyhash/
---
## ECDsaBotan::VerifyHash(ByteArrayPtr, ByteArrayPtr) метод


Проверяет подпись данных.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Хеш, рассчитанный для полученных данных. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Подпись получена. |

### Возвращаемое значение

Истина, если подпись действительна, иначе ложь.

## См. также

* Тип [ByteArrayPtr](../../../system/bytearrayptr/)
* Класс [ECDsaBotan](../)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)