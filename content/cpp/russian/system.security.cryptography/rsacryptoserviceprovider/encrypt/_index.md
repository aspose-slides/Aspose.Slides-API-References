---
title: Encrypt()
second_title: Aspose.Slides для C++ справочник API
description: Шифрует сообщение. Не реализовано.
type: docs
weight: 118
url: /ru/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) метод

Шифрует сообщение. Не реализовано.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) для шифрования. |
| use_oaep | **bool** | True для использования заполнения OAEP, false для использования заполнения PKCS#1 v1.5. |

### Возвращаемое значение

Массив зашифрованных данных.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) метод

Шифрует вводимые данные, используя указанный режим заполнения.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) массив для шифрования. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Режим заполнения. |

### Возвращаемое значение

Зашифрованные данные в формате массива байтов.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSACryptoServiceProvider](../)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)