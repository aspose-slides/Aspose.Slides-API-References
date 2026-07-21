---
title: ReadElementContentAsBinHex()
second_title: Справочник API Aspose.Slides для C++
description: Читает элемент и декодирует содержимое BinHex.
type: docs
weight: 794
url: /ru/system.xml/xmlreader/readelementcontentasbinhex/
---
## XmlReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) метод

Читает элемент и декодирует содержимое **BinHex**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер, в который копируется полученный текст. Это значение не может быть **nullptr**. |
| index | **int32_t** | Смещение в буфере, с которого начинать копировать результат. |
| count | **int32_t** | Максимальное количество байтов, которое можно скопировать в буфер. Фактическое количество скопированных байтов возвращается этим методом. |

### Возвращаемое значение

Количество байтов, записанных в буфер.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [XmlReader](../)
* Пространство имен [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)