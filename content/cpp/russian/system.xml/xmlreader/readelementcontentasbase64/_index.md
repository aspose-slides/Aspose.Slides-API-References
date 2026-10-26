---
title: ReadElementContentAsBase64()
second_title: Справочник API Aspose.Slides для C++
description: Читает элемент и декодирует содержимое Base64.
type: docs
weight: 768
url: /ru/system.xml/xmlreader/readelementcontentasbase64/
---
## XmlReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


Читает элемент и декодирует содержимое **Base64**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер, в который будет копироваться полученный текст. Это значение не может быть **nullptr**. |
| index | **int32_t** | Смещение в буфере, с которого начинать копирование результата. |
| count | **int32_t** | Максимальное количество байт, которое можно скопировать в буфер. Фактическое количество скопированных байт возвращается этим методом. |

### Возвращаемое значение

Количество байт, записанных в буфер.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)