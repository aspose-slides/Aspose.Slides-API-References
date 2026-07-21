---
title: ReadContentAsBase64()
second_title: Aspose.Slides для C++ справка API
description: Читает содержимое и возвращает двоичные байты, декодированные из Base64.
type: docs
weight: 443
url: /ru/system.xml/xmlnodereader/readcontentasbase64/
---
## XmlNodeReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) метод

Читает содержимое и возвращает двоичные байты, декодированные из Base64.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер, в который копировать полученный текст. Это значение не может быть **nullptr**. |
| index | **int32_t** | Смещение в буфере, с которого начинать копировать результат. |
| count | **int32_t** | Максимальное количество байтов для копирования в буфер. Фактическое количество скопированных байтов возвращается этим методом. |

### Возвращаемое значение

Количество байтов, записанных в буфер.

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [XmlNodeReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)