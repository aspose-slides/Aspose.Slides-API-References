---
title: ReadContentAsBinHex()
second_title: Справочник API Aspose.Slides для C++
description: Читает содержимое и возвращает двоичные байты, декодированные из BinHex.
type: docs
weight: 456
url: /ru/system.xml/xmlnodereader/readcontentasbinhex/
---
## XmlNodeReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) метод

Читает содержимое и возвращает двоичные байты, декодированные из BinHex.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер, в который будет копироваться полученный текст. Это значение не может быть **nullptr**. |
| index | **int32_t** | Смещение в буфере, с которого начинается копирование результата. |
| count | **int32_t** | Максимальное количество байтов для копирования в буфер. Фактическое количество скопированных байтов возвращается этим методом. |

### Возвращаемое значение

Количество байтов, записанных в буфер.

## Смотрите также

* typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [XmlNodeReader](../)
* Пр пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)