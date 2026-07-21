---
title: FindHeader()
second_title: Справочник API Aspose.Slides для C++
description: Найдите привязку заголовка по указанному типу заголовка.
type: docs
weight: 352
url: /ru/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader(System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, const TypeInfo\&) method

Найдите привязку заголовка по указанному типу заголовка.

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| headersInfo | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | Коллекция привязок заголовков. |
| headerType | const [TypeInfo](../../../system/typeinfo/)\& | Тип заголовка, который следует искать. |

### Возвращаемое значение

Привязка заголовка.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [SoapMessage](../)
* Пространство имён [System::Web::Services::Protocols](../../)
* Библиотека [Aspose.Slides](../../../)