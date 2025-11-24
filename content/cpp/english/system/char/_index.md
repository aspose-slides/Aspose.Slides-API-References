---
title: Char
second_title: Aspose.Slides for C++ API Reference
description: Provides methods for manipulation of characters represented as UTF-16 code units. This is a static type with no instance services. You should never create instances of it by any means.
type: docs
weight: 157
url: /system/char/
---
## Char class


Provides methods for manipulation of characters represented as UTF-16 code units. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Char
```

## Methods

| Method | Description |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | Converts UTF-32 code unit into an instance of [System::String](../string/) class. |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Converts the specified UTF-16 surrogate pair into UTF-32 code unit. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | Converts the value of a UTF-16 encoded character or surrogate pair at a specified position in a string into UTF-32 code unit. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | Converts the specified UTF-16 character into double-precision floating-point numerical value. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | Returns a value that represents a Unicode category of specified character. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Determines whether the specified character is classified as a ASCII white space character. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as Unicode control character. |
| static **bool** [IsControl](./iscontrol/)(char_t) | Determines whether the specified character is classified as Unicode control character. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as a decimal digit. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | Determines whether the character at the specified index in the specified string is classified as a decimal digit. |
| static **bool** [IsDigit](./isdigit/)(char_t) | Determines whether the specified character is classified as a decimal digit. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | Determines whether the character at the specified index in the specified string is UTF-16 high surrogate code unit. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is a high surrogate. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | Determines whether the specified character is a high surrogate. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as Unicode letter. |
| static **bool** [IsLetter](./isletter/)(char_t) | Determines whether the specified character is classified as Unicode letter. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as Unicode letter or a decimal digit. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | Determines whether the specified character is classified as Unicode letter or a decimal digit. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as a lower case letter. |
| static **bool** [IsLower](./islower/)(char_t) | Determines whether the specified character is classified as a lower case letter. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | Determines whether the character at the specified index in the specified string is classified as a lower case letter. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is a low surrogate. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | Determines whether the specified character is a low surrogate. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as a number. |
| static **bool** [IsNumber](./isnumber/)(char_t) | Determines whether the specified character is classified as a number. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as a punctuation character. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | Determines whether the specified character is classified as a punctuation character. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as a separator character. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | Determines whether the specified character is classified as a separator character. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | Determines if the specified character is a UTF-16 surrogate code unit. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | Determines whether the character at the specified index in the specified string is UTF-16 surrogate code unit. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Determines whether the two specified characters for a UTF-16 surrogate pair. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | Determines whether two consequent characters in the specified character buffer are a surrogate pair. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as a symbol character. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | Determines whether the specified character is classified as a symbol character. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | Determines whether the character at the specified index in the specified string is classified as an upper case letter. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as an upper case letter. |
| static **bool** [IsUpper](./isupper/)(char_t) | Determines whether the specified character is classified as an upper case letter. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Determines whether the character at the specified index in the specified character buffer is classified as a white space character. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | Determines whether the specified character is classified as a white space character. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | Determines whether the character at the specified index in the specified string is classified as a white space character. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | Converts the first and the only character of the specified string to a char_t value. |
| static char_t [ToLower](./tolower/)(char_t) | Converts the specified character to lower case. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Converts the specified character to lower case. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | Converts the specified character to lower case. |
| static char_t [ToUpper](./toupper/)(char_t) | Converts the specified character to upper case. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Converts the specified character to upper case. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | Converts the specified character to upper case. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | Tries to convert a string consisting of a single character into UTF-16 character. The function succeeds only when input string is not null and has length of exactly one character. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)