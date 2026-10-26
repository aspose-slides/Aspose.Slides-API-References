---
title: VerifySignature()
second_title: Aspose.Slides для C++ справочник API
description: Проверяет подпись хеша данных.
type: docs
weight: 40
url: /ru/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) метод


Проверяет подпись хеша данных.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Хеш, вычисленный для данных. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Подпись, полученная для данных. |

### Возвращаемое значение

True если подпись действительна, false в противном случае.

## Смотрите также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RSAPKCS1SignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)