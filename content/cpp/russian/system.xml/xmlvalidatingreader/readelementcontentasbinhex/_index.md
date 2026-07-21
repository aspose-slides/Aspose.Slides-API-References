---
title: ReadElementContentAsBinHex()
second_title: Справочник API Aspose.Slides для C++
description: Читает элемент и декодирует содержимое BinHex.
type: docs
weight: 612
url: /ru/system.xml/xmlvalidatingreader/readelementcontentasbinhex/
---
## XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


Читает элемент и декодирует содержимое BinHex.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер, в который копируется полученный текст. Это значение не может быть **nullptr**. |
| index | **int32_t** | Смещение в буфере, с которого начинается копирование результата. |
| count | **int32_t** | Максимальное количество байтов для копирования в буфер. Фактическое количество скопированных байтов возвращается этим методом. |

### Возвращаемое значение

Количество байтов, записанных в буфер.

## Смотрите также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [XmlValidatingReader](../)
* Пространство имён [System::Xml](../../)
* Library [Aspose.Slides](../../../)