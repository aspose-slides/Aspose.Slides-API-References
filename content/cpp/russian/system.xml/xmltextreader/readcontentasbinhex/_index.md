---
title: ReadContentAsBinHex()
second_title: Справочник API Aspose.Slides для C++
description: Читает содержимое и возвращает декодированные бинарные байты BinHex.
type: docs
weight: 664
url: /ru/system.xml/xmltextreader/readcontentasbinhex/
---
## XmlTextReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) метод

Читает содержимое и возвращает **BinHex** декодированные бинарные байты.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер, в который копируется полученный текст. Это значение не может быть **nullptr**. |
| index | **int32_t** | Смещение в буфере, с которого начинать копировать результат. |
| count | **int32_t** | Максимальное количество байтов, которое копируется в буфер. Фактическое количество скопированных байтов возвращается этим методом. |

### Возвращаемое значение

Количество байтов, записанных в буфер.

## Смотрите также

* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Класс [XmlTextReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)