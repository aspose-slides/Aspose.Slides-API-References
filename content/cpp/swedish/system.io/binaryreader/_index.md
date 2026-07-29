---
title: BinaryReader
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en läsare som läser primitiva datatyper som binär data i en viss kodning. Objekt av den här klassen bör endast allokeras med hjälp av System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 92
url: /sv/system.io/binaryreader/
---
## BinaryReader klass


Representerar en läsare som läser primitiva datatyper som binär data i en viss kodning. Objekt av den här klassen bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertion-fel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class BinaryReader : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Skapar en instans av [BinaryReader](./) klass som läser data från den angivna strömmen med UTF-8-kodning. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Skapar en instans av [BinaryReader](./) klass som läser data från den angivna strömmen med den angivna kodning. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | Skapar en instans av [BinaryReader](./) klass som läser data från den angivna strömmen med den angivna kodning. |
| virtual void [Close](./close/)() | Stänger det aktuella [BinaryReader](./)-objektet och den underliggande inmatningsströmmen. |
| void [Dispose](./dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger den underliggande strömmen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Efterliknar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Efterliknar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | Returnerar inmatningsströmmen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska typvärdet för objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar faktiskt ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar faktiskt ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| virtual int [PeekChar](./peekchar/)() | Läser ett tecken från inmatningsströmmen utan att flytta läsmarkören. |
| virtual int [Read](./read/)() | Läser ett tecken från inmatningsströmmen. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Läser det angivna antalet byte från inmatningsströmmen och skriver dem till den angivna byte-arrayen. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Läser det angivna antalet tecken från inmatningsströmmen, konverterar dem till UTF-16-kodning och skriver de resulterande UTF-16-tecknen till den angivna teckenarrayen med start vid den angivna positionen. |
| virtual **bool** [ReadBoolean](./readboolean/)() | Läser en byte från inmatningsströmmen och returnerar dess booleska representation. |
| virtual **uint8_t** [ReadByte](./readbyte/)() | Läser en byte från inmatningsströmmen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | Läser det angivna antalet byte från inmatningsströmmen. |
| virtual char_t [ReadChar](./readchar/)() | Läser ett tecken från inmatningsströmmen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | Läser det angivna antalet tecken från inmatningsströmmen och returnerar dem i UTF-16-kodning. |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | INTE IMPLEMENTERAD. |
| virtual **double** [ReadDouble](./readdouble/)() | Läser 8 byte från inmatningsströmmen och returnerar dem som ett dubbelprecisions-flyttal. |
| virtual **int16_t** [ReadInt16](./readint16/)() | Läser 2 byte från inmatningsströmmen och returnerar dem som ett 16-bitars heltal. |
| virtual int [ReadInt32](./readint32/)() | Läser 4 byte från inmatningsströmmen och returnerar dem som ett 32-bitars heltal. |
| virtual **int64_t** [ReadInt64](./readint64/)() | Läser 8 byte från inmatningsströmmen och returnerar dem som ett 64-bitars heltal. |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | Läser en byte från inmatningsströmmen och returnerar den som ett signerat 8-bitars heltal. |
| virtual **float** [ReadSingle](./readsingle/)() | Läser 4 byte från inmatningsströmmen och returnerar dem som ett enkelprecisions-flyttal. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Läser en sträng från den aktuella strömmen. Strängen föregås av dess längd, kodad som ett heltal sju bitar i taget. |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | Läser 2 byte från inmatningsströmmen och returnerar dem som ett unsigned 16-bitars heltal. |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | Läser 4 byte från inmatningsströmmen och returnerar dem som ett unsigned 32-bitars heltal. |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | Läser 8 byte från inmatningsströmmen och returnerar dem som ett unsigned 64-bitars heltal. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför ett värdetypobjekt med nullptr efter referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n-te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar den svaga referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar den svaga referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector alternativt. |
| virtual  [~BinaryReader](./~binaryreader/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigir alla interna datastrukturer. |

## Se även

* Klass [IDisposable](../../system/idisposable/)
* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)