---
title: DigitalSignature class
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/digitalsignature/
---
## DigitalSignature класс

Электронная подпись в подписанном файле.

Тип DigitalSignature предоставляет следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/ru/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | Создаёт новый объект DigitalSignature с указанным сертификатом. |
| [`__init__(self, file_path, password)`](/slides/python-net/ru/aspose.slides/digitalsignature/__init__/#str-str) | Создаёт новый объект DigitalSignature с указанным путём к файлу сертификата и паролем. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`certificate`](/slides/python-net/ru/aspose.slides/digitalsignature/certificate/) | Объект сертификата, использованный для подписи документа.<br/>            Только для чтения **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/ru/aspose.slides/digitalsignature/is_valid/) | Если эта цифровая подпись действительна и документ не был подделан, это значение будет true.<br/>            Только для чтения **bool**. |
| [`sign_time`](/slides/python-net/ru/aspose.slides/digitalsignature/sign_time/) | Время, когда документ был подписан.<br/>            Только для чтения **System.DateTime**. |
| [`comments`](/slides/python-net/ru/aspose.slides/digitalsignature/comments/) | Назначение подписи.<br/>            Чтение/запись **str**. |


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)