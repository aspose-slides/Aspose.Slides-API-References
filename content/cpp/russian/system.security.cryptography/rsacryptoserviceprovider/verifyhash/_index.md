---
title: VerifyHash()
second_title: Справочник API Aspose.Slides для C++
description: Проверяет подпись данных.
type: docs
weight: 222
url: /ru/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) метод

Проверяет подпись данных.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Хеш, рассчитанный для полученных данных. |
| str | const [String](../../../system/string/)\& | Имя используемого алгоритма хеша. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Подпись в полученном виде. |

### Возвращаемое значение

True if signature is valid, false otherwise.

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) метод

Проверяет, действительна ли подпись указанного хеша.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Значение хеша подписанных данных. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Данные подписи. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Алгоритм хеша. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Режим заполнения. возвращает true, если подпись действительна, иначе - false. |

## См. также

* Типовое определение [ByteArrayPtr](../../../system/bytearrayptr/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [RSACryptoServiceProvider](../)
* Класс [RSASignaturePadding](../../rsasignaturepadding/)
* Структура [HashAlgorithmName](../../hashalgorithmname/)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)