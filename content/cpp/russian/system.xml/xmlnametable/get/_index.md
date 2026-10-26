---
title: Get()
second_title: Aspose.Slides для C++ справочника API
description: При переопределении в производном классе возвращает атомизированную строку, содержащую те же символы, что и указанный диапазон символов в данном массиве.
type: docs
weight: 1
url: /ru/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) метод

При переопределении в производном классе возвращает атомизированную строку, содержащую те же символы, что и указанный диапазон символов в данном массиве.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Массив символов, содержащий имя для поиска. |
| offset | **int32_t** | Нулевой индекс в массиве, указывающий первый символ имени. |
| length | **int32_t** | Количество символов в имени. |

### Возвращаемое значение

Атомизированная строка или **nullptr**, если строка еще не была атомизирована. Если **length** равно нулю, [String::Empty](../../../system/string/empty/) возвращается.

## XmlNameTable::Get(const String\&) метод

При переопределении в производном классе возвращает атомизированную строку, содержащую то же значение, что и указанная строка.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Имя для поиска. |

### Возвращаемое значение

Атомизированная строка или **nullptr**, если строка еще не была атомизирована.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)