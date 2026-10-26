---
title: StringWriter
second_title: Aspose.Slides pro C++ API Reference
description: "Implementuje TextWriter, který zapisuje informace do řetězce. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám během běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání funkcím jako argument."
type: docs
weight: 417
url: /cs/system.io/stringwriter/
---
## StringWriter třída


Implementuje [TextWriter](../textwriter/) který zapisuje informace do řetězce. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku nebo pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání funkcím jako argument.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Metody

| Method | Description |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | Uzavře proud a uvolní získané zdroje. |
| void [Dispose](../textwriter/dispose/)() override | Uvolní všechny prostředky použité aktuálním objektem a uzavře podkladový proud. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání floating-point ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání floating-point ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual void [Flush](../textwriter/flush/)() | Vyprázdní obsah bufferu do podkladového proudu. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Vrací aktuálně používané kódování. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Vrací aktuálně používaný objekt [IFormatProvider](../../system/iformatprovider/). |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Vrací aktuálně používaný objekt [IFormatProvider](../../system/iformatprovider/). |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Vrací řetězec ukončující řádek. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Vrací řetězec ukončující řádek. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | Vrací aktuálně používaný StringBuilder. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného parametrem targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Volat přímo nebo použít objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený počitadlo referencí o zadanou hodnotu. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Nastavuje řetězec ukončující řádek. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený počitadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený počitadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Vytvoří novou instanci [StringWriter](./) pomocí specifikovaného StringBuilder a [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Vytvoří novou instanci [StringWriter](./) pomocí specifikovaného StringBuilder a [IFormatProvider](../../system/iformatprovider/) z aktuální kultury. |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Vytvoří novou instanci [StringWriter](./) pomocí specifikovaného [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)() | Vytvoří novou instanci [StringWriter](./) pomocí [IFormatProvider](../../system/iformatprovider/) z aktuální kultury. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Vrací podkladový řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock(). Volat přímo nebo použít objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počitadlo slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počitadlo slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [Write](./write/)(char_t) override | Zapíše zadaný znak do proudu. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Zapíše zadaný podrozsah znaků ze zadaného pole znaků do proudu. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Zapíše zadaný řetězec do proudu. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Zapíše řetězcovou reprezentaci zadaného objektu do proudu. |
| virtual void [Write](../textwriter/write/)(**bool**) | Zapíše řetězcovou reprezentaci zadané boolean hodnoty do proudu. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Zapíše řetězcovou reprezentaci zadaného objektu [Decimal](../../system/decimal/) do proudu. |
| virtual void [Write](../textwriter/write/)(**double**) | Zapíše řetězcovou reprezentaci zadané double-precision floating point hodnoty do proudu. |
| virtual void [Write](../textwriter/write/)(int) | Zapíše řetězcovou reprezentaci zadané 32-bitové celého čísla do proudu. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Zapíše řetězcovou reprezentaci zadané 64-bitové celého čísla do proudu. |
| virtual void [Write](../textwriter/write/)(**float**) | Zapíše řetězcovou reprezentaci zadané single-precision floating point hodnoty do proudu. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Zapíše řetězcovou reprezentaci zadané nepsané 32-bitové celé číslo do proudu. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Zapíše řetězcovou reprezentaci zadané nepsané 64-bitové celé číslo do proudu. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Zapíše všechny znaky ze zadaného pole do proudu. |
| virtual void [Write](../textwriter/write/)(const char_t *) | Zapíše zadaný C-řetězec do proudu. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Zapíše řetězcovou reprezentaci zadaného objektu [TypeInfo](../../system/typeinfo/) do proudu. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Zapíše zadané hodnoty formátované podle specifikovaného formátu do proudu. |
| virtual void [WriteLine](../textwriter/writeline/)() | Zapíše znaky ukončující řádek do proudu. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Zapíše řetězcovou reprezentaci zadaného objektu následovanou znaky ukončující řádek do proudu. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Zapíše řetězcovou reprezentaci zadané boolean hodnoty následovanou znaky ukončující řádek do proudu. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Zapíše zadaný znak následovaný znaky ukončující řádek do proudu. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Zapíše řetězcovou reprezentaci zadaného objektu [Decimal](../../system/decimal/) následovanou znaky ukončující řádek do proudu. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Zapíše řetězcovou reprezentaci zadané double-precision hodnoty následovanou znaky ukončující řádek do proudu. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Zapíše řetězcovou reprezentaci zadané 32-bitové celého čísla následovanou znaky ukončující řádek do proudu. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Zapíše řetězcovou reprezentaci zadané 64-bitové celého čísla následovanou znaky ukončující řádek do proudu. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Zapíše řetězcovou reprezentaci zadané single-precision hodnoty následovanou znaky ukončující řádek do proudu. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | Zapíše zadaný řetězec následovaný znaky ukončující řádek do proudu. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Zapíše řetězcovou reprezentaci zadané nepsané 32-bitové celé číslo následovanou znaky ukončující řádek do proudu. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Zapíše řetězcovou reprezentaci zadané nepsané 64-bitové celé číslo následovanou znaky ukončující řádek do proudu. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Zapíše všechny znaky ze zadaného pole následované znaky ukončující řádek do proudu. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Zapíše zadaný podrozsah znaků UTF-16 ze zadaného pole znaků následovaný znaky ukončující řádek do proudu. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | Zapíše zadaný C-řetězec následovaný znaky ukončující řádek do proudu. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Zapíše řetězcovou reprezentaci zadaného objektu [TypeInfo](../../system/typeinfo/) následovanou znaky ukončující řádek do proudu. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Zapíše zadané hodnoty formátované podle specifikovaného formátu následované znaky ukončující řádek do proudu. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destruktor. |

## Viz také

* Třída [TextWriter](../textwriter/)
* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)