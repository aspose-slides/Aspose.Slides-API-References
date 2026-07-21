---
title: ReadBinHex()
second_title: Aspose.Slides для C++ API Справка
description: Декодирует BinHex и возвращает декодированные бинарные байты.
type: docs
weight: 781
url: /ru/system.xml/xmltextreader/readbinhex/
---
## XmlTextReader::ReadBinHex(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод

Декодирует **BinHex** и возвращает декодированные бинарные байты.

```cpp
int32_t System::Xml::XmlTextReader::ReadBinHex(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив байтов, который служит буфером, в который записываются декодированные бинарные байты. |
| offset | **int32_t** | Нулевой индекс в массиве, указывающий, где метод может начать запись в буфер. |
| len | **int32_t** | Количество байтов, которое необходимо записать в буфер. |

### Возвращаемое значение

Количество байтов, записанных в ваш буфер.

## См. также

* Типedef [ArrayPtr](../../../system/arrayptr/)
* Класс [XmlTextReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)