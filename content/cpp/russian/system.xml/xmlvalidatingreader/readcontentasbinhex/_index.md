---
title: ReadContentAsBinHex()
second_title: Справочник API Aspose.Slides для C++
description: Читает содержимое и возвращает двоичные байты, декодированные из BinHex.
type: docs
weight: 599
url: /ru/system.xml/xmlvalidatingreader/readcontentasbinhex/
---
## XmlValidatingReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) метод


Читает содержимое и возвращает двоичные байты, декодированные из BinHex.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер, в который копируется полученный текст. Это значение не может быть **nullptr**. |
| index | **int32_t** | Смещение в буфере, с которого начинается копирование результата. |
| count | **int32_t** | Максимальное количество байт для копирования в буфер. Фактическое количество скопированных байт возвращается этим методом. |

### Возвращаемое значение

Количество байт, записанных в буфер.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [XmlValidatingReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)