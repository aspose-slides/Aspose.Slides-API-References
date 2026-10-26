---
title: IsSurrogate()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, является ли указанный символ кодовой единицей суррогата UTF-16.
type: docs
weight: 14
url: /ru/system/char/issurrogate/
---
## Char::IsSurrogate(char_t) метод


Определяет, является ли указанный символ кодовой единицей суррогата UTF-16.

```cpp
static bool System::Char::IsSurrogate(char_t c)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Символ |

### Return Value

True если указанный символ является кодовой единицей суррогата UTF-16, иначе - false

## Char::IsSurrogate(const String\&, int) метод


Определяет, является ли символ в указанном индексе в указанной строке кодовой единицей суррогата UTF-16.

```cpp
static bool System::Char::IsSurrogate(const String &s, int index)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | Строка |
| index | int | Индекс символа в указанной строке |

### Return Value

True если символ в указанном индексе является кодовой единицей суррогата UTF-16, иначе - false

## See Also

* Класс [Char](../)
* Класс [String](../../string/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)