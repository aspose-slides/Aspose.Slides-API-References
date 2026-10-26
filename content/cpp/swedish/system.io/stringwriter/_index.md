---
title: StringWriter
second_title: Aspose.Slides för C++ API-referens
description: "Implementerar en TextWriter som skriver information till en sträng. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Inslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 417
url: /sv/system.io/stringwriter/
---
## StringWriter klass

Implementerar en [TextWriter](../textwriter/) som skriver information till en sträng. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Inslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | Stänger strömmen och frigör förvärvade resurser. |
| void [Dispose](../textwriter/dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger den underliggande strömmen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypsobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| virtual void [Flush](../textwriter/flush/)() | Spolar innehållet i bufferten till den underliggande strömmen. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Returnerar den för närvarande använda kodningen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Returnerar det för närvarande använda [IFormatProvider](../../system/iformatprovider/)-objektet. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Returnerar det för närvarande använda [IFormatProvider](../../system/iformatprovider/)-objektet. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Returnerar en radavslutningssträng. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Returnerar en radavslutningssträng. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknardatastrukturen som är kopplad till objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | Returnerar den för närvarande använda StringBuilder-objektet. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Ställer in en radavslutningssträng. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Anger det n'te mallargumentet som en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar det aktuella värdet av den delade referensräknaren. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräknaren. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Skapar en ny instans av [StringWriter](./) med den angivna StringBuilder-objektet och [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Skapar en ny instans av [StringWriter](./) med den angivna StringBuilder-objektet och [IFormatProvider](../../system/iformatprovider/) från den aktuella kulturen. |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Skapar en ny instans av [StringWriter](./) med den angivna [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)() | Skapar en ny instans av [StringWriter](./) med [IFormatProvider](../../system/iformatprovider/) från den aktuella kulturen. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Returnerar den underliggande strängen. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [Write](./write/)(char_t) override | Skriver det angivna tecknet till strömmen. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Skriver det angivna delintervallet av tecken från den angivna teckenarrayen till strömmen. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Skriver den angivna strängen till strömmen. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Skriver den strängrepresentation av det angivna objektet till strömmen. |
| virtual void [Write](../textwriter/write/)(**bool**) | Skriver den strängrepresentation av det angivna booleska värdet till strömmen. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Skriver den strängrepresentation av det angivna [Decimal](../../system/decimal/)-objektet till strömmen. |
| virtual void [Write](../textwriter/write/)(**double**) | Skriver den strängrepresentation av det angivna dubbelprecisionflyttalvärdet till strömmen. |
| virtual void [Write](../textwriter/write/)(int) | Skriver den strängrepresentation av det angivna 32-bit heltalsvärdet till strömmen. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Skriver den strängrepresentation av det angivna 64-bit heltalsvärdet till strömmen. |
| virtual void [Write](../textwriter/write/)(**float**) | Skriver den strängrepresentation av det angivna enkelprecisionflyttalvärdet till strömmen. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Skriver den strängrepresentation av det angivna osignerade 32-bit heltalsvärdet till strömmen. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Skriver den strängrepresentation av det angivna osignerade 64-bit heltalsvärdet till strömmen. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Skriver alla tecken från den angivna arrayen till strömmen. |
| virtual void [Write](../textwriter/write/)(const char_t *) | Skriver den angivna C-strängen till strömmen. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Skriver den strängrepresentation av det angivna [TypeInfo](../../system/typeinfo/)-objektet till strömmen. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Skriver de angivna värdena formaterade enligt det angivna formatet till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)() | Skriver radavslutningstecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Skriver den strängrepresentation av det angivna objektet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Skriver den strängrepresentation av det angivna booleska värdet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Skriver det angivna tecknet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Skriver den strängrepresentation av det angivna [Decimal](../../system/decimal/)-objektet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Skriver den strängrepresentation av det angivna dubbelprecisionflyttalvärdet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Skriver den strängrepresentation av det angivna 32-bit heltalsvärdet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Skriver den strängrepresentation av det angivna 64-bit heltalsvärdet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Skriver den strängrepresentation av det angivna enkelprecisionflyttalvärdet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | Skriver den angivna strängen följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Skriver den strängrepresentation av det angivna osignerade 32-bit heltalsvärdet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Skriver den strängrepresentation av det angivna osignerade 64-bit heltalsvärdet följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Skriver alla tecken från den angivna arrayen följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Skriver det angivna delintervallet av UTF-16-tecken från den angivna teckenarrayen följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | Skriver den angivna C-strängen följt av radavslutningstecken till strömmen. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Skriver den strängrepresentation av det angivna [TypeInfo](../../system/typeinfo/)-objektet följt av radavslutningstecken till strömmen. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Skriver de angivna värdena formaterade enligt det angivna formatet följt av radavslutningstecken till strömmen. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destruktor. |

## Se också

* Klass [TextWriter](../textwriter/)
* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)