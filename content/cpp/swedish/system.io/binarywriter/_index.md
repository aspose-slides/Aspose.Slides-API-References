---
title: BinaryWriter
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en skrivare som skriver värden av primitiva typer till en byte-ström. Objekt av den här klassen bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assert-fel. Wrappa alltid denna klass i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 105
url: /sv/system.io/binarywriter/
---
## BinaryWriter klass

Representerar en skrivare som skriver värden av primitiva typer till en byte-ström. Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assert-fel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class BinaryWriter : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [BinaryWriter](./binarywriter/)(const [StreamPtr](../../system/streamptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Skapar en instans av [BinaryWriter](./) klass som skriver data till den angivna strömmen med den angivna kodningen. |
| void [Close](./close/)() | Stänger det aktuella [BinaryWriter](./)-objektet och den underliggande utmatningsströmmen. |
| void [Dispose](./dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger den underliggande strömmen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med hjälp av C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| void [Flush](./flush/)() | Spolar utmatningsströmmen. |
| [StreamPtr](../../system/streamptr/) [get_BaseStream](./get_basestream/)() | Returnerar utmatningsströmmen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknar-datastrukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Aktiverar hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Aktiverar kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar ett objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar faktiskt ingenting, initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar faktiskt ingenting, initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens av värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med angivet värde. |
| **int64_t** [Seek](./seek/)(int, [System::IO::SeekOrigin](../seekorigin/)) | Ställer in positionen för den ström som representeras av det aktuella objektet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te template-argument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för det delade referensräknaren. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar det delade referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar det delade referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Aktiverar konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning upp enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar det svaga referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar det svaga referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual void [Write](./write/)(**uint8_t**) | Skriver det angivna osignerade 8-bit-heltalsvärdet till utmatningsströmmen. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Skriver det angivna delintervallet av byte från den angivna byte-arrayen till utmatningsströmmen. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Skriver det angivna delintervallet av UTF-16-tecken från den angivna teckenarrayen till utmatningsströmmen. |
| virtual void [Write](./write/)(**bool**) | Skriver en enskild byte med värdet 0 om **value** är 'true' och 1 om **value** är 'false' till utmatningsströmmen. |
| virtual void [Write](./write/)(char16_t) | Skriver det angivna 16-bit-bredde teckenvärdet till utmatningsströmmen. |
| virtual void [Write](./write/)(**int16_t**) | Skriver det angivna 16-bit-heltalsvärdet till utmatningsströmmen. |
| virtual void [Write](./write/)(int) | Skriver det angivna 32-bit-heltalsvärdet till utmatningsströmmen. |
| virtual void [Write](./write/)(**int64_t**) | Skriver det angivna 64-bit-heltalsvärdet till utmatningsströmmen. |
| virtual void [Write](./write/)(**uint16_t**) | Skriver det angivna osignerade 16-bit-heltalsvärdet till utmatningsströmmen. |
| virtual void [Write](./write/)(**uint32_t**) | Skriver det angivna osignerade 32-bit-heltalsvärdet till utmatningsströmmen. |
| virtual void [Write](./write/)(**uint64_t**) | Skriver det angivna osignerade 64-bit-heltalsvärdet till utmatningsströmmen. |
| virtual void [Write](./write/)(**float**) | Skriver det angivna enkelprecisions-flyttalsvärdet till utmatningsströmmen. |
| virtual void [Write](./write/)(**double**) | Skriver det angivna dubbelprecisions-flyttalsvärdet till utmatningsströmmen. |
| virtual void [Write](./write/)(const [Decimal](../../system/decimal/)\&) | Skriver byte-representationen av det angivna [Decimal](../../system/decimal/)-värdet till utmatningsströmmen. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Skriver en längd-prefixed sträng i den aktuella kodningen till utmatningsströmmen. |
| virtual void [Write](./write/)(const char_t *) | Skriver en längd-prefixed sträng i den aktuella kodningen till utmatningsströmmen. |
|  [~BinaryWriter](./~binarywriter/)() | Destruktör. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigir alla interna datastrukturer. |

## Se också

* Klass [IDisposable](../../system/idisposable/)
* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)