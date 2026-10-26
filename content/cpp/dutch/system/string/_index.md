---
title: String
second_title: Aspose.Slides voor C++ API-referentie
description: "String-klasse die door de hele bibliotheek wordt gebruikt. Is een vervanging voor C# System.String bij het vertalen van code. Om optimalisatieredenen wordt het niet beschouwd als een Object-subklasse. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de System::SmartPtr-klasse om objecten van dit type te beheren."
type: docs
weight: 1275
url: /nl/system/string/
---
## String klasse

[String](./) klasse die door de bibliotheek wordt gebruikt. Is een vervanging voor C# [System.String](./) bij het vertalen van code. Om optimalisatieredenen wordt het niet beschouwd als een [Object](../object/) subklasse. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de [System::SmartPtr](../smartptr/) klasse om objecten van dit type te beheren.

```cpp
class String
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) is een waardetype aan de C++-kant dat impliciet (zonder overerving) enkele interfaces implementeert. |
| const UChar * [begin](./begin/)() const | Retourneert een pointer naar het begin van de werkelijke tekenreeksbuffer. Realloceert nooit iets. Garandeert niet dat de buffer null-terminated is. |
| [String](./) [Clone](./clone/)() const | Maakt een kopie van de huidige tekenreeks. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | Vergelijkt twee subreeksen met minder-gelijk-groter. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Vergelijkt twee subreeksen met minder-gelijk-groter. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Vergelijkt twee tekenreeksen met minder-gelijk-groter. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | Vergelijkt twee tekenreeksen met minder-gelijk-groter. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | Vergelijkt twee tekenreeksen met minder-gelijk-groter. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Vergelijkt twee tekenreeksen met minder-gelijk-groter. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | Vergelijkt twee tekenreeksen met minder-gelijk-groter in ordinal-modus. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | Vergelijkt twee tekenreeksen met minder-gelijk-groter in ordinal-modus. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | Vergelijkt twee tekenreeksen in 'minder-gelijk-groter'-stijl. Gebruikt de huidige cultuur. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | Voegt tekenreeksen samen. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | Voegt tekenreeksen samen. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | Voegt tekenreeksen samen. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | Voegt tekenreeksen samen. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | Controleert of str een subreeks is van de huidige tekenreeks. |
| **bool** [Contains](./contains/)(char16_t) const | Controleert of de tekenreeks het opgegeven teken bevat. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | Maakt een kopie van de tekenreeks. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | Kopieert tekenreeks-tekens naar bestaande array-elementen. Er wordt niet opnieuw geschaald. |
| const UChar * [end](./end/)() const | Retourneert een pointer naar het einde van de werkelijke tekenreeksbuffer. Realloceert nooit iets. Garandeert niet dat de buffer null-terminated is. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | Controleert of de tekenreeks eindigt met de opgegeven subreeks. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Controleert of de tekenreeks eindigt met de opgegeven subreeks. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Controleert of de tekenreeks eindigt met de opgegeven subreeks. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) gelijkheidsvergelijking. Diverse modi geleverd door de StringComparison-enumeratie worden ondersteund. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) gelijkheidsvergelijking. Gebruikt de [System::StringComparison::Ordinal](../stringcomparison/) vergelijkingsmodus. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Vergelijkt twee tekenreeksen op gelijkheid met de Ordial-vergelijkingsmodus. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Vergelijkt twee tekenreeksen op gelijkheid. |
| int [FastToAscii](./fasttoascii/)(char, int) const | Probeert een [String](./) naar een ASCII-tekenreeks te converteren. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | Formatteert de tekenreeks in C#-stijl. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | Formatteert de tekenreeks in C#-stijl. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Formatteert de tekenreeks in C#-stijl. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | Formatteert de tekenreeks in C#-stijl. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | Formatteert de tekenreeks in C#-stijl. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | Maakt een [String](./) aan vanuit een ASCII-tekenreeks. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | Maakt een [String](./) aan vanuit een ASCII-tekenreeks. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | Maakt een [String](./) aan vanuit een ASCII-tekenreeks. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | Maakt een [String](./) aan vanuit een UTF-16-tekenreeks. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | Maakt een [String](./) aan vanuit een UTF-32-tekenreeks. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | Maakt een [String](./) aan vanuit een UTF-8-tekenreeks. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | Maakt een [String](./) aan vanuit een UTF-8-tekenreeks. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | Maakt een [String](./) aan vanuit een UTF-8-tekenreeks. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | Maakt een [String](./) aan vanuit een UTF-8-tekenreeks. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | Maakt een [String](./) aan vanuit een wide-string. |
| int [get_Length](./get_length/)() const | Berekent de lengte van de tekenreeks. |
| int [GetHashCode](./gethashcode/)() const | Genereert een hash van de tekenreeks. Implementatie in ICU, komt niet overeen met hashes in C#. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Zoekt een subreeks vooruit. |
| int [IndexOf](./indexof/)(char_t, int) const | Zoekt een teken vooruit. |
| int [IndexOf](./indexof/)(char_t, int, int) const | Zoekt een teken vooruit in een subreeks. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | Zoekt een subreeks vooruit. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Zoekt een subreeks vooruit. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | Zoekt een subreeks vooruit. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | Zoekt een subreeks vooruit. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | Zoekt een teken vooruit. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | Zoekt vervolgens naar alle tekens van str in deze. Als het eerste teken wordt gevonden, wordt de positie geretourneerd; anders wordt gezocht naar het tweede teken, enzovoort. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Zoekt naar elk van de opgegeven tekens in de volledige tekenreeks. Vergelijkt het eerste teken van de tekenreeks met alle tekens in anyOf, daarna het tweede, enzovoort. Retourneert de index van het eerste teken dat overeenkomt met een van de doeltekens. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Zoekt naar elk van de opgegeven tekens in een subreeks. Vergelijkt het eerste teken van de tekenreeks met alle tekens in anyOf, daarna het tweede, enzovoort. Retourneert de index van het eerste teken dat overeenkomt met een van de doeltekens. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Zoekt naar elk van de opgegeven tekens in een subreeks. Vergelijkt het eerste teken van de tekenreeks met alle tekens in anyOf, daarna het tweede, enzovoort. Retourneert de index van het eerste teken dat overeenkomt met een van de doeltekens. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | Voegt een subreeks in op de opgegeven positie. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Controleert of het tekenreeksobject van het type is dat is opgegeven door [TypeInfo](../typeinfo/). |
| **bool** [IsAsciiString](./isasciistring/)() const | Geeft aan of een [String](./) alleen ASCII-symbolen bevat. |
| **bool** [IsEmpty](./isempty/)() const | Controleert of de tekenreeks zowel niet-null als leeg is. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Controleert of de Unicode-tekenreeks genormaliseerd is met de gespecificeerde normalisvorm. |
| **bool** [IsNull](./isnull/)() const | Controleert of de tekenreeks als null wordt beschouwd. [String](./) is null en alleen als deze wordt geconstrueerd via de [String()](./string/)-constructor, verplaatst, gekopieerd of toegewezen vanaf een null-tekenreeks of als de [reset()](./reset/)-methode is aangeroepen. |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | Controleert of de tekenreeks leeg is of als null wordt beschouwd. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | Controleert of de opgegeven tekenreeks null of leeg is. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | Geeft aan of een opgegeven tekenreeks null, leeg of uitsluitend uit witruimtetekens bestaat. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | Voegt een array samen met een tekenreeks als scheidingsteken. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | Voegt een array samen met een tekenreeks als scheidingsteken. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | Voegt een array samen met een tekenreeks als scheidingsteken. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | Voegt een array samen met een tekenreeks als scheidingsteken. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | Zoekt een subreeks achterwaarts. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Zoekt een subreeks achterwaarts. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Zoekt een subreeks achterwaarts. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | Zoekt een subreeks achterwaarts. |
| int [LastIndexOf](./lastindexof/)(char_t) const | Zoekt een teken achterwaarts. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | Zoekt een teken achterwaarts. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | Zoekt een teken achterwaarts. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Zoekt naar elk van de opgegeven tekens in de volledige tekenreeks achterwaarts. Vergelijkt het laatste teken van de tekenreeks met alle tekens in anyOf, daarna het vorige teken, enzovoort. Retourneert de index van de eerste gevonden overeenkomst. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Zoekt naar elk van de opgegeven tekens in een subreeks achterwaarts. Vergelijkt het laatste teken van de tekenreeks met alle tekens in anyOf, daarna het vorige teken, enzovoort. Retourneert de index van de eerste gevonden overeenkomst. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Zoekt naar elk van de opgegeven tekens in een subreeks achterwaarts. Vergelijkt het laatste teken van de tekenreeks met alle tekens in anyOf, daarna het vorige teken, enzovoort. Retourneert de index van de eerste gevonden overeenkomst. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Normaliseert een Unicode-tekenreeks met de gespecificeerde normalisvorm. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | Converteert de tekenreeks naar een alleen-lezen span. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | Niet-gelijkheidsvergelijkingsoperator. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Controleert of de tekenreeks niet null is. Past dezelfde logica toe als de [IsNull()](./isnull/)-aanroep. |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) samenvoegingsoperator. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) samenvoeging met een tekenreeks-letterlijk of een tekenreeks-pointer. |
| [String](./) [operator+](./operator_plus/)(char_t) const | Voegt een teken toe aan het einde van de tekenreeks. |
| [String](./) [operator+](./operator_plus/)(int) const | Voegt de tekenreeksrepresentatie van een geheel getal toe aan het einde van de tekenreeks. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | Voegt de tekenreeksrepresentatie van een ongetekend geheel getal toe aan het einde van de tekenreeks. |
| [String](./) [operator+](./operator_plus/)(**double**) const | Voegt de tekenreeksrepresentatie van een zwevend-kommagetal toe aan het einde van de tekenreeks. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | Voegt de tekenreeksrepresentatie van een 64-bits geheel getal toe aan het einde van de tekenreeks. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Voegt de tekenreeksrepresentatie van een referentietype-object toe aan het einde van de tekenreeks. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Voegt de tekenreeksrepresentatie van een referentietype-object toe aan het einde van de tekenreeks. |
| [String](./) [operator+](./operator_plus/)(T) const | Voegt de tekenreeksrepresentatie van een booleaanse waarde toe aan het einde van de tekenreeks. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | Samenvoeg-toewijzingsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | Samenvoeg-toewijzingsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | Samenvoeg-toewijzingsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | Samenvoeg-toewijzingsoperator.
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | Concatenatietoewijzingsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | Concatenatietoewijzingsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | Concatenatietoewijzingsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | Concatenatietoewijzingsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | Concatenatietoewijzingsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | Concatenatietoewijzingsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | Concatenatietoewijzingsoperator. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | Vergelijkt strings in volgorde. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | Toewijzingsoperator. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | Verplaatsings-toewijzingsoperator. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | Vergelijkingsoperator voor gelijkheid. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Controleert of string null is. Past dezelfde logica toe als [IsNull()](./isnull/)-aanroep. |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | Vergelijkt strings in volgorde. |
| char_t [operator[]](./operator[]/)(int) const | Haalt teken op op de opgegeven positie. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | Voegt opvulling toe aan de linkerkant van de oorspronkelijke string. |
| [String](./) [PadRight](./padright/)(int, char_t) const | Voegt opvulling toe aan de rechterkant van de oorspronkelijke string. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | Retourneert reverse-iterator naar het laatste teken (indien aanwezig) van de werkelijke stringbuffer. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | Haalt alles op behalve de sub-string van de huidige string. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | Retourneert reverse-iterator naar vóór het eerste teken (indien aanwezig) van de werkelijke stringbuffer. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | Vervangt alle voorkomens van het teken in de string. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | Vervangt alle voorkomens van lookup in deze string. |
| [String](./)\& [reset](./reset/)() | Stelt de string in op null. Is analoog aan 'string_variable_name = null' in C#. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | Stelt teken in op opgegeven positie. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | Splitst de string op teken. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Splitst de string op teken. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | Splitst de string op een van twee tekens. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Splitst de string op een van de opgegeven tekens. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Splitst de string op een van de opgegeven tekens. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | Splitst de string op sub-string. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Splitst de string op sub-string. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Splitst de string op sub-string. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Splitst de string op sub-string. Ondersteunt momenteel alleen scheidingstekensarray van nul of één elementen. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | Controleert of de string begint met de opgegeven sub-string. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Controleert of de string begint met de opgegeven sub-string. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Controleert of de string begint met de opgegeven sub-string. |
|  [String](./string/)() | Standaardconstructor. Maakt een stringobject aan dat als null wordt beschouwd. |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | Construeert string op basis van string-literal. Beschouwt literal als een null-terminerende string, berekent de doellengte op basis van de literal-grootte. |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | Construeert string op basis van tekenreeks-pointer. Beschouwt de aangewezen string als null-terminerend, berekent de doellengte op basis van het null-teken. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | Construeert string op basis van string-literal. Beschouwt literal als een null-terminerende string in UTF-8, berekent de doellengte op basis van de literal-grootte. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | Construeert string op basis van tekenreeks-pointer. Beschouwt de aangewezen string als null-terminerend in UTF-8, berekent de doellengte op basis van het null-teken. |
|  [String](./string/)(const char16_t *, int) | Construeert string vanuit tekenreeks-pointer en expliciete lengte. |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | Initialiseert een nieuw exemplaar van de [System.String](./)-klasse met de Unicode-tekens aangegeven in de opgegeven read-only-span. |
|  [String](./string/)(const char *, int) | Construeert string vanuit tekenreeks-pointer en expliciete lengte. |
|  [String](./string/)(const char16_t *, int, int) | Construeert string vanuit tekenreeks-pointer vanaf startpositie met opgegeven lengte. |
| explicit  [String](./string/)(const char16_t, int) | Fill-constructor. |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Nullptr-constructor. Gedefinieerd als template om prioriteiten met andere template-constructors op te lossen. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | Construeert string op basis van widestring-literal. Beschouwt literal als een null-terminerende string, berekent de doellengte op basis van de literal-grootte. Conversie van **wchar_t** is tijdrovend op sommige platformen, dus impliciete conversies zijn niet toegestaan. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | Construeert string op basis van wide-character-pointer. Beschouwt de aangewezen string als null-terminerend, berekent de doellengte op basis van het null-teken. Conversie van **wchar_t** is tijdrovend op sommige platformen, dus impliciete conversies zijn niet toegestaan. |
| explicit  [String](./string/)(const **wchar_t** *, int) | Construeert string vanuit wide-character-pointer en expliciete lengte. Conversie van **wchar_t** is tijdrovend op sommige platformen, dus impliciete conversies zijn niet toegestaan. |
| explicit  [String](./string/)(const **wchar_t**, int) | Fill-constructor. Conversie van **wchar_t** is tijdrovend op sommige platformen, dus impliciete conversies zijn niet toegestaan. |
|  [String](./string/)(const [String](./)\&) | Kopie-constructor. |
|  [String](./string/)([String](./)\&&) | Move-constructor. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | Converteert volledige tekenarray naar string. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | Converteert deelbereik van tekenarray naar string. Als parameters buiten de array-grenzen liggen, wordt een lege string geconstrueerd. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | Wrapt UnicodeString in [String](./). |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | Move-constructor. |
| explicit  [String](./string/)(const std::wstring\&) | Maakt [String](./) aan uit widestring. |
| explicit  [String](./string/)(const std::u16string\&) | Maakt [String](./) aan uit utf16-string. |
| explicit  [String](./string/)(const std::string\&) | Maakt [String](./) aan uit std::string gepresenteerd in UTF-8-formaat. |
| explicit  [String](./string/)(const std::u32string\&) | Maakt [String](./) aan uit std::u32string-string. |
| [String](./) [Substring](./substring/)(**int32_t**) const | Haalt sub-string op. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | Haalt sub-string op. |
| std::string [ToAsciiString](./toasciistring/)() const | Converteert string naar std::string. Gebruikt ASCII-codering. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | Converteert string of sub-string naar byte-array. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | Converteert string of sub-string naar teken-array. |
| [String](./) [ToLower](./tolower/)() const | Converteert alle tekens van de string naar kleine letters. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Converteert alle tekens van de string naar kleine letters met specifieke cultuur. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | Converteert alle tekens van de string naar kleine letters met ongewijzigde (invariant) cultuur. |
| [String](./) [ToString](./tostring/)() const | Wrapper voor het hanteren van [String](./)-klasse in contexten waar [ToString()](./tostring/) wordt aangeroepen op waardetype-objecten. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Wrapper voor het hanteren van [String](./)-klasse in contexten waar [ToString()](./tostring/) wordt aangeroepen op waardetype-objecten. |
| std::u16string [ToU16Str](./tou16str/)() const | Converteert string naar std::u16string. |
| std::u32string [ToU32Str](./tou32str/)() const | Converteert string naar std::u32string. |
| [String](./) [ToUpper](./toupper/)() const | Converteert alle tekens van de string naar hoofdletters. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Converteert alle tekens van de string naar hoofdletters met specifieke cultuur. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | Converteert alle tekens van de string naar hoofdletters met ongewijzigde (invariant) cultuur. |
| std::string [ToUtf8String](./toutf8string/)() const | Converteert string naar std::string. Gebruikt UTF-8-codering. |
| std::wstring [ToWCS](./towcs/)() const | Converteert string naar std::wstring. |
| [String](./) [Trim](./trim/)() const | Verwijdert alle witruimte-tekens aan zowel het begin als het einde van de string. |
| [String](./) [Trim](./trim/)(char_t) const | Verwijdert alle voorkomens van het opgegeven teken aan zowel het begin als het einde van de string. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | Verwijdert alle voorkomens van de opgegeven tekens aan zowel het begin als het einde van de string. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Verwijdert alle voorkomens van de opgegeven tekens aan zowel het begin als het einde van de string. |
| [String](./) [TrimEnd](./trimend/)() const | Verwijdert alle witruimte-tekens aan het einde van de string. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | Verwijdert alle voorkomens van het opgegeven teken aan het einde van de string. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | Verwijdert alle voorkomens van de opgegeven tekens aan het einde van de string. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Verwijdert alle voorkomens van de opgegeven tekens aan het einde van de string. |
| [String](./) [TrimStart](./trimstart/)() const | Verwijdert alle witruimte-tekens aan het begin van de string. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | Verwijdert alle voorkomens van het opgegeven teken aan het begin van de string. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | Verwijdert alle voorkomens van de opgegeven tekens aan het begin van de string. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Verwijdert alle voorkomens van de opgegeven tekens aan het begin van de string. |
| const UChar * [u_str](./u_str/)() const | Retourneert ICU-stijl null-terminerende buffer. Kan de string opnieuw toewijzen. |
|  [~String](./~string/)() | Destructor. |
## Velden

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Lege string. |
| static [Null](./null/) | Nulstring. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Reverse-iterator type. |
## Opmerkingen



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Maak een string aan vanuit de array van tekens en druk deze af.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Maak een string aan vanuit de array van bytes en druk deze af.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Trim de onderstaande string en druk deze af.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Print het aantal woorden in de .
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende output:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)