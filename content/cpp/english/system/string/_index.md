---
title: String
second_title: Aspose.Slides for C++ API Reference
description: "String class used across the library. Is a substitute for C# System.String when translating code. For optimization reasons, isn't considered an Object subclass. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 1158
url: /system/string/
---
## String class


[String](./) class used across the library. Is a substitute for C# [System.String](./) when translating code. For optimization reasons, isn't considered an [Object](../object/) subclass. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class String
```

## Methods

| Method | Description |
| --- | --- |
| const UChar * [begin](./begin/)() const | Returns pointer to the beginning of actual string buffer. Never reallocates anything. Doesn't guarantee buffer to be null-terminated. |
| [String](./) [Clone](./clone/)() const | Creates a copy of current string. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | Less-equal-greater-compares two substrings. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Less-equal-greater-compares two substrings. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Less-equal-greater-compares two strings. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | Less-equal-greater-compares two strings. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | Less-equal-greater-compares two strings. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Less-equal-greater-compares two strings. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | Less-equal-greater-compares two strings using ordinal mode. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | Less-equal-greater-compares two strings using ordinal mode. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | Compares two strings in 'less-equals-more' style. Uses current culture. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | Concatenates strings. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | Concatenates strings. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | Concatenates strings. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | Concatenates strings. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | Checks if str is a substring of current string. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | Creates string copy. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | Copies string characters into existing array elements. No resize is being done. |
| const UChar * [end](./end/)() const | Returns pointer to the end of actual string buffer. Never reallocates anything. Doesn't guarantee buffer to be null-terminated. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | Checks if string ends with specified substring. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Checks if string ends with specified substring. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Checks if string ends with specified substring. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) equality comparison. Several modes provided by StringComparison enumeration are supported. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) equality comparison. Uses [System::StringComparison::Ordinal](../stringcomparison/) comparison mode. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Equal-compares two strings using Ordial comparison mode. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Equal-compares two strings. |
| int [FastToAscii](./fasttoascii/)(char, int) const | Tries to convert a [String](./) to an ASCII string. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | Formats string in C# style. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | Formats string in C# style. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Formats string in C# style. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | Formats string in C# style. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | Formats string in C# style. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | Creates [String](./) from ASCII string. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | Creates [String](./) from ASCII string. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | Creates [String](./) from ASCII string. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | Creates [String](./) from utf16 string. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | Creates [String](./) from utf32 string. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | Creates [String](./) from utf8 string. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | Creates [String](./) from utf8 string. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | Creates [String](./) from utf8 string. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | Creates [String](./) from utf8 string. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | Creates [String](./) from widestring. |
| int [get_Length](./get_length/)() const | Gets string length. |
| int [GetHashCode](./gethashcode/)() const | Hashes contained string. Implemented in ICU, doesn't match hashes in C#. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Substring forward lookup. |
| int [IndexOf](./indexof/)(char_t, int) const | Character forward lookup. |
| int [IndexOf](./indexof/)(char_t, int, int) const | Character forward lookup in substring. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | Substring forward lookup. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Substring forward lookup. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | Substring forward lookup. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | Substring forward lookup. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | Character forward lookup. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | Consequently looks for all characters of str in this. If first character is found, its position is returned, otherwise looks for the second one and so on. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Looks for any of passed characters through the whole string. Compares first string character to all characters in anyOf, then compares second one and so on. Returns index of the first one matching any of the target characters. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Looks for any of passed characters through substring. Compares first string character to all characters in anyOf, then compares second one and so on. Returns index of the first one matching any of the target characters. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Looks for any of passed characters through substring. Compares first string character to all characters in anyOf, then compares second one and so on. Returns index of the first one matching any of the target characters. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | Inserts substring at specified position. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Checks if string object is of type specified by [TypeInfo](../typeinfo/) passed. |
| **bool** [IsAsciiString](./isasciistring/)() const | Indicates if a [String](./) contains ASCII symbols only. |
| **bool** [IsEmpty](./isempty/)() const | Checks if string is both non-null and empty. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Checks if unicode string is normalized using normalization form specified. |
| **bool** [IsNull](./isnull/)() const | Checks if string is considered null. [String](./) is null and only if it is constructed via [String()](./string/) constructor, moved, copied or assigned from null string or [reset()](./reset/) method was called. |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | Checks if string is empty or is considered null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | Checks if passed string is null or empty. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | Indicates whether a specified string is null, empty, or consists only of white-space characters. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | Joins array using string as separator. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | Joins array using string as separator. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | Joins array using string as separator. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | Joins array using string as separator. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | Substring backward lookup. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Substring backward lookup. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Substring backward lookup. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | Substring backward lookup. |
| int [LastIndexOf](./lastindexof/)(char_t) const | Character backward lookup. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | Character backward lookup. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | Character backward lookup. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Looks for any of passed characters through whole string backwardly. Compares last string character to all characters in anyOf, then compares previous one and so on. Returns index of the first match found. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Looks for any of passed characters through substring backwardly. Compares last string character to all characters in anyOf, then compares previous one and so on. Returns index of the first match found. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Looks for any of passed characters through substring backwardly. Compares last string character to all characters in anyOf, then compares previous one and so on. Returns index of the first match found. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Normalizes unicode string using normalization form specified. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | Non-equality comparison operator. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Checks if string is not null. Applies same logic as [IsNull()](./isnull/) call. |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) concatenation operator. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) concatenation with string literal or character string pointer. |
| [String](./) [operator+](./operator_plus/)(char_t) const | Adds character to the end of the string. |
| [String](./) [operator+](./operator_plus/)(int) const | Adds integer value string representation to the end of the string. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | Adds unsigned integer value string representation to the end of the string. |
| [String](./) [operator+](./operator_plus/)(**double**) const | Adds floating point value string representation to the end of the string. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | Adds integer value string representation to the end of the string. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Adds reference type object string representation to the end of the string. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Adds reference type object string representation to the end of the string. |
| [String](./) [operator+](./operator_plus/)(T) const | Adds boolean value string representation to the end of the string. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | Concatenation assignment operator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | Concatenation assignment operator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | Concatenation assignment operator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | Concatenation assignment operator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | Concatenation assignment operator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | Concatenation assignment operator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | Concatenation assignment operator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | Concatenation assignment operator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | Concatenation assignment operator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | Concatenation assignment operator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | Concatenation assignment operator. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | Order-compares strings. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | Assignment operator. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | Move assignment operator. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | Equality comparison operator. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Checks if string is null. Applies same logic as [IsNull()](./isnull/) call. |
| char_t [operator[]](./operator[]/)(int) const | Gets character at specified position. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | Adds padding on the left of original string. |
| [String](./) [PadRight](./padright/)(int, char_t) const | Adds padding on the right of original string. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | Returns reverse iterator to the last character (if any) of actual string buffer. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | Extracts everything but substring from current string. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | Returns reverse iterator to the before first character (if any) of actual string buffer. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | Replaces all occurrences of character in the string. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | Replaces all occurrences of lookup in this string. |
| [String](./)\& [reset](./reset/)() | Sets string to null. Is analogous to 'string_variable_name = null' in C#. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | Sets character at specified position. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by character. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by character. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by one of two characters. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by one of characters specified. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by one of characters specified. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by substring. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by substring. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by substring. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by substring. Currently, only supports separators array of zero or one elements. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | Checks if string begins with specified substring. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Checks if string begins with specified substring. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Checks if string begins with specified substring. |
|  [String](./string/)() | Default constructor. Creates string object which is considered null. |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | Constructs string based on string literal. Considers literal a null-terminated string, calculates target string length based on literal size. |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | Constructs string based on character string pointer. Treats pointed string as null-terminated, calculates target string length based on null character. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | Constructs string based on string literal. Considers literal a null-terminated string in UTF8, calculates target string length based on literal size. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | Constructs string based on character string pointer. Treats pointed string as null-terminated in UTF8, calculates target string length based on null character. |
|  [String](./string/)(const char16_t *, int) | Constructs string from character string pointer and explicit length. |
|  [String](./string/)(const char *, int) | Constructs string from character string pointer and explicit length. |
|  [String](./string/)(const char16_t *, int, int) | Constructs string from character string pointer from starting position using length. |
| explicit  [String](./string/)(const char16_t, int) | Fill constructor. |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Nullptr constructor. Declared as template to resolve priorities with other template constructors. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | Constructs string based on widestring literal. Considers literal a null-terminated string, calculates target string length based on literal size. Conversion from **wchar_t** is time-consuming on some platforms, so no implicit conversions are allowed. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | Constructs string based on widecharacter string pointer. Treats pointed string as null-terminated, calculates target string length based on null character. Conversion from **wchar_t** is time-consuming on some platforms, so no implicit conversions are allowed. |
| explicit  [String](./string/)(const **wchar_t** *, int) | Constructs string from widecharacter string pointer and explicit length. Conversion from **wchar_t** is time-consuming on some platforms, so no implicit conversions are allowed. |
| explicit  [String](./string/)(const **wchar_t**, int) | Fill constructor. Conversion from **wchar_t** is time-consuming on some platforms, so no implicit conversions are allowed. |
|  [String](./string/)(const [String](./)\&) | Copy constructor. |
|  [String](./string/)([String](./)\&&) | Move constructor. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | Converts whole character array to string. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | Converts character array subrange to string. If parameters are out of array bounds, empty string is constructed. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | Wraps UnicodeString into [String](./). |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | Move constructor. |
| explicit  [String](./string/)(const std::wstring\&) | Creates [String](./) from widestring. |
| explicit  [String](./string/)(const std::u16string\&) | Creates [String](./) from utf16 string. |
| explicit  [String](./string/)(const std::string\&) | Creates [String](./) from std::string string presented in format UTF-8. |
| explicit  [String](./string/)(const std::u32string\&) | Creates [String](./) from std::u32string string. |
| [String](./) [Substring](./substring/)(**int32_t**) const | Extracts substring. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | Extracts substring. |
| std::string [ToAsciiString](./toasciistring/)() const | Converts string to std::string. Uses ASCII encoding. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | Converts string or substring to array of bytes. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | Converts string or substring to array of characters. |
| [String](./) [ToLower](./tolower/)() const | Converts all string's characters to lower case. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Converts all string's characters to lower case using specific culture. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | Converts all string's characters to lower case using invariant culture. |
| [String](./) [ToString](./tostring/)() const | Wrapper for handling [String](./) class in contexts where [ToString()](./tostring/) is being called on value type objects. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Wrapper for handling [String](./) class in contexts where [ToString()](./tostring/) is being called on value type objects. |
| std::u16string [ToU16Str](./tou16str/)() const | Converts string to std::u16string. |
| std::u32string [ToU32Str](./tou32str/)() const | Converts string to std::u32string. |
| [String](./) [ToUpper](./toupper/)() const | Converts all string's characters to upper case. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Converts all string's characters to upper case using specific culture. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | Converts all string's characters to upper case using invariant culture. |
| std::string [ToUtf8String](./toutf8string/)() const | Converts string to std::string. Uses UTF-8 encoding. |
| std::wstring [ToWCS](./towcs/)() const | Converts string to std::wstring. |
| [String](./) [Trim](./trim/)() const | Removes all whitespace characters from both beginning and end of the string. |
| [String](./) [Trim](./trim/)(char_t) const | Removes all occurrences of passed character from both beginning and end of the string. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | Removes all occurrences of passed characters from both beginning and end of the string. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Removes all occurrences of passed characters from both beginning and end of the string. |
| [String](./) [TrimEnd](./trimend/)() const | Removes all whitespace characters from end of the string. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | Removes all occurrences of passed character from end of the string. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | Removes all occurrences of passed characters from end of the string. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Removes all occurrences of passed characters from end of the string. |
| [String](./) [TrimStart](./trimstart/)() const | Removes all whitespace characters from beginning of the string. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | Removes all occurrences of passed character from beginning of the string. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | Removes all occurrences of passed characters from beginning of the string. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Removes all occurrences of passed characters from beginning of the string. |
| const UChar * [u_str](./u_str/)() const | Returns ICU-styled null-terminated buffer. May reallocate the string. |
|  [~String](./~string/)() | Destructor. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Empty string. |
| static [Null](./null/) | Null string. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Reverse iterator type. |
## Remarks



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Construct a string from the array of characters and print it.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Construct a string from the array of bytes and print it.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Trim the string below and print it.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Print the number of words in the .
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
This code example produces the following output:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)