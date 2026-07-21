---
title: Add()
second_title: Справочник API Aspose.Slides для C++
description: При переопределении в производном классе атомизирует указанную строку и добавляет её в XmlNameTable.
type: docs
weight: 14
url: /ru/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) метод

При переопределении в производном классе атомизирует указанную строку и добавляет её в [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Массив символов, содержащий имя для добавления. |
| offset | **int32_t** | Нулевой индекс в массиве, указывающий первый символ имени. |
| length | **int32_t** | Количество символов в имени. |

### Возвращаемое значение

Новая атомизированная строка или существующая, если она уже есть. Если длина равна нулю, возвращается [String::Empty](../../../system/string/empty/).

## XmlNameTable::Add(const String\&) метод

При переопределении в производном классе атомизирует указанную строку и добавляет её в [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Имя для добавления. |

### Возвращаемое значение

Новая атомизированная строка или существующая, если она уже есть.

## Смотрите также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [XmlNameTable](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)