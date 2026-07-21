---
title: Decrypt()
second_title: Aspose.Slides для C++ справочника API
description: Расшифровывает входные данные, используя указанный режим заполнения.
type: docs
weight: 27
url: /ru/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method

Расшифровывает входные данные, используя указанный режим заполнения.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) массив для расшифровки. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Режим заполнения. |

### Return Value

Расшифрованные данные в формате массива байтов.

## See Also

* Тип [ByteArrayPtr](../../../system/bytearrayptr/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Класс [RSA](../)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)