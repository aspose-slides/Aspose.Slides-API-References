---
title: FileInfo
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en sökväg till en fil och en fil som refereras av denna sökväg samt tillhandahåller metoder för att manipulera den. Objekt av denna klass bör endast allokeras med hjälp av System::MakeObject()-funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kan leda till körningstidfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 274
url: /sv/system.io/fileinfo/
---
## FileInfo klass

Representerar en sökväg till en fil och en fil som refereras av denna sökväg samt tillhandahåller metoder för att manipulera den. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körningstidfel och/eller påståendenfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | Öppnar en fil som representeras av det aktuella objektet för att skriva text med UTF-8-kodning, i 'Append'-läge utan delning. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | Kopierar filen som representeras av det aktuella objektet till den angivna platsen. Om målfilen redan finns misslyckas kopieringen. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | Kopierar filen som representeras av det aktuella objektet till den angivna platsen. En parameter anger om en befintlig målfil ska skrivas över. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | Skapar en fil på den plats som anges av sökvägen som representeras av det aktuella objektet och öppnar den för läsning och skrivning, i trunkeringsläge utan delning. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | Skapar en fil på den plats som anges av sökvägen som representeras av det aktuella objektet och öppnar den för att skriva text med UTF-8-kodning utan delning. |
| void [Decrypt](./decrypt/)() | INTE IMPLEMENTERAD. |
| void [Delete](./delete/)() override | Tar bort filen som representeras av det aktuella objektet. |
| void [Encrypt](./encrypt/)() | INTE IMPLEMENTERAD. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil jämförelse av flyttal där två **double** betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
|  [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | Skapar en ny instans av [FileInfo](./)-klassen som representerar den angivna filen. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Gör ingenting. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Returnerar attributen för den entitet som representeras av det aktuella objektet. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Returnerar skapandetiden för den entitet som representeras av det aktuella objektet som lokal tid. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Returnerar skapandetiden för den entitet som representeras av det aktuella objektet som UTC-tid. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | Returnerar ett [DirectoryInfo](../directoryinfo/)-objekt som representerar den katalog där filen som representeras av det aktuella objektet finns. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | Returnerar det fullständiga namnet på katalogen där filen som representeras av det aktuella objektet är placerad. |
| **bool** [get_Exists](./get_exists/)() override | Returnerar ett värde som indikerar om filen finns. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Returnerar filens filändelse för den fil som representeras av det aktuella objektet. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Returnerar det fullständiga namnet (inklusive sökväg) för den entitet som representeras av det aktuella objektet. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Returnerar ett värde som indikerar om ReadOnly-attributet är satt. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Returnerar den senaste åtkomsttiden för den entitet som representeras av det aktuella objektet som lokal tid. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Returnerar den senaste åtkomsttiden för den entitet som representeras av det aktuella objektet som UTC-tid. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Returnerar den senaste skrivtiden för den entitet som representeras av det aktuella objektet som lokal tid. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Returnerar den senaste skrivtiden för den entitet som representeras av det aktuella objektet som UTC-tid. |
| **int64_t** [get_Length](./get_length/)() | Returnerar storleken på filen i byte. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Returnerar filens namn. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknardatastukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Flyttar filen som representeras av det aktuella objektet till den angivna platsen. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | Öppnar filen som representeras av det aktuella objektet i angivet läge för läsning och skrivning utan delning. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | Öppnar filen som representeras av det aktuella objektet i angivet läge, med den specificerade åtkomsttypen och utan delning. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Öppnar filen som representeras av det aktuella objektet i angivet läge, med den specificerade åtkomsttypen och delningsalternativ. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | Öppnar en fil som representeras av det aktuella objektet endast för läsning, i 'Open'-läge med delad åtkomst för läsning. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | Öppnar den befintliga filen på den plats som anges av sökvägen som representeras av det aktuella objektet för att läsa text med UTF-8-kodning utan delning. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | Öppnar en fil som representeras av det aktuella objektet endast för skrivning, i 'OpenOrCreate'-läge utan delning. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför en värdetyp med nullptr via referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| void [Refresh](../filesysteminfo/refresh/)() | Uppdaterar tillståndet för det aktuella objektet. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med det angivna värdet. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ersätter innehållet i en angiven målfil med filen som representeras av det aktuella [FileInfo](./)-objektet och skapar en säkerhetskopia av den ersatta filen. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Ersätter innehållet i en angiven målfil med filen som representeras av det aktuella [FileInfo](./)-objektet och skapar en säkerhetskopia av den ersatta filen. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Sätter de angivna attributen på den entitet som representeras av det aktuella objektet. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Sätter skapandetiden för den entitet som representeras av det aktuella objektet som lokal tid. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Sätter skapandetiden för den entitet som representeras av det aktuella objektet som UTC-tid. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | Sätter eller tar bort ReadOnly-attributet på filen. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Sätter den senaste åtkomsttiden för den entitet som representeras av det aktuella objektet som lokal tid. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Sätter den senaste åtkomsttiden för den entitet som representeras av det aktuella objektet som UTC-tid. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Sätter den senaste skrivtiden för den entitet som representeras av det aktuella objektet som lokal tid. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Sätter den senaste skrivtiden för den entitet som representeras av det aktuella objektet som UTC-tid. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en weak-pekare (istället för shared). Tillåter byte av pekare i behållare till weak-läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Returnerar en sökväg som representeras av det aktuella objektet. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar weak-referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar weak-referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se också

* Klass [FileSystemInfo](../filesysteminfo/)
* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)