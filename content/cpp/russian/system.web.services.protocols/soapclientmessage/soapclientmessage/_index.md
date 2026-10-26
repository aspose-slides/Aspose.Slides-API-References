---
title: SoapClientMessage()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новый экземпляр.
type: docs
weight: 66
url: /ru/system.web.services.protocols/soapclientmessage/soapclientmessage/
---
## SoapClientMessage::SoapClientMessage(System::SharedPtr\<SoapHttpClientProtocol\>, System::SharedPtr\<SoapMethodStubInfo\>, String, System::ArrayPtr\<System::SharedPtr\<Object\>\>) конструктор

Создаёт новый экземпляр.

```cpp
System::Web::Services::Protocols::SoapClientMessage::SoapClientMessage(System::SharedPtr<SoapHttpClientProtocol> client, System::SharedPtr<SoapMethodStubInfo> msi, String url, System::ArrayPtr<System::SharedPtr<Object>> parameters)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| client | [System::SharedPtr](../../../system/sharedptr/)\<[SoapHttpClientProtocol](../../soaphttpclientprotocol/)\> | Экземпляр класса прокси-клиента. |
| msi | [System::SharedPtr](../../../system/sharedptr/)\<SoapMethodStubInfo\> | Информация о заглушке метода. |
| url | [String](../../../system/string/) | URL XML-веб-службы. |
| parameters | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Коллекция параметров. |

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [SoapHttpClientProtocol](../../soaphttpclientprotocol/)
* Класс [String](../../../system/string/)
* Класс [Object](../../../system/object/)
* Класс [SoapClientMessage](../)
* Пространство имён [System::Web::Services::Protocols](../../)
* Библиотека [Aspose.Slides](../../../)