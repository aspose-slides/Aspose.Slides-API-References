---
title: Add()
second_title: Aspose.Slides для C++ справочник API
description: Атомизирует указанную строку и добавляет её в NameTable.
type: docs
weight: 14
url: /ru/system.xml/nametable/add/
---
## NameTable::Add(const String\&) метод

Атомизирует указанную строку и добавляет её в [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | Строка для добавления. |

### Возвращаемое значение

Атомизированная строка или существующая строка, если она уже присутствует в [NameTable](../).

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) метод

Атомизирует указанную строку и добавляет её в [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Массив символов, содержащий строку для добавления. |
| start | **int32_t** | Нулевой индекс массива, указывающий первый символ строки. |
| len | **int32_t** | Количество символов в строке. |

### Возвращаемое значение

Атомизированная строка или существующая строка, если она уже присутствует в [NameTable](../). Если **len** равен нулю, возвращается [String::Empty](../../../system/string/empty/).

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [NameTable](../)
* Пространство имен [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)