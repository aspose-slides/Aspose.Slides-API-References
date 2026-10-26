---
title: SoapParameterStyle
second_title: Справочник API Aspose.Slides для C++
description: Перечисляет форматы параметров в SOAP-сообщении.
type: docs
weight: 183
url: /ru/system.web.services.protocols/soapparameterstyle/
---
## SoapParameterStyle enum

Перечисляет форматы параметров в SOAP-сообщении.

```cpp
enum class SoapParameterStyle
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Default | 0 | Если к классу не применён '[SoapDocumentServiceAttribute](../soapdocumentserviceattribute/)', то значение по умолчанию — 'Wrapped'. |
| Bare | 1 | Параметры размещаются в XML-элементах, которые следуют за элементом 'Body'. |
| Wrapped | 2 | Параметры инкапсулируются в один XML-элемент, который следует за элементом 'Body'. |

## Смотрите также

* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.Slides](../../)