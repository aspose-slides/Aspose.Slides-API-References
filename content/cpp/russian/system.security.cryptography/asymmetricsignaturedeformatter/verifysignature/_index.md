---
title: VerifySignature()
second_title: Aspose.Slides для C++ справочник API
description: Проверяет подпись данных.
type: docs
weight: 27
url: /ru/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) метод

Проверяет подпись данных.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) подписан(а) с помощью **rgbSignature**. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Подпись, подлежащая проверке для данных. |

### Возвращаемое значение

Возвращает true, если проверка подписи прошла успешно, иначе false.

## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) метод

Проверяет подпись данных. Не реализовано.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Алгоритм, используемый для хэширования. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Подпись, подлежащая проверке для данных. |

### Возвращаемое значение

Возвращает true, если проверка подписи прошла успешно, иначе false.

## См. также

* Тип-определение [ArrayPtr](../../../system/arrayptr/)
* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [AsymmetricSignatureDeformatter](../)
* Класс [HashAlgorithm](../../hashalgorithm/)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)