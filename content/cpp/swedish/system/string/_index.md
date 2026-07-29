---
title: String
second_title: Aspose.Slides för C++ API-referens
description: "String-klass som används i hela biblioteket. Är en ersättning för C# System.String vid kodöversättning. Av optimeringsskäl betraktas den inte som en underklass till Object. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ."
type: docs
weight: 1275
url: /sv/system/string/
---
## String klass


[String](./) klass används i hela biblioteket. Är en ersättning för C# [System.String](./) vid kodöversättning. Av optimeringsskäl betraktas den inte som en [Object](../object/) subklass. Denna typ bör allokeras på stacken och passeras till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

```cpp
class String
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) är ett värdetyp på C++-sidan som implicit (utan arv) implementerar vissa gränssnitt. |
| const UChar * [begin](./begin/)() const | Returnerar en pekare till början av den faktiska strängbufferten. Återallokerar aldrig något. Garanterar inte att bufferten är null-terminerad. |
| [String](./) [Clone](./clone/)() const | Skapar en kopia av den aktuella strängen. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | Jämför två delsträngar med mindre-lika-större-logik. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Jämför två delsträngar med mindre-lika-större-logik. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Jämför två strängar med mindre-lika-större-logik. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | Jämför två strängar med mindre-lika-större-logik. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | Jämför två strängar med mindre-lika-större-logik. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Jämför två strängar med mindre-lika-större-logik. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | Jämför två strängar i ordinalt läge. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | Jämför två strängar i ordinalt läge. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | Jämför två strängar i “mindre-lika-större”-stil. Använder aktuell kultur. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | Konkatenar strängar. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | Konkatenar strängar. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | Konkatenar strängar. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | Konkatenar strängar. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | Kontrollerar om str är en delsträng av den aktuella strängen. |
| **bool** [Contains](./contains/)(char16_t) const | Kontrollerar om strängen innehåller det angivna tecknet. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | Skapar en kopia av strängen. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | Kopierar tecken från strängen till befintliga array-element. Storlek förändras inte. |
| const UChar * [end](./end/)() const | Returnerar en pekare till slutet av den faktiska strängbufferten. Återallokerar aldrig något. Garanterar inte att bufferten är null-terminerad. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | Kontrollerar om strängen avslutas med angiven delsträng. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Kontrollerar om strängen avslutas med angiven delsträng. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Kontrollerar om strängen avslutas med angiven delsträng. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) likhetsjämförelse. Flera lägen som tillhandahålls av StringComparison-enumerationen stöds. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) likhetsjämförelse. Använder [System::StringComparison::Ordinal](../stringcomparison/)-jämförelseläge. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Likhetsjämför två strängar med ordinalt jämförelseläge. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Likhetsjämför två strängar. |
| int [FastToAscii](./fasttoascii/)(char, int) const | Försöker konvertera en [String](./) till en ASCII-sträng. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | Formaterar sträng i C#-stil. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | Formaterar sträng i C#-stil. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Formaterar sträng i C#-stil. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | Formaterar sträng i C#-stil. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | Formaterar sträng i C#-stil. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | Skapar [String](./) från en ASCII-sträng. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | Skapar [String](./) från en ASCII-sträng. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | Skapar [String](./) från en ASCII-sträng. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | Skapar [String](./) från en UTF-16-sträng. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | Skapar [String](./) från en UTF-32-sträng. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | Skapar [String](./) från en UTF-8-sträng. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | Skapar [String](./) från en UTF-8-sträng. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | Skapar [String](./) från en UTF-8-sträng. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | Skapar [String](./) från en UTF-8-sträng. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | Skapar [String](./) från en widestring. |
| int [get_Length](./get_length/)() const | Hämtar stränglängd. |
| int [GetHashCode](./gethashcode/)() const | Hashar den innehållna strängen. Implementerad i ICU, matchar inte hashvärden i C#. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Framåtsökning av delsträng. |
| int [IndexOf](./indexof/)(char_t, int) const | Framåtsökning av tecken. |
| int [IndexOf](./indexof/)(char_t, int, int) const | Framåtsökning av tecken i delsträng. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | Framåtsökning av delsträng. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Framåtsökning av delsträng. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | Framåtsökning av delsträng. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | Framåtsökning av delsträng. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | Framåtsökning av tecken. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | Söker sekventiellt efter alla tecken i str i denna sträng. Om det första tecknet hittas returneras dess position, annars fortsätts med nästa osv. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Söker efter någon av de överförda tecknen i hela strängen. Jämför det första tecknet i strängen med alla tecken i anyOf, sedan det andra osv. Returnerar index för det första som matchar något av måltecknen. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Söker efter någon av de överförda tecknen i delsträngen. Jämför det första tecknet i strängen med alla tecken i anyOf, sedan det andra osv. Returnerar index för det första som matchar något av måltecknen. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Söker efter någon av de överförda tecknen i delsträngen. Jämför det första tecknet i strängen med alla tecken i anyOf, sedan det andra osv. Returnerar index för det första som matchar något av måltecknen. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | Infogar delsträng på angiven position. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Kontrollerar om strängobjektet är av den typ som specificeras av [TypeInfo](../typeinfo/). |
| **bool** [IsAsciiString](./isasciistring/)() const | Anger om en [String](./) endast innehåller ASCII-symboler. |
| **bool** [IsEmpty](./isempty/)() const | Kontrollerar om strängen både är icke-null och tom. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Kontrollerar om en Unicode-sträng är normaliserad med den angivna normaliseringsformen. |
| **bool** [IsNull](./isnull/)() const | Kontrollerar om strängen betraktas som null. [String](./) är null endast om den konstruerats via [String()](./string/)-konstruktorn, flyttats, kopierats eller tilldelats från en null-sträng eller om [reset()](./reset/)-metoden har anropats. |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | Kontrollerar om strängen är tom eller betraktas som null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | Kontrollerar om den överförda strängen är null eller tom. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | Anger huruvida en given sträng är null, tom eller består enbart av blankstegstecken. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | Slår samman en array med sträng som avgränsare. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | Slår samman en array med sträng som avgränsare. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | Slår samman en array med sträng som avgränsare. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | Slår samman en array med sträng som avgränsare. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | Bakåtsökning av delsträng. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Bakåtsökning av delsträng. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Bakåtsökning av delsträng. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | Bakåtsökning av delsträng. |
| int [LastIndexOf](./lastindexof/)(char_t) const | Bakåtsökning av tecken. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | Bakåtsökning av tecken. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | Bakåtsökning av tecken. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Söker baklänges efter någon av de överförda tecknen i hela strängen. Jämför sista tecknet i strängen med alla tecken i anyOf, sedan föregående osv. Returnerar index för den första träffen. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Söker baklänges efter någon av de överförda tecknen i delsträngen. Jämför sista tecknet i strängen med alla tecken i anyOf, sedan föregående osv. Returnerar index för den första träffen. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Söker baklänges efter någon av de överförda tecknen i delsträngen. Jämför sista tecknet i strängen med alla tecken i anyOf, sedan föregående osv. Returnerar index för den första träffen. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Normaliserar Unicode-sträng med den angivna normaliseringsformen. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | Konverterar strängen till ett skrivskyddat span. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | Icke-likhetsoperator. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Kontrollerar om strängen inte är null. Använder samma logik som [IsNull()](./isnull/)-anropet. |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./)-konkateneringsoperator. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./)-konkatenering med strängliteral eller tecken-strängpekare. |
| [String](./) [operator+](./operator_plus/)(char_t) const | Lägger till tecken i slutet av strängen. |
| [String](./) [operator+](./operator_plus/)(int) const | Lägger till heltalsvärdets strängrepresentation i slutet av strängen. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | Lägger till unsigned-heltalsvärdets strängrepresentation i slutet av strängen. |
| [String](./) [operator+](./operator_plus/)(**double**) const | Lägger till flyttalsvärdets strängrepresentation i slutet av strängen. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | Lägger till heltalsvärdets strängrepresentation i slutet av strängen. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Lägger till referenstypens objekts strängrepresentation i slutet av strängen. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Lägger till referenstypens objekts strängrepresentation i slutet av strängen. |
| [String](./) [operator+](./operator_plus/)(T) const | Lägger till booleskt värdes strängrepresentation i slutet av strängen. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | Konkatenerings-tilldelningsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | Konkatenerings-tilldelningsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | Konkatenerings-tilldelningsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | Konkatenerings-tilldelningsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | Konkatenationstilldelningsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | Konkatenationstilldelningsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | Konkatenationstilldelningsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | Konkatenationstilldelningsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | Konkatenationstilldelningsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | Konkatenationstilldelningsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | Konkatenationstilldelningsoperator. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | Jämför strängar i ordning. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | Tilldelningsoperator. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | Flyttilldelningsoperator. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | Operator för likhetsjämförelse. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Kontrollerar om strängen är null. Använder samma logik som anropet [IsNull()](./isnull/). |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | Jämför strängar i ordning. |
| char_t [operator[]](./operator[]/)(int) const | Hämtar tecken på angiven position. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | Lägger till utfyllnad till vänster om den ursprungliga strängen. |
| [String](./) [PadRight](./padright/)(int, char_t) const | Lägger till utfyllnad till höger om den ursprungliga strängen. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | Returnerar omvänd iterator till det sista tecknet (om något) i den faktiska strängbufferten. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | Extraherar allt förutom delsträngen från den aktuella strängen. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | Returnerar omvänd iterator till positionen före första tecknet (om något) i den faktiska strängbufferten. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | Ersätter alla förekomster av tecken i strängen. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | Ersätter alla förekomster av sökningen i denna sträng. |
| [String](./)\& [reset](./reset/)() | Sätter strängen till null. Är analogt med 'string_variable_name = null' i C#. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | Sätter tecken på angiven position. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | Delar strängen med tecken. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Delar strängen med tecken. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | Delar strängen med ett av två tecken. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Delar strängen med ett av de angivna tecknen. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Delar strängen med ett av de angivna tecknen. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | Delar strängen med delsträng. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Delar strängen med delsträng. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Delar strängen med delsträng. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Delar strängen med delsträng. För närvarande stöds bara separatorer-array med noll eller ett element. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | Kontrollerar om strängen börjar med den angivna delsträngen. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Kontrollerar om strängen börjar med den angivna delsträngen. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Kontrollerar om strängen börjar med den angivna delsträngen. |
| [String](./string/)() | Standardkonstruktör. Skapar ett strängobjekt som anses vara null. |
| [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | Konstruktor som bygger en sträng baserat på en strängliteral. Betraktar literal som en nullterminerad sträng, beräknar mållängden baserat på literalens storlek. |
| [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | Konstruktor som bygger en sträng baserat på en pekare till teckensträng. Behandlar den pekade strängen som nullterminerad, beräknar mållängden baserat på null-tecknet. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | Explicit konstruktor som bygger en sträng baserat på en strängliteral. Betraktar literal som en nullterminerad sträng i UTF-8, beräknar mållängden baserat på literalens storlek. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | Explicit konstruktor som bygger en sträng baserat på en pekare till teckensträng. Behandlar den pekade strängen som nullterminerad i UTF-8, beräknar mållängden baserat på null-tecknet. |
| [String](./string/)(const char16_t *, int) | Konstruktor som bygger en sträng från en pekare till teckensträng och explicit längd. |
| [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | Initierar en ny instans av klassen [System.String](./) med de Unicode-tecken som anges i den specificerade skrivskyddade spännvidden. |
| [String](./string/)(const char *, int) | Konstruktor som bygger en sträng från en pekare till teckensträng och explicit längd. |
| [String](./string/)(const char16_t *, int, int) | Konstruktor som bygger en sträng från en pekare till teckensträng, med startposition och längd. |
| explicit  [String](./string/)(const char16_t, int) | Explicit fyllningskonstruktor. |
| [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Nullptr-konstruktor. Deklarerad som mall för att lösa prioriteringar med andra mallkonstruktörer. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | Explicit konstruktor som bygger en sträng baserat på en widestring-literal. Betraktar literal som en nullterminerad sträng, beräknar mållängden baserat på literalens storlek. Konvertering från **wchar_t** är tidskrävande på vissa plattformar, så inga implicita konverteringar tillåts. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | Explicit konstruktor som bygger en sträng baserat på en pekare till ett bredteckensträng. Behandlar den pekade strängen som nullterminerad, beräknar mållängden baserat på null-tecknet. Konvertering från **wchar_t** är tidskrävande på vissa plattformar, så inga implicita konverteringar tillåts. |
| explicit  [String](./string/)(const **wchar_t** *, int) | Explicit konstruktor som bygger en sträng från en pekare till ett bredteckensträng och explicit längd. Konvertering från **wchar_t** är tidskrävande på vissa plattformar, så inga implicita konverteringar tillåts. |
| explicit  [String](./string/)(const **wchar_t**, int) | Explicit fyllningskonstruktor. Konvertering från **wchar_t** är tidskrävande på vissa plattformar, så inga implicita konverteringar tillåts. |
| [String](./string/)(const [String](./)\&) | Kopieringskonstruktor. |
| [String](./string/)([String](./)\&&) | Flyttkonstruktor. |
| [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | Konverterar hela teckenarrayen till en sträng. |
| [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | Konverterar ett delintervall av teckenarrayen till en sträng. Om parametrarna är utanför arrayens gränser, konstrueras en tom sträng. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | Explicit konstruktor som omsluter UnicodeString i [String](./). |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | Flyttkonstruktor. |
| explicit  [String](./string/)(const std::wstring\&) | Skapar [String](./) från widestring. |
| explicit  [String](./string/)(const std::u16string\&) | Skapar [String](./) från utf-16-sträng. |
| explicit  [String](./string/)(const std::string\&) | Skapar [String](./) från std::string som presenteras i UTF-8-format. |
| explicit  [String](./string/)(const std::u32string\&) | Skapar [String](./) från std::u32string. |
| [String](./) [Substring](./substring/)(**int32_t**) const | Extraherar delsträng. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | Extraherar delsträng. |
| std::string [ToAsciiString](./toasciistring/)() const | Konverterar strängen till std::string. Använder ASCII-kodning. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | Konverterar sträng eller delsträng till en bytearray. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | Konverterar sträng eller delsträng till en teckenarray. |
| [String](./) [ToLower](./tolower/)() const | Konverterar alla tecken i strängen till gemener. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Konverterar alla tecken i strängen till gemener med specifik kultur. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | Konverterar alla tecken i strängen till gemener med invariant kultur. |
| [String](./) [ToString](./tostring/)() const | Omslag för att hantera [String](./)-klassen i sammanhang där [ToString()](./tostring/) anropas på värdetypsobjekt. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Omslag för att hantera [String](./)-klassen i sammanhang där [ToString()](./tostring/) anropas på värdetypsobjekt. |
| std::u16string [ToU16Str](./tou16str/)() const | Konverterar strängen till std::u16string. |
| std::u32string [ToU32Str](./tou32str/)() const | Konverterar strängen till std::u32string. |
| [String](./) [ToUpper](./toupper/)() const | Konverterar alla tecken i strängen till versaler. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Konverterar alla tecken i strängen till versaler med specifik kultur. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | Konverterar alla tecken i strängen till versaler med invariant kultur. |
| std::string [ToUtf8String](./toutf8string/)() const | Konverterar strängen till std::string. Använder UTF-8-kodning. |
| std::wstring [ToWCS](./towcs/)() const | Konverterar strängen till std::wstring. |
| [String](./) [Trim](./trim/)() const | Tar bort alla blankstegstecken från både början och slutet av strängen. |
| [String](./) [Trim](./trim/)(char_t) const | Tar bort alla förekomster av angivet tecken från både början och slutet av strängen. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | Tar bort alla förekomster av angivna tecken från både början och slutet av strängen. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Tar bort alla förekomster av angivna tecken från både början och slutet av strängen. |
| [String](./) [TrimEnd](./trimend/)() const | Tar bort alla blankstegstecken från slutet av strängen. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | Tar bort alla förekomster av angivet tecken från slutet av strängen. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | Tar bort alla förekomster av angivna tecken från slutet av strängen. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Tar bort alla förekomster av angivna tecken från slutet av strängen. |
| [String](./) [TrimStart](./trimstart/)() const | Tar bort alla blankstegstecken från början av strängen. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | Tar bort alla förekomster av angivet tecken från början av strängen. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | Tar bort alla förekomster av angivna tecken från början av strängen. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Tar bort alla förekomster av angivna tecken från början av strängen. |
| const UChar * [u_str](./u_str/)() const | Returnerar en nullterminerad buffer i ICU-stil. Kan omallokera strängen. |
| [~String](./~string/)() | Destruktor. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | Tom sträng. |
| static [Null](./null/) | Nullsträng. |

## Typdefinitioner

| Typdef | Beskrivning |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Typ för omvänd iterator. |

## Anmärkningar



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Konstruera en sträng från teckenarrayen och skriv ut den.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Konstruera en sträng från bytearrayen och skriv ut den.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Trimma strängen nedan och skriv ut den.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Skriv ut antalet ord i .
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
Det här kodexemplet producerar följande utskrift:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)