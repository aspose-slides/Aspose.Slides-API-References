---
title: HexUnescape()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует указанное шестнадцатеричное представление символа в символ.
type: docs
weight: 443
url: /ru/system/uri/hexunescape/
---
## Uri::HexUnescape(const String\&, int32_t\&) метод

Преобразует указанное шестнадцатеричное представление символа в символ.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | Строка, содержащая шестнадцатеричное представление символа |
| index | **int32_t**\& | Позиция в **pattern**, где начинается шестнадцатеричное представление символа |

### Return Value

Символ, представленный шестнадцатеричным кодированием в позиции **index**. Если символ в позиции **index** не закодирован в шестнадцатеричном виде, возвращается символ из позиции **index**. Значение **index** увеличивается, указывая на символ, следующий за возвращённым.

## See Also

* Класс [String](../../string/)
* Класс [Uri](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)