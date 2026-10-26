---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides для C++ справка по API
description: Читает элемент и декодирует содержимое Base64.
type: docs
weight: 651
url: /ru/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) метод

Читает элемент и декодирует содержимое Base64.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер, в который копируется полученный текст. Это значение не может быть **nullptr**. |
| index | **int32_t** | Смещение в буфере, с которого начинается копирование результата. |
| count | **int32_t** | Максимальное количество байтов для копирования в буфер. Фактическое количество скопированных байтов возвращается этим методом. |

### Return Value

Количество байтов, записанных в буфер.

## См. также

* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Класс [XmlTextReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)