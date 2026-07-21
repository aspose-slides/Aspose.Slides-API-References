---
title: ReadContentAsBase64()
second_title: Справочник API Aspose.Slides для C++
description: Считывает содержимое и возвращает бинарные байты, декодированные из Base64.
type: docs
weight: 755
url: /ru/system.xml/xmlreader/readcontentasbase64/
---
## XmlReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) метод

Считывает содержимое и возвращает бинарные байты, декодированные из Base64.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер, в который копируется полученный текст. Это значение не может быть **nullptr**. |
| index | **int32_t** | Смещение в буфере, с которого начинать копировать результат. |
| count | **int32_t** | Максимальное количество байтов, которое можно скопировать в буфер. Фактическое количество скопированных байтов возвращается этим методом. |

### Возвращаемое значение

Количество байтов, записанных в буфер.

## См. также

* typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)