---
title: Char
second_title: Справочник API Aspose.Slides для C++
description: Предоставляет методы для работы с символами, представленными кодовыми единицами UTF-16. Это статический тип без сервисов экземпляров. Нельзя создавать его экземпляры никакими способами.
type: docs
weight: 170
url: /ru/system/char/
---
## Класс Char

Предоставляет методы для работы с символами, представленными кодовыми единицами UTF-16. Это статический тип без сервисов экземпляров. Создавать его экземпляры никакими средствами нельзя.

```cpp
class Char
```

## Методы

| Метод | Описание |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | Преобразует кодовую единицу UTF-32 в экземпляр класса [System::String](../string/). |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Преобразует указанную пару суррогатов UTF-16 в кодовую единицу UTF-32. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | Преобразует значение символа, закодированного в UTF-16, или пары суррогатов в указанной позиции строки в кодовую единицу UTF-32. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | Преобразует указанный символ UTF-16 в числовое значение двойной точности с плавающей запятой. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | Возвращает значение, представляющее категорию Unicode указанного символа. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Определяет, классифицируется ли указанный символ как пробельный символ ASCII. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | Определяет, классифицируется ли символ по указанному индексу в указанном буфере символов как управляющий символ Unicode. |
| static **bool** [IsControl](./iscontrol/)(char_t) | Определяет, классифицируется ли указанный символ как управляющий символ Unicode. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | Определяет, классифицируется ли символ по указанному индексу в указанном буфере символов как десятичная цифра. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | Определяет, классифицируется ли символ по указанному индексу в указанной строке как десятичная цифра. |
| static **bool** [IsDigit](./isdigit/)(char_t) | Определяет, классифицируется ли указанный символ как десятичная цифра. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | Определяет, является ли символ по указанному индексу в указанной строке кодовой единицей UTF-16 высокого суррогата. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Определяет, является ли символ по указанному индексу в указанном буфере символов высоким суррогатом. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | Определяет, является ли указанный символ высоким суррогатом. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | Определяет, классифицируется ли символ по указанному индексу в указанном буфере символов как буква Unicode. |
| static **bool** [IsLetter](./isletter/)(char_t) | Определяет, классифицируется ли указанный символ как буква Unicode. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Определяет, классифицируется ли символ по указанному индексу в указанном буфере символов как буква Unicode или десятичная цифра. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | Определяет, классифицируется ли указанный символ как буква Unicode или десятичная цифра. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | Определяет, классифицируется ли символ по указанному индексу в указанном буфере символов как строчная буква. |
| static **bool** [IsLower](./islower/)(char_t) | Определяет, классифицируется ли указанный символ как строчная буква. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | Определяет, классифицируется ли символ по указанному индексу в указанной строке как строчная буква. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Определяет, является ли символ по указанному индексу в указанном буфере символов низким суррогатом. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | Определяет, является ли указанный символ низким суррогатом. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | Определяет, классифицируется ли символ по указанному индексу в указанном буфере символов как число. |
| static **bool** [IsNumber](./isnumber/)(char_t) | Определяет, классифицируется ли указанный символ как число. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | Определяет, классифицируется ли символ по указанному индексу в указанном буфере символов как символ пунктуации. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | Определяет, классифицируется ли указанный символ как символ пунктуации. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | Определяет, классифицируется ли символ по указанному индексу в указанном буфере символов как разделительный символ. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | Определяет, классифицируется ли указанный символ как разделительный символ. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | Определяет, является ли указанный символ кодовой единицей суррогата UTF-16. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | Определяет, является ли символ по указанному индексу в указанной строке кодовой единицей суррогата UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Определяет, образуют ли два указанных символа пару суррогатов UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | Определяет, образуют ли два последовательных символа в указанном буфере символов пару суррогатов. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | Определяет, классифицируется ли символ по указанному индексу в указанном буфере символов как символ. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | Определяет, классифицируется ли указанный символ как символ. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | Определяет, классифицируется ли символ по указанному индексу в указанной строке как заглавная буква. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | Определяет, классифицируется ли символ по указанному индексу в указанном буфере символов как заглавная буква. |
| static **bool** [IsUpper](./isupper/)(char_t) | Определяет, классифицируется ли указанный символ как заглавная буква. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Определяет, классифицируется ли символ по указанному индексу в указанном буфере символов как пробельный символ. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | Определяет, классифицируется ли указанный символ как пробельный символ. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | Определяет, классифицируется ли символ по указанному индексу в указанной строке как пробельный символ. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | Преобразует первый и единственный символ указанной строки в значение char_t. |
| static char_t [ToLower](./tolower/)(char_t) | Преобразует указанный символ к нижнему регистру. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Преобразует указанный символ к нижнему регистру. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | Преобразует указанный символ к нижнему регистру. |
| static char_t [ToUpper](./toupper/)(char_t) | Преобразует указанный символ к верхнему регистру. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Преобразует указанный символ к верхнему регистру. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | Преобразует указанный символ к верхнему регистру. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | Пытается преобразовать строку, состоящую из одного символа, в символ UTF-16. Функция успешна только тогда, когда входная строка не null и имеет длину ровно один символ. |

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)