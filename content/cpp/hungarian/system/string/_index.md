---
title: String
second_title: Aspose.Slides C++ API referencia
description: "String osztály a könyvtárban széles körben használatos. A C# System.String helyettesítőjeként szolgál a kód fordításakor. Teljesítményoptimalizálási okokból nem tekinthető az Object alosztályának. Ezt a típust a stacken kell lefoglalni, és értékként vagy referenciaként átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 1275
url: /hu/system/string/
---
## String osztály

[String](./) osztály a könyvtárban széles körben használt. A [System.String](./) helyettesítője C#-ban a kód fordításakor. Optimalizálási okokból nem tekinthető az [Object](../object/) alosztálynak. Ezt a típust a stacken kell lefoglalni, és érték szerint vagy referenciaként kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
class String
```

## Metódusok

| Módszer | Leírás |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) értéktípus a C++ oldalon, amely implicit módon (öröklődés nélkül) implementál néhány interfészt. |
| const UChar * [begin](./begin/)() const | Visszaad egy mutatót a tényleges karakterlánc buffer elejére. Soha nem allokál újra semmit. Nem garantálja, hogy a buffer nullával zárul. |
| [String](./) [Clone](./clone/)() const | Létrehozza az aktuális karakterlánc másolatát. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | Kisebb-egyenlő-nagyobb összehasonlít két részkarakterláncot. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Kisebb-egyenlő-nagyobb összehasonlít két részkarakterláncot. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Kisebb-egyenlő-nagyobb összehasonlít két karakterláncot. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | Kisebb-egyenlő-nagyobb összehasonlít két karakterláncot. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | Kisebb-egyenlő-nagyobb összehasonlít két karakterláncot. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Kisebb-egyenlő-nagyobb összehasonlít két karakterláncot. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | Kisebb-egyenlő-nagyobb összehasonlít két karakterláncot ordinális módban. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | Kisebb-egyenlő-nagyobb összehasonlít két karakterláncot ordinális módban. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | Összehasonlít két karakterláncot 'kevesebb-egyenlő-nagyobb' stílusban. A jelenlegi kultúrát használja. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | Összefűzi a karakterláncokat. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | Összefűzi a karakterláncokat. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | Összefűzi a karakterláncokat. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | Összefűzi a karakterláncokat. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | Ellenőrzi, hogy a str része-e az aktuális karakterláncnak. |
| **bool** [Contains](./contains/)(char16_t) const | Ellenőrzi, hogy a karakterlánc tartalmazza-e a megadott karaktert. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | Létrehozza a karakterlánc másolatát. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | Átmásolja a karakterlánc karaktereit meglévő tömb elemeibe. Nem történik átméretezés. |
| const UChar * [end](./end/)() const | Visszaad mutatót a tényleges karakterlánc buffer végére. Soha nem allokál újra semmit. Nem garantálja, hogy a buffer nullával zárul. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | Ellenőrzi, hogy a karakterlánc a megadott részkarakterlánccal végződik-e. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Ellenőrzi, hogy a karakterlánc a megadott részkarakterlánccal végződik-e. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Ellenőrzi, hogy a karakterlánc a megadott részkarakterlánccal végződik-e. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) egyenlőség összehasonlítás. A StringComparison felsorolás által biztosított több mód támogatott. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) egyenlőség összehasonlítás. A [System::StringComparison::Ordinal](../stringcomparison/) összehasonlítási módot használja. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Egyenlőség összehasonlít két karakterláncot Ordial összehasonlítási móddal. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Egyenlőség összehasonlít két karakterláncot. |
| int [FastToAscii](./fasttoascii/)(char, int) const | Megpróbál egy [String](./)-t ASCII karakterlánccá konvertálni. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | Formázza a karakterláncot C# stílusban. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | Formázza a karakterláncot C# stílusban. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Formázza a karakterláncot C# stílusban. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | Formázza a karakterláncot C# stílusban. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | Formázza a karakterláncot C# stílusban. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | Létrehoz egy [String](./)-t ASCII karakterláncból. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | Létrehoz egy [String](./)-t ASCII karakterláncból. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | Létrehoz egy [String](./)-t ASCII karakterláncból. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | Létrehoz egy [String](./)-t utf16 karakterláncból. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | Létrehoz egy [String](./)-t utf32 karakterláncból. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | Létrehoz egy [String](./)-t utf8 karakterláncból. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | Létrehoz egy [String](./)-t utf8 karakterláncból. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | Létrehoz egy [String](./)-t utf8 karakterláncból. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | Létrehoz egy [String](./)-t utf8 karakterláncból. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | Létrehoz egy [String](./)-t widestringből. |
| int [get_Length](./get_length/)() const | Visszaadja a karakterlánc hosszát. |
| int [GetHashCode](./gethashcode/)() const | Hash-eli a tartalmazott karakterláncot. ICU-ban van implementálva, nem egyezik a C# hash-ekkel. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Előre keresés részkarakterláncra. |
| int [IndexOf](./indexof/)(char_t, int) const | Előre keresés karakterre. |
| int [IndexOf](./indexof/)(char_t, int, int) const | Előre keresés karakterre a részkarakterláncban. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | Előre keresés részkarakterláncra. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Előre keresés részkarakterláncra. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | Előre keresés részkarakterláncra. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | Előre keresés részkarakterláncra. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | Előre keresés karakterre. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | Következetesen keresi a str összes karakterét ebben. Ha az első karakter megtalálható, visszaadja a pozícióját, egyébként a másodikat és így tovább. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Megvizsgálja az egész karakterláncot a megadott karakterek keresésével. Az első karaktert összehasonlítja az anyOf összes karakterével, majd a másodikat stb. Visszaadja az első, a célkarakterek valamelyikével egyező karakter indexét. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Megvizsgálja a részkarakterláncot a megadott karakterek keresésével. Az első karaktert összehasonlítja az anyOf összes karakterével, majd a másodikat stb. Visszaadja az első, a célkarakterek valamelyikével egyező karakter indexét. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Megvizsgálja a részkarakterláncot a megadott karakterek keresésével. Az első karaktert összehasonlítja az anyOf összes karakterével, majd a másodikat stb. Visszaadja az első, a célkarakterek valamelyikével egyező karakter indexét. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | Beszúr egy részkarakterláncot a megadott pozícióba. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Ellenőrzi, hogy a karakterlánc objektum a megadott [TypeInfo](../typeinfo/) típussal egyezik-e. |
| **bool** [IsAsciiString](./isasciistring/)() const | Jelzi, hogy a [String](./) csak ASCII szimbólumokat tartalmaz-e. |
| **bool** [IsEmpty](./isempty/)() const | Ellenőrzi, hogy a karakterlánc nem null és üres is egyben. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Ellenőrzi, hogy a Unicode karakterlánc a megadott normalizálási formával normalizált-e. |
| **bool** [IsNull](./isnull/)() const | Ellenőrzi, hogy a karakterlánc nullnak tekinthető-e. [String](./) null, ha csak a [String()](./string/) konstruktorral, mozgatással, másolással vagy null karakterláncból való hozzárendeléssel, illetve a [reset()](./reset/) metódus meghívásával jön létre. |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | Ellenőrzi, hogy a karakterlánc üres vagy nullnak tekinthető. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | Ellenőrzi, hogy a megadott karakterlánc null vagy üres. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | Jelzi, hogy a megadott karakterlánc null, üres vagy csak szóköz karakterekből áll-e. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | Összefűzi a tömböt a karakterlánc szeparátorként használatával. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | Összefűzi a tömböt a karakterlánc szeparátorként használatával. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | Összefűzi a tömböt a karakterlánc szeparátorként használatával. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | Összefűzi a tömböt a karakterlánc szeparátorként használatával. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | Hátrafelé keresés részkarakterláncra. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Hátrafelé keresés részkarakterláncra. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Hátrafelé keresés részkarakterláncra. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | Hátrafelé keresés részkarakterláncra. |
| int [LastIndexOf](./lastindexof/)(char_t) const | Hátrafelé keresés karakterre. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | Hátrafelé keresés karakterre. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | Hátrafelé keresés karakterre. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Megvizsgálja a teljes karakterláncot hátrafelé a megadott karakterek keresésével. Az utolsó karaktert összehasonlítja az anyOf összes karakterével, majd az előzőt stb. Visszaadja az első megtalált egyezés indexét. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Megvizsgálja a részkarakterláncot hátrafelé a megadott karakterek keresésével. Az utolsó karaktert összehasonlítja az anyOf összes karakterével, majd az előzőt stb. Visszaadja az első megtalált egyezés indexét. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Megvizsgálja a részkarakterláncot hátrafelé a megadott karakterek keresésével. Az utolsó karaktert összehasonlítja az anyOf összes karakterével, majd az előzőt stb. Visszaadja az első megtalált egyezés indexét. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Normalizálja a Unicode karakterláncot a megadott normalizálási formával. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | Átalakítja a karakterláncot csak-olvasásra alkalmas spanné. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | Nem egyenlőség összehasonlító operátor. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a karakterlánc nem null. Ugyanazt a logikát alkalmazza, mint a [IsNull()](./isnull/) hívás. |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) összefűző operátor. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) összefűzés karakterlánc literállal vagy karakterlánc mutatóval. |
| [String](./) [operator+](./operator_plus/)(char_t) const | Karaktert ad a karakterlánc végéhez. |
| [String](./) [operator+](./operator_plus/)(int) const | Egész szám értékének karakterlánc reprezentációját adja a karakterlánc végéhez. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | Aláíratlan egész szám értékének karakterlánc reprezentációját adja a karakterlánc végéhez. |
| [String](./) [operator+](./operator_plus/)(**double**) const | Lebegőpontos szám értékének karakterlánc reprezentációját adja a karakterlánc végéhez. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | 64 bites egész szám értékének karakterlánc reprezentációját adja a karakterlánc végéhez. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Referencia típusú objektum karakterlánc reprezentációját adja a karakterlánc végéhez. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Referencia típusú objektum karakterlánc reprezentációját adja a karakterlánc végéhez. |
| [String](./) [operator+](./operator_plus/)(T) const | Bool érték karakterlánc reprezentációját adja a karakterlánc végéhez. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | Összefűző hozzárendelő operátor. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | Összefűző hozzárendelő operátor. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | Összefűző hozzárendelő operátor. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | Összefűző hozzárendelő operátor.
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | Összefűző hozzárendelési operátor. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | Összefűző hozzárendelési operátor. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | Összefűző hozzárendelési operátor. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | Összefűző hozzárendelési operátor. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | Összefűző hozzárendelési operátor. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | Összefűző hozzárendelési operátor. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | Összefűző hozzárendelési operátor. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | Rendelés szerint összehasonlítja a karakterláncokat. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | Hozzárendelő operátor. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | Mozgató hozzárendelő operátor. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | Egyenlőség-összehasonlító operátor. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a karakterlánc null-e. Ugyanazt a logikát alkalmazza, mint a [IsNull()](./isnull/) hívás. |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | Rendelés szerint összehasonlítja a karakterláncokat. |
| char_t [operator[]](./operator[]/)(int) const | Lekéri a karaktert a megadott pozíción. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | Bal oldali kitöltést ad hozzá az eredeti karakterlánchoz. |
| [String](./) [PadRight](./padright/)(int, char_t) const | Jobb oldali kitöltést ad hozzá az eredeti karakterlánchoz. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | Visszaad egy fordított iterátort az utolsó karakterhez (ha van) a tényleges karakterlánc pufferben. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | Kivon mindent, kivéve az alkarakterláncot a jelenlegi karakterláncból. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | Visszaad egy fordított iterátort az első karakter előtti helyhez (ha van) a tényleges karakterlánc pufferben. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | Lecseréli a karakter összes előfordulását a karakterláncban. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | Lecseréli a keresés összes előfordulását ebben a karakterláncban. |
| [String](./)\& [reset](./reset/)() | A karakterláncot null-ra állítja. Hasonló a C#-ban a 'string_variable_name = null' művelethez. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | Beállítja a karaktert a megadott pozíción. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | Felosztja a karakterláncot karakter alapján. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Felosztja a karakterláncot karakter alapján. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | Felosztja a karakterláncot két karakter egyikével. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Felosztja a karakterláncot a megadott karakterek egyikével. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Felosztja a karakterláncot a megadott karakterek egyikével. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | Felosztja a karakterláncot alkarakterlánc alapján. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Felosztja a karakterláncot alkarakterlánc alapján. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Felosztja a karakterláncot alkarakterlánc alapján. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Felosztja a karakterláncot alkarakterlánc alapján. Jelenleg csak nulla vagy egy elemből álló elválasztók tömbjét támogatja. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | Ellenőrzi, hogy a karakterlánc a megadott alkarakterlánccal kezdődik-e. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Ellenőrzi, hogy a karakterlánc a megadott alkarakterlánccal kezdődik-e. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Ellenőrzi, hogy a karakterlánc a megadott alkarakterlánccal kezdődik-e. |
|  [String](./string/)() | Alapértelmezett konstruktor. Létrehozza a karakterlánc objektumot, amely null-nek tekintendő. |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | A karakterláncot karakterlánc literál alapján hozza létre. A literált null-terminált karakterláncként kezeli, a célkarakterlánc hosszát a literál mérete alapján számítja. |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | A karakterláncot karakter string pointer alapján hozza létre. A mutatott karakterláncot null-termináltként kezeli, a célkarakterlánc hosszát a null karakter alapján számítja. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | A karakterláncot karakterlánc literál alapján hozza létre. A literált UTF8-ban null-terminált karakterláncként kezeli, a célkarakterlánc hosszát a literál mérete alapján számítja. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | A karakterláncot karakter string pointer alapján hozza létre. A mutatott karakterláncot UTF8-ban null-termináltként kezeli, a célkarakterlánc hosszát a null karakter alapján számítja. |
|  [String](./string/)(const char16_t *, int) | A karakter string pointer és explicit hossz alapján hozza létre a karakterláncot. |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | Inicializál egy új példányt a [System.String](./) osztályból a megadott csak olvasható span-ban jelölt Unicode karakterekkel. |
|  [String](./string/)(const char *, int) | A karakter string pointer és explicit hossz alapján hozza létre a karakterláncot. |
|  [String](./string/)(const char16_t *, int, int) | A karakter string pointert a kezdő pozíciótól, a megadott hosszal felhasználva hozza létre a karakterláncot. |
| explicit  [String](./string/)(const char16_t, int) | Kitöltő konstruktor. |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Nullptr konstruktor. Sablonnal deklarálva, hogy feloldja a prioritásokat más sablonkonstruktorokkal. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | A karakterláncot widestring literál alapján hozza létre. A literált null-terminált karakterláncként kezeli, a célkarakterlánc hosszát a literál mérete alapján számítja. A **wchar_t**-ról való konverzió bizonyos platformokon időigényes, ezért nem megengedett az implicit konverzió. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | A karakterláncot widecharacter string pointer alapján hozza létre. A mutatott karakterláncot null-termináltként kezeli, a célkarakterlánc hosszát a null karakter alapján számítja. A **wchar_t**-ról való konverzió bizonyos platformokon időigényes, ezért nem megengedett az implicit konverzió. |
| explicit  [String](./string/)(const **wchar_t** *, int) | A karakterláncot widecharacter string pointer és explicit hossz alapján hozza létre. A **wchar_t**-ról való konverzió bizonyos platformokon időigényes, ezért nem megengedett az implicit konverzió. |
| explicit  [String](./string/)(const **wchar_t**, int) | Kitöltő konstruktor. A **wchar_t**-ról való konverzió bizonyos platformokon időigényes, ezért nem megengedett az implicit konverzió. |
|  [String](./string/)(const [String](./)\&) | Másoló konstruktor. |
|  [String](./string/)([String](./)\&&) | Mozgató konstruktor. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | Átalakítja a teljes karaktertömböt karakterlánccá. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | Átalakítja a karaktertömb részletet karakterlánccá. Ha a paraméterek kívül esnek a tömb határain, üres karakterlánc jön létre. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | A UnicodeString-et a [String](./)-be csomagolja. |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | Mozgató konstruktor. |
| explicit  [String](./string/)(const std::wstring\&) | Létrehozza a [String](./)-t widestringből. |
| explicit  [String](./string/)(const std::u16string\&) | Létrehozza a [String](./)-t utf16 karakterláncból. |
| explicit  [String](./string/)(const std::string\&) | Létrehozza a [String](./)-t egy UTF-8 formátumú std::string karakterláncból. |
| explicit  [String](./string/)(const std::u32string\&) | Létrehozza a [String](./)-t egy std::u32string karakterláncból. |
| [String](./) [Substring](./substring/)(**int32_t**) const | Kivon egy alkarakterláncot. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | Kivon egy alkarakterláncot. |
| std::string [ToAsciiString](./toasciistring/)() const | Átalakítja a karakterláncot std::string-té. ASCII kódolást használ. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | Átalakítja a karakterláncot vagy alkarakterláncot bájt tömbbé. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | Átalakítja a karakterláncot vagy alkarakterláncot karakter tömbbé. |
| [String](./) [ToLower](./tolower/)() const | Az összes karaktert kisbetűssé alakítja. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Az összes karaktert a megadott kultúra szerint kisbetűssé alakítja. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | Az összes karaktert invariáns kultúrával kisbetűssé alakítja. |
| [String](./) [ToString](./tostring/)() const | Buborék a [String](./) osztály kezelésére olyan kontextusokban, ahol a [ToString()](./tostring/) értéktípusú objektumokon kerül meghívásra. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Buborék a [String](./) osztály kezelésére olyan kontextusokban, ahol a [ToString()](./tostring/) értéktípusú objektumokon kerül meghívásra. |
| std::u16string [ToU16Str](./tou16str/)() const | Átalakítja a karakterláncot std::u16string-té. |
| std::u32string [ToU32Str](./tou32str/)() const | Átalakítja a karakterláncot std::u32string-té. |
| [String](./) [ToUpper](./toupper/)() const | Az összes karaktert nagybetűssé alakítja. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Az összes karaktert a megadott kultúra szerint nagybetűssé alakítja. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | Az összes karaktert invariáns kultúrával nagybetűssé alakítja. |
| std::string [ToUtf8String](./toutf8string/)() const | Átalakítja a karakterláncot std::string-té. UTF-8 kódolást használ. |
| std::wstring [ToWCS](./towcs/)() const | Átalakítja a karakterláncot std::wstring-té. |
| [String](./) [Trim](./trim/)() const | Eltávolítja az összes szóköz karaktert a karakterlánc elejéről és végéről. |
| [String](./) [Trim](./trim/)(char_t) const | Eltávolítja a megadott karakter összes előfordulását a karakterlánc elejéről és végéről. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | Eltávolítja a megadott karakterek összes előfordulását a karakterlánc elejéről és végéről. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Eltávolítja a megadott karakterek összes előfordulását a karakterlánc elejéről és végéről. |
| [String](./) [TrimEnd](./trimend/)() const | Eltávolítja az összes szóköz karaktert a karakterlánc végéről. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | Eltávolítja a megadott karakter összes előfordulását a karakterlánc végéről. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | Eltávolítja a megadott karakterek összes előfordulását a karakterlánc végéről. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Eltávolítja a megadott karakterek összes előfordulását a karakterlánc végéről. |
| [String](./) [TrimStart](./trimstart/)() const | Eltávolítja az összes szóköz karaktert a karakterlánc elejéről. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | Eltávolítja a megadott karakter összes előfordulását a karakterlánc elejéről. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | Eltávolítja a megadott karakterek összes előfordulását a karakterlánc elejéről. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Eltávolítja a megadott karakterek összes előfordulását a karakterlánc elejéről. |
| const UChar * [u_str](./u_str/)() const | Visszaad egy ICU-stílusú null-terminált puffert. Újraallokálhatja a karakterláncot. |
|  [~String](./~string/)() | Megsemmisítő. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [Empty](./empty/) | Üres karakterlánc. |
| static [Null](./null/) | Null karakterlánc. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Fordított iterátor típus. |

## Megjegyzések



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Egy karaktertömbből hoz létre egy stringet és kiírja.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Egy bájttömbből hoz létre egy stringet és kiírja.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Levágja az alábbi stringet, majd kiírja.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Kiírja a szavak számát a stringben.
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
Ez a kódpélda a következő kimenetet eredményezi:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)