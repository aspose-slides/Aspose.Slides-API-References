---
title: TryParse()
second_title: Aspose.Slides для C++ API Reference
description: Пытается преобразовать указанную строку в эквивалентную константу перечисления.
type: docs
weight: 79
url: /ru/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) метод


Пытается преобразовать указанную строку в эквивалентную константу перечисления.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) который интерпретируется как содержащий имя константы перечисления |
| result | E\& | Параметр вывода, который при успешном преобразовании содержит результат преобразования функции |

### Return Value

True если преобразование успешно, иначе — false

## Enum::TryParse(const String\&, bool, E\&) метод


Пытается преобразовать указанную строку в эквивалентную константу перечисления.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) который интерпретируется как содержащий имя константы перечисления |
| ignoreCase | **bool** | Указывает, следует ли игнорировать регистр при интерпретации строки |
| result | E\& | Параметр вывода, который при успешном преобразовании содержит результат преобразования при возврате функции |

### Return Value

True если преобразование успешно, иначе — false

## См. также

* Класс [String](../../string/)
* Структура [Enum](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)