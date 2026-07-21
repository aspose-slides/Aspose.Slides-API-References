---
title: CollectHeaders()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает внутреннюю коллекцию заголовков SOAP.
type: docs
weight: 326
url: /ru/system.web.services.protocols/soapmessage/collectheaders/
---
## SoapMessage::CollectHeaders(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, SoapHeaderDirection) метод

Устанавливает внутреннюю коллекцию заголовков SOAP.

```cpp
void System::Web::Services::Protocols::SoapMessage::CollectHeaders(System::SharedPtr<Object> target, System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headers, SoapHeaderDirection direction)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| target | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Объект, из которого получать заголовки SOAP. |
| headers | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | Коллекция заголовков, из которой будет заполнена внутренняя коллекция. |
| direction | [SoapHeaderDirection](../../soapheaderdirection/) | Направление заголовка SOAP. |

## См. также

* Перечисление [SoapHeaderDirection](../../soapheaderdirection/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [Object](../../../system/object/)
* Класс [SoapMessage](../)
* Пространство имён [System::Web::Services::Protocols](../../)
* Библиотека [Aspose.Slides](../../../)