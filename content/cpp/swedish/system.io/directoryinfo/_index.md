---
title: DirectoryInfo
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en filsökväg, en katalog som refereras av denna sökväg och tillhandahåller instansmetoder för att manipulera kataloger. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert-fel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 248
url: /sv/system.io/directoryinfo/
---
## DirectoryInfo klass

Representerar en filsystemsväg, en katalog som refereras av denna väg och tillhandahåller instansmetoder för att manipulera kataloger. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assert-fel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [Create](./create/)() | Skapar en katalog på sökvägen som representeras av det aktuella objektet. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [CreateSubdirectory](./createsubdirectory/)(const [String](../../system/string/)\&) | Skapar underkataloger på den angivna sökvägen. |
| void [Delete](./delete/)() override | Tar bort katalogen som refereras av sökvägen som representeras av det aktuella objektet om katalogen är tom. |
| void [Delete](./delete/)(**bool**) | Tar bort katalogen som refereras av sökvägen som representeras av det aktuella objektet. En parameter anger om katalogens innehåll ska tas bort rekursivt om katalogen inte är tom. |
| [DirectoryInfo](./directoryinfo/)(const [String](../../system/string/)\&) | Konstruerar en instans av [DirectoryInfo](./)-klassen på den angivna sökvägen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)() | Returnerar en enumererbar samling som innehåller alla kataloger som finns i katalogen som representeras av det aktuella objektet. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&) | Söker efter kataloger som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Söker efter kataloger som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har detta objekt som rot. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)() | Returnerar en enumererbar samling som innehåller alla filer som finns i katalogen som representeras av det aktuella objektet. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&) | Söker efter filer som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Söker efter filer som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har detta objekt som rot. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | Returnerar en enumererbar samling som innehåller alla filer och kataloger som finns i katalogen som representeras av det aktuella objektet. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&) | Söker efter filer och kataloger som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har detta objekt som rot. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C#-semantiken [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyps-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Gör ingenting. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Returnerar attributen för entiteten som representeras av det aktuella objektet. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Returnerar skapandetiden för entiteten som representeras av det aktuella objektet i lokal tid. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Returnerar skapandetiden för entiteten som representeras av det aktuella objektet i UTC-tid. |
| **bool** [get_Exists](./get_exists/)() override | Avgör om sökvägen som representeras av det aktuella objektet pekar på en befintlig katalog. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Returnerar filens filändelse för filen som representeras av det aktuella objektet. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Returnerar det fullständiga namnet (inklusive sökväg) för entiteten som representeras av det aktuella objektet. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Returnerar den senaste åtkomsttiden för entiteten som representeras av det aktuella objektet i lokal tid. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Returnerar den senaste åtkomsttiden för entiteten som representeras av det aktuella objektet i UTC-tid. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Returnerar den senaste skrivtiden för entiteten som representeras av det aktuella objektet i lokal tid. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Returnerar den senaste skrivtiden för entiteten som representeras av det aktuella objektet i UTC-tid. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Returnerar namnet på entiteten som refereras av sökvägen som representeras av det aktuella objektet. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Parent](./get_parent/)() | Returnerar en delad pekare till ett [DirectoryInfo](./)-objekt som representerar en sökväg som pekar på föräldrakatalogen till katalogen som representeras av det aktuella objektet. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Root](./get_root/)() | Returnerar en delad pekare till ett [DirectoryInfo](./)-objekt som representerar en sökväg som pekar på rotkatalogen till katalogen som representeras av det aktuella objektet. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenskontostrukturen som är associerad med objektet. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)() | Returnerar en array som innehåller delade pekare till [DirectoryInfo](./)-objekt som representerar alla kataloger som finns i katalogen som representeras av det aktuella objektet. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&) | Söker efter kataloger som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Söker efter kataloger som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har detta objekt som rot. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)() | Returnerar en array som innehåller delade pekare till [FileInfo](../fileinfo/)-objekt som representerar alla kataloger som finns i katalogen som representeras av det aktuella objektet. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&) | Söker efter filer som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Söker efter filer som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har detta objekt som rot. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)() | Returnerar en array som innehåller delade pekare till [FileSystemInfo](../filesysteminfo/)-objekt som representerar alla filer och kataloger som finns i katalogen som representeras av det aktuella objektet. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&) | Söker efter filer och kataloger som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har detta objekt som rot. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C#-metoden [Object.GetHashCode()](../../system/object/gethashcode/). Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C#-anropet [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet är en instans av den typ som beskrivs av targetType. Analog till C#-operatorn `is`. |
| void [Lock](../../system/object/lock/)() | Implementerar C#-`lock()`-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C#-metoden [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Möjliggör kloning av anpassade typer. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Flyttar katalogen som representeras av det aktuella objektet och allt dess innehåll till den angivna platsen. |
| [Object](../../system/object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen inget, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen inget, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetyp-objekt med nullptr efter referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| void [Refresh](../filesysteminfo/refresh/)() | Uppdaterar tillståndet för det aktuella objektet. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknet med det angivna värdet. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Sätter de angivna attributen på entiteten som representeras av det aktuella objektet. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Sätter skapandetiden för entiteten som representeras av det aktuella objektet i lokal tid. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Sätter skapandetiden för entiteten som representeras av det aktuella objektet i UTC-tid. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Sätter den senaste åtkomsttiden för entiteten som representeras av det aktuella objektet i lokal tid. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Sätter den senaste åtkomsttiden för entiteten som representeras av det aktuella objektet i UTC-tid. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Sätter den senaste skrivtiden för entiteten som representeras av det aktuella objektet i lokal tid. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Sätter den senaste skrivtiden för entiteten som representeras av det aktuella objektet i UTC-tid. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n-te mallargumentet till en svag pekare (istället för en delad). Möjliggör byte av pekare i behållare till svag modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar det aktuella värdet av den delade referensräknaren. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräkningen. Bör ej anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräkningen. Bör ej anropas direkt; använd smarta pekare eller ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Returnerar en sträng som innehåller sökvägen som representeras av det aktuella objektet. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C#-`typeof([System.Object](../../system/object/))`-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C#-`lock()`-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar den svaga referensräkningen. Bör ej anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar den svaga referensräkningen. Bör ej anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se också

* Klass [FileSystemInfo](../filesysteminfo/)
* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)