---
title: ContentDispositionHeaderValue
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett värde för 'Content-Disposition'-headern. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Wrapa alltid den här klassen i en System::SmartPtr-pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 27
url: /sv/system.net.http.headers/contentdispositionheadervalue/
---
## ContentDispositionHeaderValue klass

Representerar ett värde för 'Content-Disposition'-headern. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Wrapa alltid den här klassen i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class ContentDispositionHeaderValue : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [ContentDispositionHeaderValue](./contentdispositionheadervalue/)() | Skapar en ny instans. |
|  [ContentDispositionHeaderValue](./contentdispositionheadervalue/)([String](../../system/string/)) | Skapar en ny instans. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_CreationDate](./get_creationdate/)() | Hämtar filens skapandedatum. |
| [String](../../system/string/) [get_DispositionType](./get_dispositiontype/)() | Hämtar en dispositionstyp. |
| [String](../../system/string/) [get_FileName](./get_filename/)() | Hämtar ett värde som bestämmer hur ett filnamn ska konstrueras för att lagra meddelandets nyttolast. Det används när enheten är fristående och lagras i en separat fil. |
| [String](../../system/string/) [get_FileNameStar](./get_filenamestar/)() | Hämtar ett värde som bestämmer hur filnamn ska konstrueras för att lagra meddelandets nyttolast. Det används när enheterna är fristående och lagras i separata filer. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_ModificationDate](./get_modificationdate/)() | Hämtar filens ändringsdatum. |
| [String](../../system/string/) [get_Name](./get_name/)() | Hämtar ett namn för en del av innehållskroppen. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](./get_parameters/)() | Returnerar en parameterkollektion för 'Content-Disposition'-headern. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_ReadDate](./get_readdate/)() | Hämtar datumet då filen senast lästes. |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_Size](./get_size/)() | Hämtar en ungefärlig filstorlek. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| static **int32_t** [GetDispositionTypeLength](./getdispositiontypelength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Konverterar en given sträng från det angivna indexet till en instans av [ContentDispositionHeaderValue](./)-klassen. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning för C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar faktiskt ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static [System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Konverterar en given sträng till en instans av [ContentDispositionHeaderValue](./)-klassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför ett värdetyp-objekt med nullptr genom referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_CreationDate](./set_creationdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | Sätter filens skapandedatum. |
| void [set_DispositionType](./set_dispositiontype/)([String](../../system/string/)) | Sätter en dispositionstyp. |
| void [set_FileName](./set_filename/)([String](../../system/string/)) | Sätter ett värde som bestämmer hur ett filnamn ska konstrueras för att lagra meddelandets nyttolast. Det används när enheten är fristående och lagras i en separat fil. |
| void [set_FileNameStar](./set_filenamestar/)([String](../../system/string/)) | Sätter ett värde som bestämmer hur filnamn ska konstrueras för att lagra meddelandets nyttolast. Det används när enheterna är fristående och lagras i separata filer. |
| void [set_ModificationDate](./set_modificationdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | Sätter filens ändringsdatum. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Sätter ett namn för en del av innehållskroppen. |
| void [set_ReadDate](./set_readdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | Sätter datumet då filen senast lästes. |
| void [set_Size](./set_size/)([Nullable](../../system/nullable/)\<**int64_t**\>) | Sätter en ungefärlig filstorlek. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n'te mallargumentet till en svag pekare (istället för delad). Möjliggör att byta pekare i containrar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](./)\>\&) | Försöker konvertera en given sträng till en instans av [ContentDispositionHeaderValue](./)-klassen. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning för C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigir alla interna datastrukturer. |

## Se även

* Klass [ICloneable](../../system/icloneable/)
* Namnrymd [System::Net::Http::Headers](../)
* Bibliotek [Aspose.Slides](../../)