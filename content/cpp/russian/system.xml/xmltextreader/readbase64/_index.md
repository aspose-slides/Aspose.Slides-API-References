---
title: ReadBase64()
second_title: Справочник API Aspose.Slides для C++
description: Декодирует Base64 и возвращает декодированные двоичные байты.
type: docs
weight: 768
url: /ru/system.xml/xmltextreader/readbase64/
---
## XmlTextReader::ReadBase64(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод

Декодирует Base64 и возвращает декодированные двоичные байты.

```cpp
int32_t System::Xml::XmlTextReader::ReadBase64(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив символов, служащий буфером, в который записывается текстовое содержимое. |
| offset | **int32_t** | Нулевой индекс в массиве, указывающий, с какой позиции метод может начать запись в буфер. |
| len | **int32_t** | Количество байтов, которые необходимо записать в буфер. |

### Возвращаемое значение

Количество байтов, записанных в буфер.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [XmlTextReader](../)
* Пространство имён [System::Xml](../../)
* Library [Aspose.Slides](../../../)