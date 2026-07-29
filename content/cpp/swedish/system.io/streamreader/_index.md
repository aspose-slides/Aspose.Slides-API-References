---
title: StreamReader
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en läsare som läser tecken från en byte-ström. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kan leda till körningstidfel och/eller assertionsfel. Packa alltid in denna klass i en System::SmartPtr pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 378
url: /sv/system.io/streamreader/
---
## StreamReader klass


Representerar en läsare som läser tecken från en byte-ström. Objekt av denna klass ska endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det leder till körningstidfel och/eller assertionsfel. Packa alltid in denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class StreamReader : public System::IO::TextReader
```

## Metoder

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Stänger den aktuella och underliggande strömmarna. |
| virtual void [Dispose](./dispose/)(**bool**) | Frigör alla resurser som används av det aktuella objektet och stänger den underliggande strömmen. |
| void [Dispose](./dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger den underliggande strömmen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Returnerar en delad pekare till ett objekt som representerar den underliggande strömmen. |
| [EncodingPtr](../../system/encodingptr/) [get_CurrentEncoding](./get_currentencoding/)() | Returnerar den för närvarande använda kodningen. |
| **bool** [get_EndOfStream](./get_endofstream/)() | Returnerar ett värde som indikerar om slutet av strömmen har nåtts. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| int [Peek](./peek/)() override | Läser ett enskilt tecken från strömmen utan att ändra läsmarkören. |
| int [Read](./read/)() override | Läser ett enskilt tecken från strömmen. |
| int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) override | Läser det angivna antalet tecken från strömmen, konverterar dem till UTF-16-kodning och skriver de resulterande UTF-16-tecknen till den angivna teckenarrayen med början på den angivna positionen. |
| virtual int [ReadBlock](../textreader/readblock/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Läser det angivna maximala antalet tecken från den aktuella textläsaren och skriver data till en buffer med början på det angivna indexet. |
| [String](../../system/string/) [ReadLine](./readline/)() override | Läser tecken från strömmen tills slutet av den aktuella raden. |
| [String](../../system/string/) [ReadToEnd](./readtoend/)() override | Läser tecken från strömmen tills slutet av strömmen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av den delade referensräknaren. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Konstruktor för [StreamReader](./)-objekt som läser tecken från den angivna underliggande strömmen med UTF-8-kodning och en buffer med standardstorlek 1024 byte. |
| [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **bool**) | Konstruktor för [StreamReader](./)-objekt som läser tecken från den angivna underliggande strömmen med UTF-8-kodning och en buffer med standardstorlek 1024 byte. En parameter anger om byte order mark-detektering ska vara aktiverad. |
| [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Konstruktor för [StreamReader](./)-objekt som läser tecken från den angivna underliggande strömmen med den angivna kodningen och en buffer med standardstorlek 1024 byte. |
| [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Konstruktor för [StreamReader](./)-objekt som läser tecken från den angivna underliggande strömmen med den angivna kodningen och en buffer med standardstorlek 1024 byte. En parameter anger om byte order mark-detektering ska vara aktiverad. |
| [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Konstruktor för [StreamReader](./)-objekt som läser tecken från den angivna underliggande strömmen med den angivna kodningen och en buffer med angiven storlek. En parameter anger om byte order mark-detektering ska vara aktiverad. |
| [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&) | Konstruktor för [StreamReader](./)-objekt som läser tecken från den angivna filen med UTF-8-kodning och en buffer med standardstorlek 4096 byte. |
| [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, **bool**) | Konstruktor för [StreamReader](./)-objekt som läser tecken från den angivna filen med UTF-8-kodning och en buffer med standardstorlek 4096 byte. En parameter anger om byte order mark-detektering ska vara aktiverad. |
| [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Konstruktor för [StreamReader](./)-objekt som läser tecken från den angivna filen med den angivna kodningen och en buffer med standardstorlek 4096 byte. |
| [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Konstruktor för [StreamReader](./)-objekt som läser tecken från den angivna underliggande strömmen med den angivna kodningen och en buffer med standardstorlek 4096 byte. En parameter anger om byte order mark-detektering ska vara aktiverad. |
| [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Konstruktor för [StreamReader](./)-objekt som läser tecken från den angivna filen med den angivna kodningen och en buffer med angiven storlek. En parameter anger om byte order mark-detektering ska vara aktiverad. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
| [~StreamReader](./~streamreader/)() | Destruktor. |

## Se även

* Klass [TextReader](../textreader/)
* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)