---
title: Get()
second_title: Aspose.Slides для C++ справка API
description: Возвращает атомизированную строку с указанным значением.
type: docs
weight: 27
url: /ru/system.xml/nametable/get/
---
## NameTable::Get(const String\&) метод

Возвращает атомизированную строку с указанным значением.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Имя для поиска. |

### Возвращаемое значение

Объект атомизированной строки или **nullptr**, если строка ещё не была атомизирована.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) метод

Возвращает атомизированную строку, содержащую те же символы, что и указанный диапазон символов в заданном массиве.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Массив символов, содержащий имя для поиска. |
| start | **int32_t** | Нулевой индекс в массиве, указывающий первый символ имени. |
| len | **int32_t** | Количество символов в имени. |

### Возвращаемое значение

Атомизированная строка или **nullptr**, если строка ещё не была атомизирована. Если **len** равно нулю, возвращается [String::Empty](../../../system/string/empty/).

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [NameTable](../)
* Пространство имен [System::Xml](../../)
* Library [Aspose.Slides](../../../)