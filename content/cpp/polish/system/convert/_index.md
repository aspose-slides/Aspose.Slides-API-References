---
title: Convert
second_title: Referencja API Aspose.Slides dla C++
description: "Struktura zawierająca metody wykonujące konwersję wartości jednego typu na wartości innego typu. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 1561
url: /pl/system/convert/
---
## Struktura konwersji

Struktura zawierająca metody wykonujące konwersję wartości jednego typu na wartości innego typu. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy [System::SmartPtr](../smartptr/) do zarządzania obiektami tego typu.

```cpp
class Convert
```

## Metody

| Method | Description |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | NIE ZAIMPLEMENTOWANO. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Dekoduje dane zakodowane w base-64 reprezentowane jako zakres w tablicy znaków Unicode. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | Dekoduje dane zakodowane w base-64 reprezentowane jako ciąg znaków. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Zwraca wartość TypeCode reprezentującą typ określonej wartości w pudełku. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | NIE ZAIMPLEMENTOWANO. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | NIE ZAIMPLEMENTOWANO Fałszywa implementacja, sprawdza, czy wartość jest nullptr. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | Koduje w base-64 zakres elementów w określonej tablicy bajtów i zapisuje zakodowane dane jako tablicę znaków Unicode. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | Koduje w base-64 zakres elementów w określonej tablicy bajtów i zapisuje zakodowane dane jako tablicę znaków Unicode. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | Koduje w base-64 elementy w określonej tablicy bajtów i zwraca zakodowane dane jako ciąg znaków. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | Koduje w base-64 zakres elementów w określonej tablicy bajtów i zwraca zakodowane dane jako ciąg znaków. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | Koduje w base-64 elementy w określonej tablicy bajtów i zwraca zakodowane dane jako ciąg znaków. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | Koduje w base-64 zakres elementów w określonej tablicy bajtów i zwraca zakodowane dane jako ciąg znaków. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | Zwraca określoną wartość logiczną. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | Konwertuje określoną 8-bitową liczbę całkowitą bez znaku na równoważną wartość logiczną. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | Konwertuje określoną 8-bitową liczbę całkowitą ze znakiem na równoważną wartość logiczną. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | Konwertuje określoną 16-bitową liczbę całkowitą bez znaku na równoważną wartość logiczną. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | Konwertuje określoną 16-bitową liczbę całkowitą ze znakiem na równoważną wartość logiczną. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | Konwertuje określoną 32-bitową liczbę całkowitą bez znaku na równoważną wartość logiczną. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | Konwertuje określoną 32-bitową liczbę całkowitą ze znakiem na równoważną wartość logiczną. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | Konwertuje określoną 64-bitową liczbę całkowitą bez znaku na równoważną wartość logiczną. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | Konwertuje określoną 64-bitową liczbę całkowitą ze znakiem na równoważną wartość logiczną. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | Konwertuje określoną liczbę zmiennoprzecinkową float na równoważną wartość logiczną. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | Konwertuje określoną liczbę zmiennoprzecinkową double na równoważną wartość logiczną. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | Konwertuje określoną liczbę dziesiętną na równoważną wartość logiczną. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | Konwertuje określony pusty ciąg znaków na równoważną wartość logiczną. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | Konwertuje określony ciąg znaków typu C na wartość typu bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | Konwertuje określony ciąg znaków na wartość typu bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określony ciąg znaków na wartość typu bool. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość w pudełku na równoważną wartość logiczną. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | Konwertuje określoną wartość logiczną na równoważną 8-bitową liczbę całkowitą bez znaku. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | Zwraca określoną 8-bitową liczbę całkowitą bez znaku. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | Konwertuje określoną 8-bitową liczbę całkowitą ze znakiem na równoważną 8-bitową liczbę całkowitą bez znaku. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | Konwertuje określoną 16-bitową liczbę całkowitą bez znaku na równoważną 8-bitową liczbę całkowitą bez znaku. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | Konwertuje określoną 16-bitową liczbę całkowitą ze znakiem na równoważną 8-bitową liczbę całkowitą bez znaku. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | Konwertuje określoną 32-bitową liczbę całkowitą bez znaku na równoważną 8-bitową liczbę całkowitą bez znaku. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | Konwertuje określoną 32-bitową liczbę całkowitą ze znakiem na równoważną 8-bitową liczbę całkowitą bez znaku. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | Konwertuje określoną 64-bitową liczbę całkowitą bez znaku na równoważną 8-bitową liczbę całkowitą bez znaku. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | Konwertuje określoną 64-bitową liczbę całkowitą ze znakiem na równoważną 8-bitową liczbę całkowitą bez znaku. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | Konwertuje określoną liczbę zmiennoprzecinkową float na równoważną 8-bitową liczbę całkowitą bez znaku. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | Konwertuje określoną liczbę zmiennoprzecinkową double na równoważną 8-bitową liczbę całkowitą bez znaku. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | Konwertuje określoną liczbę dziesiętną na równoważną 8-bitową liczbę całkowitą bez znaku. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | Konwertuje określony znak Unicode na równoważną 8-bitową liczbę całkowitą bez znaku. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | Konwertuje określony pusty ciąg znaków na równoważną wartość bez znaku 8-bitowej liczby całkowitej. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | Konwertuje określony ciąg znaków typu C zawierający reprezentację liczby na równoważną wartość bez znaku 8-bitowej liczby całkowitej. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | Konwertuje określony ciąg znaków zawierający reprezentację liczby na równoważną wartość bez znaku 8-bitowej liczby całkowitej. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | Konwertuje określony ciąg znaków zawierający reprezentację liczby w określonej podstawie na równoważną wartość bez znaku 8-bitowej liczby całkowitej. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określony ciąg znaków zawierający reprezentację liczby na równoważną wartość bez znaku 8-bitowej liczby całkowitej, wykorzystując podane informacje o formatowaniu. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określony ciąg znaków zawierający reprezentację liczby na równoważną wartość bez znaku 8-bitowej liczby całkowitej, wykorzystując podane informacje o formatowaniu i stylu liczby. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość w pudełku na równoważną wartość bez znaku 8-bitowej liczby całkowitej. |
| static char_t [ToChar](./tochar/)(**bool**) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | Konwertuje określoną 8-bitową liczbę całkowitą bez znaku na równoważny znak Unicode. |
| static char_t [ToChar](./tochar/)(**int8_t**) | Konwertuje określoną 8-bitową liczbę całkowitą ze znakiem na równoważny znak Unicode. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | Konwertuje określoną 16-bitową liczbę całkowitą bez znaku na równoważny znak Unicode. |
| static char_t [ToChar](./tochar/)(**int16_t**) | Konwertuje określoną 16-bitową liczbę całkowitą ze znakiem na równoważny znak Unicode. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | Konwertuje określoną 32-bitową liczbę całkowitą bez znaku na równoważny znak Unicode. |
| static char_t [ToChar](./tochar/)(**int32_t**) | Konwertuje określoną 32-bitową liczbę całkowitą ze znakiem na równoważny znak Unicode. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | Konwertuje określoną 64-bitową liczbę całkowitą bez znaku na równoważny znak Unicode. |
| static char_t [ToChar](./tochar/)(**int64_t**) | Konwertuje określoną 64-bitową liczbę całkowitą ze znakiem na równoważny znak Unicode. |
| static char_t [ToChar](./tochar/)(**float**) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static char_t [ToChar](./tochar/)(**double**) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | Zwraca określony znak Unicode. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static char_t [ToChar](./tochar/)(const char_t *) | Konwertuje pierwszy i jedyny znak określonego ciągu c-string na wartość typu char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | Konwertuje pierwszy i jedyny znak określonego ciągu znaków na wartość typu char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje pierwszy i jedyny znak określonego ciągu znaków na wartość typu char_t. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość w pudełku na równoważny znak Unicode. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | Konwersja nie jest obsługiwana. Zawsze zgłasza wyjątek InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | Konwersja nie jest obsługiwana. Zawsze zgłasza wyjątek InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | Konwersja nie jest obsługiwana. Zawsze zgłasza wyjątek InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | Konwersja nie jest obsługiwana. Zawsze zgłasza wyjątek InvalidCastException. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | Zwraca określoną datę i godzinę. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | Konwertuje podany ciąg znaków na instancję klasy [DateTime](../datetime/). |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg znaków na instancję klasy [DateTime](../datetime/) używając podanych informacji formatowania. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podaną wartość opakowaną na równoważną wartość [DateTime](../datetime/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | Konwertuje podaną wartość logiczną na równoważną liczbę dziesiętną. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | Konwertuje podaną 8-bitową liczbę całkowitą bez znaku na równoważną liczbę dziesiętną. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | Konwertuje podaną 8-bitową liczbę całkowitą ze znakiem na równoważną liczbę dziesiętną. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | Konwertuje podaną 16-bitową liczbę całkowitą bez znaku na równoważną liczbę dziesiętną. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | Konwertuje podaną 16-bitową liczbę całkowitą ze znakiem na równoważną liczbę dziesiętną. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | Konwertuje podaną 32-bitową liczbę całkowitą bez znaku na równoważną liczbę dziesiętną. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | Konwertuje podaną 32-bitową liczbę całkowitą ze znakiem na równoważną liczbę dziesiętną. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | Konwertuje podaną 64-bitową liczbę całkowitą bez znaku na równoważną liczbę dziesiętną. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | Konwertuje podaną 64-bitową liczbę całkowitą ze znakiem na równoważną liczbę dziesiętną. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | Konwertuje podaną liczbę zmiennoprzecinkową (float) na równoważną liczbę dziesiętną. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | Konwertuje podaną liczbę podwójnej precyzji (double) na równoważną liczbę dziesiętną. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | Zwraca określoną liczbę dziesiętną. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | Konwersja nie jest obsługiwana. Zawsze zgłasza wyjątek InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | Konwersja nie jest obsługiwana. Zawsze zgłasza wyjątek InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | Konwertuje podany null-string na równoważną wartość [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | Konwertuje podany c-string zawierający reprezentację liczby jako ciąg znaków na równoważną wartość [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość [Decimal](../decimal/) używając podanych informacji formatowania. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość [Decimal](../decimal/) używając określonych stylów liczbowych i informacji formatowania. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podaną wartość opakowaną na równoważną wartość [Decimal](../decimal/). |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | Konwertuje podaną wartość logiczną na równoważną liczbę zmiennoprzecinkową podwójnej precyzji. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | Konwertuje podaną 8-bitową liczbę całkowitą bez znaku na równoważną liczbę zmiennoprzecinkową podwójnej precyzji. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | Konwertuje podaną 8-bitową liczbę całkowitą ze znakiem na równoważną liczbę zmiennoprzecinkową podwójnej precyzji. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | Konwertuje podaną 16-bitową liczbę całkowitą bez znaku na równoważną liczbę zmiennoprzecinkową podwójnej precyzji. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | Konwertuje podaną 16-bitową liczbę całkowitą ze znakiem na równoważną liczbę zmiennoprzecinkową podwójnej precyzji. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | Konwertuje podaną 32-bitową liczbę całkowitą bez znaku na równoważną liczbę zmiennoprzecinkową podwójnej precyzji. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | Konwertuje podaną 32-bitową liczbę całkowitą ze znakiem na równoważną liczbę zmiennoprzecinkową podwójnej precyzji. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | Konwertuje podaną 64-bitową liczbę całkowitą bez znaku na równoważną liczbę zmiennoprzecinkową podwójnej precyzji. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | Konwertuje podaną 64-bitową liczbę całkowitą ze znakiem na równoważną liczbę zmiennoprzecinkową podwójnej precyzji. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | Konwertuje podaną liczbę zmiennoprzecinkową (float) na równoważną liczbę zmiennoprzecinkową podwójnej precyzji. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | Zwraca określoną liczbę podwójnej precyzji. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | Konwertuje podaną liczbę dziesiętną na równoważną liczbę zmiennoprzecinkową podwójnej precyzji. |
| static **double** [ToDouble](./todouble/)(char_t) | Konwersja nie jest obsługiwana. Zawsze zgłasza wyjątek InvalidCastException. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | Konwersja nie jest obsługiwana. Zawsze zgłasza wyjątek InvalidCastException. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | Konwertuje podany null-string na równoważną wartość zmiennoprzecinkową podwójnej precyzji. |
| static **double** [ToDouble](./todouble/)(const char_t *) | Konwertuje podany c-string zawierający reprezentację liczby jako ciąg znaków na równoważną wartość zmiennoprzecinkową podwójnej precyzji. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową podwójnej precyzji. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową podwójnej precyzji używając podanych informacji formatowania. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną wartość zmiennoprzecinkową podwójnej precyzji używając podanych informacji formatowania i stylu liczbowego. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podaną wartość opakowaną na wartość zmiennoprzecinkową podwójnej precyzji. Jeśli typ wartości opakowanej jest [String](../string/), podczas konwersji używany jest podany format ciągu znaków. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | Konwertuje podaną wartość logiczną na równoważną 16-bitową liczbę całkowitą ze znakiem. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | Konwertuje podaną 8-bitową liczbę całkowitą bez znaku na równoważną 16-bitową liczbę całkowitą ze znakiem. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | Konwertuje podaną 8-bitową liczbę całkowitą ze znakiem na równoważną 16-bitową liczbę całkowitą ze znakiem. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | Konwertuje podaną 16-bitową liczbę całkowitą bez znaku na równoważną 16-bitową liczbę całkowitą ze znakiem. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | Zwraca określoną 16-bitową liczbę całkowitą ze znakiem. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | Konwertuje podaną 32-bitową liczbę całkowitą bez znaku na równoważną 16-bitową liczbę całkowitą ze znakiem. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | Konwertuje podaną 32-bitową liczbę całkowitą ze znakiem na równoważną 16-bitową liczbę całkowitą ze znakiem. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | Konwertuje podaną 64-bitową liczbę całkowitą bez znaku na równoważną 16-bitową liczbę całkowitą ze znakiem. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | Konwertuje podaną 64-bitową liczbę całkowitą ze znakiem na równoważną 16-bitową liczbę całkowitą ze znakiem. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | Konwertuje podaną liczbę zmiennoprzecinkową (float) na równoważną 16-bitową liczbę całkowitą ze znakiem. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | Konwertuje podaną liczbę podwójnej precyzji (double) na równoważną 16-bitową liczbę całkowitą ze znakiem. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | Konwertuje podaną liczbę dziesiętną na równoważną 16-bitową liczbę całkowitą ze znakiem. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | Konwertuje podany znak Unicode na równoważną 16-bitową liczbę całkowitą ze znakiem. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | Konwersja nie jest obsługiwana. Zawsze zgłasza wyjątek InvalidCastException. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | Konwertuje podany null-string na równoważną wartość 16-bitową. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | Konwertuje podany c-string zawierający reprezentację liczby jako ciąg znaków na równoważną 16-bitową wartość. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 16-bitową wartość. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | Konwertuje podany ciąg znaków zawierający reprezentację liczby w określonej podstawie na równoważną 16-bitową wartość. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 16-bitową wartość używając podanych informacji formatowania. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 16-bitową wartość używając podanych informacji formatowania i stylu liczbowego. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podaną wartość opakowaną na równoważną 16-bitową wartość całkowitą. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | Konwertuje podaną wartość logiczną na równoważną 32-bitową liczbę całkowitą ze znakiem. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | Konwertuje podaną 8-bitową liczbę całkowitą bez znaku na równoważną 32-bitową liczbę całkowitą ze znakiem. |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | Konwertuje podany 8-bitowy całkowity ze znakiem na równoważny 32-bitowy całkowity ze znakiem. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | Konwertuje podany 16-bitowy całkowity bez znaku na równoważny 32-bitowy całkowity ze znakiem. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | Konwertuje podany 16-bitowy całkowity ze znakiem na równoważny 32-bitowy całkowity ze znakiem. |
| static int [ToInt32](./toint32/)(**uint32_t**) | Konwertuje podany 32-bitowy całkowity bez znaku na równoważny 32-bitowy całkowity ze znakiem. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | Zwraca podany 32-bitowy całkowity ze znakiem. |
| static int [ToInt32](./toint32/)(**uint64_t**) | Konwertuje podany 64-bitowy całkowity bez znaku na równoważny 32-bitowy całkowity ze znakiem. |
| static int [ToInt32](./toint32/)(**int64_t**) | Konwertuje podany 64-bitowy całkowity ze znakiem na równoważny 32-bitowy całkowity ze znakiem. |
| static int [ToInt32](./toint32/)(**float**) | Konwertuje podaną liczbę zmiennoprzecinkową (float) na równoważny 32-bitowy całkowity ze znakiem. |
| static int [ToInt32](./toint32/)(**double**) | Konwertuje podaną liczbę zmiennoprzecinkową (double) na równoważny 32-bitowy całkowity ze znakiem. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | Konwertuje podaną liczbę dziesiętną na równoważny 32-bitowy całkowity ze znakiem. |
| static constexpr int [ToInt32](./toint32/)(char_t) | Konwertuje podany znak Unicode na równoważny 32-bitowy całkowity ze znakiem. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | Konwertuje podany null-string na równoważną 32-bitową wartość całkowitą. |
| static int [ToInt32](./toint32/)(const char_t *) | Konwertuje podany ciąg znaków C-string zawierający reprezentację liczby na równoważną 32-bitową wartość całkowitą. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 32-bitową wartość całkowitą. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | Konwertuje podany ciąg znaków zawierający reprezentację liczby w określonej podstawie na równoważną 32-bitową wartość całkowitą. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 32-bitową wartość całkowitą, używając podanych informacji formatowania. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 32-bitową wartość całkowitą, używając podanych informacji formatowania i stylu liczby. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podaną wartość opakowaną (boxed) na równoważną 32-bitową wartość całkowitą. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | Konwertuje podaną wartość logiczną (bool) na równoważny 64-bitowy całkowity ze znakiem. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | Konwertuje podany 8-bitowy całkowity bez znaku na równoważny 64-bitowy całkowity ze znakiem. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | Konwertuje podany 8-bitowy całkowity ze znakiem na równoważny 64-bitowy całkowity ze znakiem. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | Konwertuje podany 16-bitowy całkowity bez znaku na równoważny 64-bitowy całkowity ze znakiem. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | Konwertuje podany 16-bitowy całkowity ze znakiem na równoważny 64-bitowy całkowity ze znakiem. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | Konwertuje podany 32-bitowy całkowity bez znaku na równoważny 64-bitowy całkowity ze znakiem. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | Konwertuje podany 32-bitowy całkowity ze znakiem na równoważny 64-bitowy całkowity ze znakiem. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | Konwertuje podany 64-bitowy całkowity bez znaku na równoważny 64-bitowy całkowity ze znakiem. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | Zwraca podany 64-bitowy całkowity ze znakiem. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | Konwertuje podaną liczbę zmiennoprzecinkową (float) na równoważny 64-bitowy całkowity ze znakiem. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | Konwertuje podaną liczbę zmiennoprzecinkową (double) na równoważny 64-bitowy całkowity ze znakiem. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | Konwertuje podaną liczbę dziesiętną na równoważny 64-bitowy całkowity ze znakiem. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | Konwertuje podany znak Unicode na równoważny 64-bitowy całkowity ze znakiem. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | Konwertuje podany null-string na równoważną 64-bitową wartość całkowitą. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | Konwertuje podany ciąg znaków C-string zawierający reprezentację liczby na równoważną 64-bitową wartość całkowitą. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 64-bitową wartość całkowitą. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | Konwertuje podany ciąg znaków zawierający reprezentację liczby w określonej podstawie na równoważną 64-bitową wartość całkowitą. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 64-bitową wartość całkowitą, używając podanych informacji formatowania. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 64-bitową wartość całkowitą, używając podanych informacji formatowania i stylu liczby. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podaną wartość opakowaną (boxed) na równoważną 64-bitową wartość całkowitą. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | Konwertuje podaną wartość logiczną (bool) na równoważny 8-bitowy całkowity ze znakiem. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | Konwertuje podany 8-bitowy całkowity bez znaku na równoważny 8-bitowy całkowity ze znakiem. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | Zwraca podany 8-bitowy całkowity ze znakiem. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | Konwertuje podany 16-bitowy całkowity bez znaku na równoważny 8-bitowy całkowity ze znakiem. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | Konwertuje podany 16-bitowy całkowity ze znakiem na równoważny 8-bitowy całkowity ze znakiem. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | Konwertuje podany 32-bitowy całkowity bez znaku na równoważny 8-bitowy całkowity ze znakiem. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | Konwertuje podany 32-bitowy całkowity ze znakiem na równoważny 8-bitowy całkowity ze znakiem. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | Konwertuje podany 64-bitowy całkowity bez znaku na równoważny 8-bitowy całkowity ze znakiem. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | Konwertuje podany 64-bitowy całkowity ze znakiem na równoważny 8-bitowy całkowity ze znakiem. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | Konwertuje podaną liczbę zmiennoprzecinkową (float) na równoważny 8-bitowy całkowity ze znakiem. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | Konwertuje podaną liczbę zmiennoprzecinkową (double) na równoważny 8-bitowy całkowity ze znakiem. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | Konwertuje podaną liczbę dziesiętną na równoważny 8-bitowy całkowity ze znakiem. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | Konwertuje podany znak Unicode na równoważny 8-bitowy całkowity ze znakiem. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | Konwertuje podany null-string na równoważną 8-bitową wartość całkowitą. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | Konwertuje podany ciąg znaków C-string zawierający reprezentację liczby na równoważną 8-bitową wartość całkowitą. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 8-bitową wartość całkowitą. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | Konwertuje podany ciąg znaków zawierający reprezentację liczby w określonej podstawie na równoważną 8-bitową wartość całkowitą. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną bez znaku 8-bitową wartość całkowitą, używając podanych informacji formatowania. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany ciąg znaków zawierający reprezentację liczby na równoważną 8-bitową wartość całkowitą, używając podanych informacji formatowania i stylu liczby. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podaną wartość opakowaną (boxed) na równoważną 8-bitową wartość całkowitą. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | Konwertuje podaną wartość logiczną (bool) na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji (float). |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | Konwertuje podany 8-bitowy całkowity bez znaku na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji (float). |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | Konwertuje podany 8-bitowy całkowity ze znakiem na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji (float). |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | Konwertuje podany 16-bitowy całkowity bez znaku na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji (float). |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | Konwertuje podany 16-bitowy całkowity ze znakiem na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji (float). |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | Konwertuje podany 32-bitowy całkowity bez znaku na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji (float). |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | Konwertuje podany 32-bitowy całkowity ze znakiem na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji (float). |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | Konwertuje określoną 64-bitową liczbę całkowitą bez znaku na równoważną liczbę zmiennoprzecinkową pojedynczej precyzji. |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | Konwertuje określoną 64-bitową liczbę całkowitą ze znakiem na równoważną liczbę zmiennoprzecinkową pojedynczej precyzji. |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | Zwraca określoną liczbę zmiennoprzecinkową typu float. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | Konwertuje określoną liczbę podwójnej precyzji na równoważną liczbę zmiennoprzecinkową pojedynczej precyzji. |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | Konwertuje określoną liczbę dziesiętną na równoważną liczbę zmiennoprzecinkową pojedynczej precyzji. |
| static **float** [ToSingle](./tosingle/)(char_t) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | Konwertuje określony null-string na równoważną wartość zmiennoprzecinkową pojedynczej precyzji. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | Konwertuje określony ciąg znaków C zawierający reprezentację liczbową na równoważną wartość zmiennoprzecinkową pojedynczej precyzji. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | Konwertuje określony ciąg znaków zawierający reprezentację liczbową na równoważną wartość zmiennoprzecinkową pojedynczej precyzji. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określony ciąg znaków zawierający reprezentację liczbową na równoważną wartość zmiennoprzecinkową pojedynczej precyzji przy użyciu podanych informacji formatowania. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określony ciąg znaków zawierający reprezentację liczbową na równoważną wartość zmiennoprzecinkową pojedynczej precyzji przy użyciu podanych informacji formatowania i stylu liczby. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość opakowaną (boxed) na wartość zmiennoprzecinkową pojedynczej precyzji. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków. |
| static [String](../string/) [ToString](./tostring/)(**float**) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków. |
| static [String](../string/) [ToString](./tostring/)(**double**) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na łańcuch znaków przy użyciu informacji o formacie specyficznym dla kultury. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na łańcuch znaków przy użyciu informacji o formacie specyficznym dla kultury. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na łańcuch znaków przy użyciu informacji o formacie specyficznym dla kultury. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na łańcuch znaków przy użyciu informacji o formacie specyficznym dla kultury. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na łańcuch znaków przy użyciu informacji o formacie specyficznym dla kultury. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na łańcuch znaków przy użyciu informacji o formacie specyficznym dla kultury. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na łańcuch znaków przy użyciu informacji o formacie specyficznym dla kultury. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na łańcuch znaków przy użyciu informacji o formacie specyficznym dla kultury. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na łańcuch znaków przy użyciu informacji o formacie specyficznym dla kultury. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na łańcuch znaków przy użyciu informacji o formacie specyficznym dla kultury. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na łańcuch znaków przy użyciu informacji o formacie specyficznym dla kultury. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na łańcuch znaków przy użyciu informacji o formacie specyficznym dla kultury. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków przy użyciu określonego formatu ciągu znaków oraz informacji o formacie specyficznym dla kultury, dostarczonych przez określony obiekt [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków przy użyciu określonego formatu ciągu znaków oraz informacji o formacie specyficznym dla kultury, dostarczonych przez określony obiekt [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków przy użyciu określonego formatu ciągu znaków oraz informacji o formacie specyficznym dla kultury, dostarczonych przez określony obiekt [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków przy użyciu określonego formatu ciągu znaków oraz informacji o formacie specyficznym dla kultury, dostarczonych przez określony obiekt [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków przy użyciu określonego formatu ciągu znaków oraz informacji o formacie specyficznym dla kultury, dostarczonych przez określony obiekt [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość na jej reprezentację w postaci łańcucha znaków przy użyciu określonego formatu ciągu znaków oraz informacji o formacie specyficznym dla kultury, dostarczonych przez określony obiekt [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |   |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podaną wartość na jej reprezentację tekstową przy użyciu określonego formatu łańcucha oraz informacji o formacie specyficznym dla kultury, dostarczonych przez określony obiekt [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podaną wartość na jej reprezentację tekstową przy użyciu określonego formatu łańcucha oraz informacji o formacie specyficznym dla kultury, dostarczonych przez określony obiekt [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podaną wartość na jej reprezentację tekstową przy użyciu określonego formatu łańcucha oraz informacji o formacie specyficznym dla kultury, dostarczonych przez określony obiekt [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podaną wartość na jej reprezentację tekstową przy użyciu określonego formatu łańcucha oraz informacji o formacie specyficznym dla kultury, dostarczonych przez określony obiekt [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podaną wartość na jej reprezentację tekstową przy użyciu określonego formatu łańcucha oraz informacji o formacie specyficznym dla kultury, dostarczonych przez określony obiekt [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podaną wartość na jej reprezentację tekstową przy użyciu określonego formatu łańcucha oraz informacji o formacie specyficznym dla kultury, dostarczonych przez określony obiekt [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | Konwertuje podaną wartość na ciąg znaków. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | Konwertuje podaną wartość na ciąg znaków przy użyciu określonego formatu łańcucha. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | Konwertuje określoną tablicę znaków Unicode na ciąg znaków. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną tablicę znaków Unicode na ciąg znaków przy użyciu informacji o formacie specyficznym dla kultury, dostarczonych przez określony obiekt [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | Zwraca podaną wartość; nie wykonywana jest konwersja. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Zwraca podaną wartość; nie wykonywana jest konwersja. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Zwraca podaną wartość; nie wykonywana jest konwersja. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Zwraca podaną wartość; nie wykonywana jest konwersja. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | Zwraca podaną wartość; nie wykonywana jest konwersja. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Zwraca podaną wartość; nie wykonywana jest konwersja. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Zwraca podaną wartość; nie wykonywana jest konwersja. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Zwraca podaną wartość; nie wykonywana jest konwersja. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Zwraca podaną wartość; nie wykonywana jest konwersja. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | Zwraca podaną wartość; nie wykonywana jest konwersja. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | Konwertuje podaną wartość na jej reprezentację tekstową. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podaną wartość na jej reprezentację tekstową. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Konwertuje podaną wartość na jej reprezentację tekstową. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Konwertuje podaną wartość na jej reprezentację tekstową. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podaną wartość na jej reprezentację tekstową. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Konwertuje podaną wartość na jej reprezentację tekstową. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | Konwertuje podaną wartość na jej reprezentację tekstową. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | Konwertuje podaną wartość całkowitą na jej reprezentację tekstową w określonej podstawie. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | Konwertuje podaną wartość całkowitą na jej reprezentację tekstową w określonej podstawie. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | Konwertuje podaną wartość całkowitą na jej reprezentację tekstową w określonej podstawie. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | Konwertuje podaną wartość całkowitą na jej reprezentację tekstową w określonej podstawie. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje opakowaną wartość na jej reprezentację tekstową. Jeśli typ opakowanej wartości jest [String](../string/), podczas konwersji używany jest określony format łańcucha. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | Konwertuje podaną wartość logiczną na równoważną 16-bitową liczbę całkowitą bez znaku. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | Konwertuje podaną 8-bitową liczbę całkowitą bez znaku na równoważną 16-bitową liczbę całkowitą bez znaku. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | Konwertuje podaną 8-bitową liczbę całkowitą ze znakiem na równoważną 16-bitową liczbę całkowitą bez znaku. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | Zwraca podaną 16-bitową liczbę całkowitą bez znaku. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | Konwertuje podaną 16-bitową liczbę całkowitą ze znakiem na równoważną 16-bitową liczbę całkowitą bez znaku. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | Konwertuje podaną 32-bitową liczbę całkowitą bez znaku na równoważną 16-bitową liczbę całkowitą bez znaku. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | Konwertuje podaną 32-bitową liczbę całkowitą ze znakiem na równoważną 16-bitową liczbę całkowitą bez znaku. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | Konwertuje podaną 64-bitową liczbę całkowitą bez znaku na równoważną 16-bitową liczbę całkowitą bez znaku. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | Konwertuje podaną 64-bitową liczbę całkowitą ze znakiem na równoważną 16-bitową liczbę całkowitą bez znaku. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | Konwertuje podaną liczbę typu float na równoważną 16-bitową liczbę całkowitą bez znaku. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | Konwertuje podaną liczbę typu double na równoważną 16-bitową liczbę całkowitą bez znaku. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | Konwertuje podaną liczbę dziesiętną na równoważną 16-bitową liczbę całkowitą bez znaku. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | Konwertuje podany znak Unicode na równoważną 16-bitową liczbę całkowitą bez znaku. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | Konwersja nie jest obsługiwana. Zawsze zgłasza wyjątek InvalidCastException. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | Konwertuje podany ciąg null na równoważną wartość 16-bitowej liczby całkowitej bez znaku. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | Konwertuje podany łańcuch C zawierający tekstową reprezentację liczby na równoważną wartość 16-bitowej liczby całkowitej bez znaku. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | Konwertuje podany łańcuch zawierający tekstową reprezentację liczby na równoważną wartość 16-bitowej liczby całkowitej bez znaku. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | Konwertuje podany łańcuch zawierający tekstową reprezentację liczby w określonej podstawie na równoważną wartość 16-bitowej liczby całkowitej bez znaku. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany łańcuch zawierający tekstową reprezentację liczby na równoważną wartość 16-bitowej liczby całkowitej bez znaku przy użyciu dostarczonych informacji o formatowaniu. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje podany łańcuch zawierający tekstową reprezentację liczby na równoważną wartość 16-bitowej liczby całkowitej bez znaku przy użyciu dostarczonych informacji o formatowaniu oraz stylu liczby. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje opakowaną wartość na równoważną wartość 16-bitowej liczby całkowitej bez znaku. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | Konwertuje podaną wartość logiczną na równoważną 32-bitową liczbę całkowitą bez znaku. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | Konwertuje podaną 8-bitową liczbę całkowitą bez znaku na równoważną 32-bitową liczbę całkowitą bez znaku. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | Konwertuje podaną 8-bitową liczbę całkowitą ze znakiem na równoważną 32-bitową liczbę całkowitą bez znaku. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | Konwertuje podaną 16-bitową liczbę całkowitą bez znaku na równoważną 32-bitową liczbę całkowitą bez znaku. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | Konwertuje podaną 16-bitową liczbę całkowitą ze znakiem na równoważną 32-bitową liczbę całkowitą bez znaku. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | Zwraca podaną 32-bitową liczbę całkowitą bez znaku. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | Konwertuje określoną 32-bitową liczbę całkowitą ze znakiem na równoważną 32-bitową liczbę całkowitą bez znaku. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | Konwertuje określoną 64-bitową liczbę całkowitą bez znaku na równoważną 32-bitową liczbę całkowitą bez znaku. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | Konwertuje określoną 64-bitową liczbę całkowitą ze znakiem na równoważną 32-bitową liczbę całkowitą bez znaku. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | Konwertuje określoną liczbę zmiennoprzecinkową typu float na równoważną 32-bitową liczbę całkowitą bez znaku. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | Konwertuje określoną liczbę zmiennoprzecinkową typu double na równoważną 32-bitową liczbę całkowitą bez znaku. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | Konwertuje określoną liczbę dziesiętną na równoważną 32-bitową liczbę całkowitą bez znaku. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | Konwertuje określony znak Unicode na równoważną 32-bitową liczbę całkowitą bez znaku. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | Konwertuje określony null-string na równoważną wartość 32-bitowej liczby całkowitej bez znaku. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | Konwertuje określony c-string zawierający tekstową reprezentację liczby na równoważną wartość 32-bitowej liczby całkowitej bez znaku. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | Konwertuje określony string zawierający tekstową reprezentację liczby na równoważną wartość 32-bitowej liczby całkowitej bez znaku. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | Konwertuje określony string zawierający tekstową reprezentację liczby w określonej podstawie na równoważną wartość 32-bitowej liczby całkowitej bez znaku. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określony string zawierający tekstową reprezentację liczby na równoważną wartość 32-bitowej liczby całkowitej bez znaku przy użyciu podanych informacji o formatowaniu. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określony string zawierający tekstową reprezentację liczby na równoważną wartość 32-bitowej liczby całkowitej bez znaku przy użyciu podanych informacji o formatowaniu i stylu liczby. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość opakowaną (boxed) na równoważną wartość 32-bitowej liczby całkowitej bez znaku. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | Konwertuje określoną wartość logiczną (bool) na równoważną 64-bitową liczbę całkowitą bez znaku. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | Konwertuje określoną 8-bitową liczbę całkowitą bez znaku na równoważną 64-bitową liczbę całkowitą bez znaku. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | Konwertuje określoną 8-bitową liczbę całkowitą ze znakiem na równoważną 64-bitową liczbę całkowitą bez znaku. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | Konwertuje określoną 16-bitową liczbę całkowitą bez znaku na równoważną 64-bitową liczbę całkowitą bez znaku. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | Konwertuje określoną 16-bitową liczbę całkowitą ze znakiem na równoważną 64-bitową liczbę całkowitą bez znaku. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | Konwertuje określoną 32-bitową liczbę całkowitą bez znaku na równoważną 64-bitową liczbę całkowitą bez znaku. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | Konwertuje określoną 32-bitową liczbę całkowitą ze znakiem na równoważną 64-bitową liczbę całkowitą bez znaku. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | Zwraca określoną 64-bitową liczbę całkowitą bez znaku. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | Konwertuje określoną 64-bitową liczbę całkowitą ze znakiem na równoważną 64-bitową liczbę całkowitą bez znaku. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | Konwertuje określoną liczbę zmiennoprzecinkową typu float na równoważną 64-bitową liczbę całkowitą bez znaku. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | Konwertuje określoną liczbę zmiennoprzecinkową typu double na równoważną 64-bitową liczbę całkowitą bez znaku. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | Konwertuje określoną liczbę dziesiętną na równoważną 64-bitową liczbę całkowitą bez znaku. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | Konwertuje określony znak Unicode na równoważną 64-bitową liczbę całkowitą bez znaku. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | Konwertuje określony null-string na równoważną wartość 64-bitowej liczby całkowitej bez znaku. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | Konwertuje określony c-string zawierający tekstową reprezentację liczby na równoważną wartość 64-bitowej liczby całkowitej bez znaku. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | Konwertuje określony string zawierający tekstową reprezentację liczby na równoważną wartość 64-bitowej liczby całkowitej bez znaku. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | Konwertuje określony string zawierający tekstową reprezentację liczby w określonej podstawie na równoważną wartość 64-bitowej liczby całkowitej bez znaku. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określony string zawierający tekstową reprezentację liczby na równoważną wartość 64-bitowej liczby całkowitej bez znaku przy użyciu podanych informacji o formatowaniu. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określony string zawierający tekstową reprezentację liczby na równoważną wartość 64-bitowej liczby całkowitej bez znaku przy użyciu podanych informacji o formatowaniu i stylu liczby. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje określoną wartość opakowaną (boxed) na równoważną wartość 64-bitowej liczby całkowitej bez znaku. |
## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)