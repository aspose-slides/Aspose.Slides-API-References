---
title: String
second_title: Aspose.Slides pro C++ - reference API
description: "Třída String používaná v celé knihovně. Je náhradou za C# System.String při překladu kódu. Z důvodů optimalizace není považována za podtřídu Object. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo odkazem. Nikdy nepoužívejte třídu System::SmartPtr k správě objektů tohoto typu."
type: docs
weight: 1275
url: /cs/system/string/
---
## Třída String


[String](./) třída used across the library. Is a substitute for C# [System.String](./) when translating code. For optimization reasons, isn't considered an [Object](../object/) subclass. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class String
```

## Metody

| Metoda | Popis |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) je typ hodnoty na straně C++ který implicitně (bez dědičnosti) implementuje některá rozhraní. |
| const UChar * [begin](./begin/)() const | Vrací ukazatel na začátek aktuálního bufferu řetězce. Nikdy nealokuje znovu nic. Není zaručeno, že je buffer ukončen nulovým znakem. |
| [String](./) [Clone](./clone/)() const | Vytvoří kopii aktuálního řetězce. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | Porovnává dva podřetězce. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Porovnává dva podřetězce. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Porovnává dva řetězce. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | Porovnává dva řetězce. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | Porovnává dva řetězce. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Porovnává dva řetězce. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | Porovnává dva řetězce v ordinálním režimu. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | Porovnává dva řetězce v ordinálním režimu. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | Porovnává dva řetězce ve stylu 'méně-rovných-víc'. Používá aktuální kulturu. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | Spojuje řetězce. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | Spojuje řetězce. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | Spojuje řetězce. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | Spojuje řetězce. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | Kontroluje, zda je str podřetězcem aktuálního řetězce. |
| **bool** [Contains](./contains/)(char16_t) const | Kontroluje, zda řetězec obsahuje zadaný znak. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | Vytvoří kopii řetězce. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | Kopíruje znaky řetězce do existujících prvků pole. Změna velikosti se neprovádí. |
| const UChar * [end](./end/)() const | Vrací ukazatel na konec aktuálního bufferu řetězce. Nikdy nealokuje znovu nic. Není zaručeno, že je buffer ukončen nulovým znakem. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | Kontroluje, zda řetězec končí zadaným podřetězcem. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Kontroluje, zda řetězec končí zadaným podřetězcem. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Kontroluje, zda řetězec končí zadaným podřetězcem. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) srovnání rovnosti. Podporuje několik režimů poskytovaných výčtem StringComparison. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) srovnání rovnosti. Používá režim porovnání [System::StringComparison::Ordinal](../stringcomparison/). |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Porovnává dva řetězce pomocí ordinálního režimu porovnání. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Porovnává dva řetězce. |
| int [FastToAscii](./fasttoascii/)(char, int) const | Pokouší se převést [String](./) na ASCII řetězec. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | Formátuje řetězec ve stylu C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | Formátuje řetězec ve stylu C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Formátuje řetězec ve stylu C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | Formátuje řetězec ve stylu C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | Formátuje řetězec ve stylu C#. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | Vytváří [String](./) z ASCII řetězce. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | Vytváří [String](./) z ASCII řetězce. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | Vytváří [String](./) z ASCII řetězce. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | Vytváří [String](./) z utf16 řetězce. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | Vytváří [String](./) z utf32 řetězce. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | Vytváří [String](./) z utf8 řetězce. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | Vytváří [String](./) z utf8 řetězce. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | Vytváří [String](./) z utf8 řetězce. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | Vytváří [String](./) z utf8 řetězce. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | Vytváří [String](./) z widestringu. |
| int [get_Length](./get_length/)() const | Získává délku řetězce. |
| int [GetHashCode](./gethashcode/)() const | Vytváří hash obsaženého řetězce. Implementováno v ICU, neodpovídá hashům v C#. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Vyhledává podřetězec dopředu. |
| int [IndexOf](./indexof/)(char_t, int) const | Vyhledává znak dopředu. |
| int [IndexOf](./indexof/)(char_t, int, int) const | Vyhledává znak v podřetězci dopředu. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | Vyhledává podřetězec dopředu. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Vyhledává podřetězec dopředu. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | Vyhledává podřetězec dopředu. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | Vyhledává podřetězec dopředu. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | Vyhledává znak dopředu. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | Hledá postupně všechny znaky str v tomto řetězci. Pokud je nalezen první znak, vrátí se jeho pozice, jinak hledá druhý a tak dále. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Prohledává celý řetězec na výskyt libovolného z předaných znaků. Porovnává první znak řetězce se všemi znaky v anyOf, poté druhý a tak dále. Vrací index prvního shodujícího se s některým z cílových znaků. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Prohledává podřetězec na výskyt libovolného z předaných znaků. Porovnává první znak podřetězce se všemi znaky v anyOf, poté druhý a tak dále. Vrací index prvního shodujícího se s některým z cílových znaků. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Prohledává podřetězec na výskyt libovolného z předaných znaků. Porovnává první znak podřetězce se všemi znaky v anyOf, poté druhý a tak dále. Vrací index prvního shodujícího se s některým z cílových znaků. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | Vkládá podřetězec na určenou pozici. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Kontroluje, zda je objekt řetězce typu určeného předaným [TypeInfo](../typeinfo/). |
| **bool** [IsAsciiString](./isasciistring/)() const | Ukazuje, zda [String](./) obsahuje pouze ASCII znaky. |
| **bool** [IsEmpty](./isempty/)() const | Kontroluje, zda řetězec není null a je prázdný. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Kontroluje, zda je unicode řetězec normalizován pomocí zadané normalizační formy. |
| **bool** [IsNull](./isnull/)() const | Kontroluje, zda je řetězec považován za null. [String](./) je null pouze pokud byl vytvořen pomocí konstruktoru [String()](./string/), byl přesunut, zkopírován nebo přiřazen z null řetězce či byla volána metoda [reset()](./reset/). |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | Kontroluje, zda je řetězec prázdný nebo je považován za null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | Kontroluje, zda je předaný řetězec null nebo prázdný. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | Ukazuje, zda je zadaný řetězec null, prázdný nebo se skládá pouze z bílých znaků. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | Spojuje pole pomocí řetězce jako oddělovače. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | Spojuje pole pomocí řetězce jako oddělovače. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | Spojuje pole pomocí řetězce jako oddělovače. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | Spojuje pole pomocí řetězce jako oddělovače. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | Vyhledává podřetězec zpětně. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Vyhledává podřetězec zpětně. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Vyhledává podřetězec zpětně. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | Vyhledává podřetězec zpětně. |
| int [LastIndexOf](./lastindexof/)(char_t) const | Vyhledává znak zpětně. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | Vyhledává znak zpětně. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | Vyhledává znak zpětně. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Prohledává celý řetězec na výskyt libovolného z předaných znaků zpětně. Porovnává poslední znak řetězce se všemi znaky v anyOf, poté předchozí a tak dále. Vrací index prvního shodujícího se s některým z cílových znaků. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Prohledává podřetězec na výskyt libovolného z předaných znaků zpětně. Porovnává poslední znak podřetězce se všemi znaky v anyOf, poté předchozí a tak dále. Vrací index prvního shodujícího se s některým z cílových znaků. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Prohledává podřetězec na výskyt libovolného z předaných znaků zpětně. Porovnává poslední znak podřetězce se všemi znaky v anyOf, poté předchozí a tak dále. Vrací index prvního shodujícího se s některým z cílových znaků. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Normalizuje unicode řetězec pomocí zadané normalizační formy. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | Převádí řetězec na jen pro čtení span. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | Operátor nerovnosti. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Kontroluje, zda řetězec není null. Používá stejnou logiku jako volání [IsNull()](./isnull/). |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) operátor konkatenace. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) konkatenace s literálem řetězce nebo ukazatelem na řetězec znaků. |
| [String](./) [operator+](./operator_plus/)(char_t) const | Přidá znak na konec řetězce. |
| [String](./) [operator+](./operator_plus/)(int) const | Přidá řetězcovou reprezentaci celočíselné hodnoty na konec řetězce. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | Přidá řetězcovou reprezentaci nezáporné celočíselné hodnoty na konec řetězce. |
| [String](./) [operator+](./operator_plus/)(**double**) const | Přidá řetězcovou reprezentaci desetinného čísla na konec řetězce. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | Přidá řetězcovou reprezentaci celočíselné hodnoty na konec řetězce. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Přidá řetězcovou reprezentaci objektu referenčního typu na konec řetězce. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Přidá řetězcovou reprezentaci objektu referenčního typu na konec řetězce. |
| [String](./) [operator+](./operator_plus/)(T) const | Přidá řetězcovou reprezentaci logické hodnoty na konec řetězce. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | Operátor přiřazení konkatenace. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | Operátor přiřazení konkatenace. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | Operátor přiřazení konkatenace. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | Operátor přiřazení konkatenace.
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | Operátor přiřazení konkatenace. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | Operátor přiřazení konkatenace. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | Operátor přiřazení konkatenace. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | Operátor přiřazení konkatenace. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | Operátor přiřazení konkatenace. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | Operátor přiřazení konkatenace. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | Operátor přiřazení konkatenace. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | Porovnává řetězce podle pořadí. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | Operátor přiřazení. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | Operátor přiřazení přesunutím. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | Operátor porovnání rovnosti. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Kontroluje, zda je řetězec nulový. Používá stejnou logiku jako volání [IsNull()](./isnull/). |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | Porovnává řetězce podle pořadí. |
| char_t [operator[]](./operator[]/)(int) const | Získá znak na zadané pozici. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | Přidá odsazení vlevo od původního řetězce. |
| [String](./) [PadRight](./padright/)(int, char_t) const | Přidá odsazení vpravo od původního řetězce. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | Vrací reverzní iterátor na poslední znak (je-li) skutečného bufferu řetězce. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | Extrahuje vše kromě podřetězce z aktuálního řetězce. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | Vrací reverzní iterátor na před první znak (je-li) skutečného bufferu řetězce. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | Nahradí všechny výskyty znaku v řetězci. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | Nahradí všechny výskyty hledání v tomto řetězci. |
| [String](./)\& [reset](./reset/)() | Nastaví řetězec na null. Je analogické k 'string_variable_name = null' v C#. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | Nastaví znak na zadané pozici. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | Rozdělí řetězec podle znaku. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Rozdělí řetězec podle znaku. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | Rozdělí řetězec podle jednoho ze dvou znaků. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Rozdělí řetězec podle jednoho ze zadaných znaků. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Rozdělí řetězec podle jednoho ze zadaných znaků. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | Rozdělí řetězec podle podřetězce. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Rozdělí řetězec podle podřetězce. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Rozdělí řetězec podle podřetězce. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Rozdělí řetězec podle podřetězce. V současné době podporuje pole oddělovačů o délce nula nebo jedna. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | Kontroluje, zda řetězec začíná zadaným podřetězcem. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Kontroluje, zda řetězec začíná zadaným podřetězcem. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Kontroluje, zda řetězec začíná zadaným podřetězcem. |
|  [String](./string/)() | Výchozí konstruktor. Vytvoří objekt řetězce, který je považován za null. |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | Vytvoří řetězec na základě literálu řetězce. Považuje literál za řetězec ukončený nulovým znakem, vypočítá cílovou délku řetězce na základě velikosti literálu. |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | Vytvoří řetězec na základě ukazatele na znakový řetězec. Považuje ukazovaný řetězec za nulou ukončený, vypočítá cílovou délku řetězce na základě nulového znaku. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | Vytvoří řetězec na základě literálu řetězce. Považuje literál za řetězec ukončený nulou v UTF8, vypočítá cílovou délku řetězce na základě velikosti literálu. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | Vytvoří řetězec na základě ukazatele na znakový řetězec. Považuje ukazovaný řetězec za nulou ukončený v UTF8, vypočítá cílovou délku řetězce na základě nulového znaku. |
|  [String](./string/)(const char16_t *, int) | Vytvoří řetězec z ukazatele na znakový řetězec a explicitní délky. |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | Inicializuje novou instanci třídy [System.String](./) na Unicode znaky uvedené ve specifikovaném pouze pro čtení úseku. |
|  [String](./string/)(const char *, int) | Vytvoří řetězec z ukazatele na znakový řetězec a explicitní délky. |
|  [String](./string/)(const char16_t *, int, int) | Vytvoří řetězec z ukazatele na znakový řetězec od počáteční pozice pomocí délky. |
| explicit  [String](./string/)(const char16_t, int) | Konstruktor vyplnění. |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Konstruktor nullptr. Deklarován jako šablona pro vyřešení priorit s ostatními šablonovými konstruktory. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | Vytvoří řetězec na základě literálu widestring. Považuje literál za řetězec ukončený nulou, vypočítá cílovou délku řetězce na základě velikosti literálu. Převod z **wchar_t** je na některých platformách časově náročný, takže nejsou povoleny implicitní konverze. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | Vytvoří řetězec na základě ukazatele na široký znakový řetězec. Považuje ukazovaný řetězec za nulou ukončený, vypočítá cílovou délku řetězce na základě nulového znaku. Převod z **wchar_t** je na některých platformách časově náročný, takže nejsou povoleny implicitní konverze. |
| explicit  [String](./string/)(const **wchar_t** *, int) | Vytvoří řetězec z ukazatele na široký znakový řetězec a explicitní délky. Převod z **wchar_t** je na některých platformách časově náročný, takže nejsou povoleny implicitní konverze. |
| explicit  [String](./string/)(const **wchar_t**, int) | Konstruktor vyplnění. Převod z **wchar_t** je na některých platformách časově náročný, takže nejsou povoleny implicitní konverze. |
|  [String](./string/)(const [String](./)\&) | Kopírovací konstruktor. |
|  [String](./string/)([String](./)\&&) | Přesouvací konstruktor. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | Převede celý pole znaků na řetězec. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | Převede podrozsah pole znaků na řetězec. Pokud jsou parametry mimo hranice pole, je vytvořen prázdný řetězec. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | Zabaluje UnicodeString do [String](./). |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | Přesouvací konstruktor. |
| explicit  [String](./string/)(const std::wstring\&) | Vytvoří [String](./) z widestringu. |
| explicit  [String](./string/)(const std::u16string\&) | Vytvoří [String](./) z utf16 řetězce. |
| explicit  [String](./string/)(const std::string\&) | Vytvoří [String](./) ze std::string řetězce prezentovaného ve formátu UTF-8. |
| explicit  [String](./string/)(const std::u32string\&) | Vytvoří [String](./) ze std::u32string řetězce. |
| [String](./) [Substring](./substring/)(**int32_t**) const | Extrahuje podřetězec. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | Extrahuje podřetězec. |
| std::string [ToAsciiString](./toasciistring/)() const | Převede řetězec na std::string. Používá ASCII kódování. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | Převede řetězec nebo podřetězec na pole bajtů. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | Převede řetězec nebo podřetězec na pole znaků. |
| [String](./) [ToLower](./tolower/)() const | Převede všechny znaky řetězce na malá písmena. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Převede všechny znaky řetězce na malá písmena pomocí specifické kultury. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | Převede všechny znaky řetězce na malá písmena pomocí invariantní kultury. |
| [String](./) [ToString](./tostring/)() const | Obal pro zpracování třídy [String](./) v kontextech, kde je [ToString()](./tostring/) voláno na objektech typu hodnota. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Obal pro zpracování třídy [String](./) v kontextech, kde je [ToString()](./tostring/) voláno na objektech typu hodnota. |
| std::u16string [ToU16Str](./tou16str/)() const | Převede řetězec na std::u16string. |
| std::u32string [ToU32Str](./tou32str/)() const | Převede řetězec na std::u32string. |
| [String](./) [ToUpper](./toupper/)() const | Převede všechny znaky řetězce na velká písmena. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Převede všechny znaky řetězce na velká písmena pomocí specifické kultury. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | Převede všechny znaky řetězce na velká písmena pomocí invariantní kultury. |
| std::string [ToUtf8String](./toutf8string/)() const | Převede řetězec na std::string. Používá kódování UTF-8. |
| std::wstring [ToWCS](./towcs/)() const | Převede řetězec na std::wstring. |
| [String](./) [Trim](./trim/)() const | Odstraní všechny bílé znaky z počátku i konce řetězce. |
| [String](./) [Trim](./trim/)(char_t) const | Odstraní všechny výskyty zadaného znaku z počátku i konce řetězce. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | Odstraní všechny výskyty zadaných znaků z počátku i konce řetězce. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Odstraní všechny výskyty zadaných znaků z počátku i konce řetězce. |
| [String](./) [TrimEnd](./trimend/)() const | Odstraní všechny bílé znaky z konce řetězce. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | Odstraní všechny výskyty zadaného znaku z konce řetězce. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | Odstraní všechny výskyty zadaných znaků z konce řetězce. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Odstraní všechny výskyty zadaných znaků z konce řetězce. |
| [String](./) [TrimStart](./trimstart/)() const | Odstraní všechny bílé znaky z počátku řetězce. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | Odstraní všechny výskyty zadaného znaku z počátku řetězce. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | Odstraňuje všechny výskyty zadaných znaků z počátku řetězce. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Odstraňuje všechny výskyty zadaných znaků z počátku řetězce. |
| const UChar * [u_str](./u_str/)() const | Vrací buffer ukončený nulou ve stylu ICU. Může realokovat řetězec. |
|  [~String](./~string/)() | Destruktor. |

## Pole

| Pole | Popis |
| --- | --- |
| static [Empty](./empty/) | Prázdný řetězec. |
| static [Null](./null/) | Null řetězec. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Reverse iterator type. |

## Poznámky



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Vytvořte řetězec z pole znaků a vytiskněte jej.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Vytvořte řetězec z pole bajtů a vytiskněte jej.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Odstraňte mezery z níže uvedeného řetězce a vytiskněte jej.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Vytiskněte počet slov v řetězci.
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
Tento příklad kódu vytiskne následující výstup:
ahoj
svět
"Tento řetězec obsahuje mezery na začátku i na konci."
Počet slov: 11
*/
```

## Viz také

* Namespace [System](../)
* Knihovna [Aspose.Slides](../../)