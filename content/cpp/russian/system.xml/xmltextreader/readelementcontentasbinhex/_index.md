---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides для C++ справка по API
description: Читает элемент и декодирует содержимое BinHex.
type: docs
weight: 677
url: /ru/system.xml/xmltextreader/readelementcontentasbinhex/
---
## XmlTextReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) метод

Читает элемент и декодирует содержимое **BinHex**.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер, в который копируется полученный текст. Это значение не может быть **nullptr**. |
| index | **int32_t** | Смещение в буфере, с которого начинать копировать результат. |
| count | **int32_t** | Максимальное количество байтов для копирования в буфер. Фактическое количество скопированных байтов возвращается этим методом. |

### Возвращаемое значение

Количество байтов, записанных в буфер.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [XmlTextReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)