---
title: FontFamily
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en grupp av teckensnitt som delar en liknande grundläggande design. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körtidsfel och/eller assertfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den som argument till funktioner."
type: docs
weight: 105
url: /sv/system.drawing/fontfamily/
---
## FontFamily klass

Representerar en grupp av typsnitt som delar en liknande grundläggande design. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class FontFamily : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [Clone](./clone/)() | Returnerar en kopia av det aktuella [FontFamily](./) objektet. |
| void [Dispose](./dispose/)() | Frigör alla operativsystemresurser som erhållits av det aktuella objektet. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Bestämmer om de aktuella och de specificerade objekten är identiska. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
|  [FontFamily](./fontfamily/)(const [String](../../system/string/)\&) | Skapar en ny instans av [FontFamily](./)-klassen som representerar en teckensnittsfamilj med det angivna namnet. |
|  [FontFamily](./fontfamily/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::FontCollection](../../system.drawing.text/fontcollection/)\>\&) | Skapar en ny instans av [FontFamily](./) i den specificerade FontCollection med det angivna namnet. |
|  [FontFamily](./fontfamily/)([Text::GenericFontFamilies](../../system.drawing.text/genericfontfamilies/)) | Skapar en ny instans av [FontFamily](./) från den specificerade generiska teckensnittsfamiljen. |
| static [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\>\> [get_Families](./get_families/)() | Returnerar en array som innehåller alla [FontFamily](./)-objekt som är associerade med det aktuella grafiksammanhanget. |
| static [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [get_GenericMonospace](./get_genericmonospace/)() | Returnerar ett [FontFamily](./)-objekt som representerar en generisk monospaced teckensnittsfamilj. |
| static [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [get_GenericSansSerif](./get_genericsansserif/)() | Returnerar ett [FontFamily](./)-objekt som representerar en generisk sans serif-teckensnittsfamilj. |
| static [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [get_GenericSerif](./get_genericserif/)() | Returnerar ett [FontFamily](./)-objekt som representerar en generisk serif-teckensnittsfamilj. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Returnerar namnet på teckensnittsfamiljen som representeras av det aktuella objektet. |
| int [GetCellAscent](./getcellascent/)([FontStyle](../fontstyle/)) | Returnerar cellascent för teckensnittsfamiljen som det aktuella objektet representerar för den angivna teckensnittsstilen. |
| int [GetCellDescent](./getcelldescent/)([FontStyle](../fontstyle/)) | Returnerar cellnedgång för teckensnittsfamiljen som det aktuella objektet representerar för den angivna teckensnittsstilen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräkningsdatastruktur som är associerad med objektet. |
| int [GetEmHeight](./getemheight/)([FontStyle](../fontstyle/)) | Returnerar höjden på em-kvadraten i teckensnittets designenheter för den angivna stilen. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| int [GetLineSpacing](./getlinespacing/)([FontStyle](../fontstyle/)) | Returnerar radavståndet för teckensnittsfamiljen som det aktuella objektet representerar för den angivna teckensnittsstilen. |
| [String](../../system/string/) [GetName](./getname/)(int) const | Returnerar namnet på teckensnittsfamiljen som det aktuella objektet representerar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| **bool** [IsStyleAvailable](./isstyleavailable/)([FontStyle](../fontstyle/)) | Bestämmer om den specificerade teckensnittsstilen är tillgänglig. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsen för låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen inget, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion i subklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen inget, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion i subklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delat referensräknare med det angivna värdet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n'te mallargumentet till en svag pekare (i stället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-sats för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual  [~FontFamily](./~fontfamily/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [System::Drawing](../)
* Bibliotek [Aspose.Slides](../../)