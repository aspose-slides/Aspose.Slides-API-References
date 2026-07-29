---
title: FileSystemInfo
second_title: Aspose.Slides för C++ API-referens
description: "Basisklassen för FileInfo och DirectoryInfo. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av den här typen på stacken eller med operator new, eftersom det kommer att leda till körfel och/eller assert-fel. Packa alltid in denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 300
url: /sv/system.io/filesysteminfo/
---
## FileSystemInfo klass


Basklass för [FileInfo](../fileinfo/) och [DirectoryInfo](../directoryinfo/). Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körtidsfel och/eller assertionsfel. Paketera alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class FileSystemInfo : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual void [Delete](./delete/)() | Tar bort enheten som representeras av det aktuella objektet. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med hjälp av C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual void [Finalize](./finalize/)() | Gör ingenting. |
| [FileAttributes](../fileattributes/) [get_Attributes](./get_attributes/)() | Returnerar attributen för enheten som representeras av det aktuella objektet. |
| [DateTime](../../system/datetime/) [get_CreationTime](./get_creationtime/)() | Returnerar skapelsestiden för enheten som representeras av det aktuella objektet som lokal tid. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](./get_creationtimeutc/)() | Returnerar skapelsestiden för enheten som representeras av det aktuella objektet som UTC-tid. |
| virtual **bool** [get_Exists](./get_exists/)() | Avgör om enheten som refereras av sökvägen som representeras av det aktuella objektet finns. |
| [String](../../system/string/) [get_Extension](./get_extension/)() | Returnerar filens filändelse för objektet som representeras av det aktuella objektet. |
| virtual [String](../../system/string/) [get_FullName](./get_fullname/)() | Returnerar det fullständiga namnet (inklusive sökväg) för enheten som representeras av det aktuella objektet. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](./get_lastaccesstime/)() | Returnerar den senaste åtkomsttiden för enheten som representeras av det aktuella objektet som lokal tid. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](./get_lastaccesstimeutc/)() | Returnerar den senaste åtkomsttiden för enheten som representeras av det aktuella objektet som UTC-tid. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](./get_lastwritetime/)() | Returnerar den senaste skrivtiden för enheten som representeras av det aktuella objektet som lokal tid. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](./get_lastwritetimeutc/)() | Returnerar den senaste skrivtiden för enheten som representeras av det aktuella objektet som UTC-tid. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Returnerar ett namn på enheten som representeras av det aktuella objektet. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| void [Refresh](./refresh/)() | Uppdaterar tillståndet för det aktuella objektet. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_Attributes](./set_attributes/)([FileAttributes](../fileattributes/)) | Ställer in de angivna attributen på enheten som representeras av det aktuella objektet. |
| void [set_CreationTime](./set_creationtime/)([DateTime](../../system/datetime/)) | Ställer in skapelsestiden för enheten som representeras av det aktuella objektet som lokal tid. |
| void [set_CreationTimeUtc](./set_creationtimeutc/)([DateTime](../../system/datetime/)) | Ställer in skapelsestiden för enheten som representeras av det aktuella objektet som UTC-tid. |
| void [set_LastAccessTime](./set_lastaccesstime/)([DateTime](../../system/datetime/)) | Ställer in den senaste åtkomsttiden för enheten som representeras av det aktuella objektet som lokal tid. |
| void [set_LastAccessTimeUtc](./set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Ställer in den senaste åtkomsttiden för enheten som representeras av det aktuella objektet som UTC-tid. |
| void [set_LastWriteTime](./set_lastwritetime/)([DateTime](../../system/datetime/)) | Ställer in den senaste skrivtiden för enheten som representeras av det aktuella objektet som lokal tid. |
| void [set_LastWriteTimeUtc](./set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Ställer in den senaste skrivtiden för enheten som representeras av det aktuella objektet som UTC-tid. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (i stället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuell värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräknaren. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar den svaga referensräknaren. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar den svaga referensräknaren. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |
## Se även

* Klass [Object](../../system/object/)
* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)