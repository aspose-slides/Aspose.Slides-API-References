---
title: Decrypt()
second_title: Aspose.Slides для C++ справочник API
description: Дешифрует сообщение. Не реализовано.
type: docs
weight: 105
url: /ru/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) метод


Дешифрует сообщение. Не реализовано.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) для дешифрования. |
| use_oaep | **bool** | True to use OAEP padding, false to use PKCS#1 v1.5 padding. |

### Возвращаемое значение

Дешифрованный массив данных.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) метод


Дешифрует входные данные, используя указанный режим заполнения.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) массив для дешифрования. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Режим заполнения. |

### Возвращаемое значение

Дешифрованные данные в формате массива байтов.

## См. также

* Типовое определение [ByteArrayPtr](../../../system/bytearrayptr/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [RSACryptoServiceProvider](../)
* Класс [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Пространство имен [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)