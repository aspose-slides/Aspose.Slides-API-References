---
title: Details_InvalidTimeZoneException
second_title: Aspose.Slides C++ API hivatkozás
description: "InvalidTimeZoneException akkor dobódik, amikor az időzóna információ érvénytelen. Soha ne hozza létre ennek az osztálynak a példányait kézzel. Használja helyette az InvalidTimeZoneException osztályt. Soha ne csomagolja be az InvalidTimeZoneException osztálypéldányokat a System::SmartPtr-be."
type: docs
weight: 534
url: /hu/system/details_invalidtimezoneexception/
---
## Details_InvalidTimeZoneException osztály

Az InvalidTimeZoneException akkor dobódik, amikor az időzóna információ érvénytelen. Soha ne hozzon létre példányokat ebből az osztályból kézzel. Használja helyette az InvalidTimeZoneException osztályt. Soha ne csomagoljon bele az InvalidTimeZoneException osztálypéldányokat a [System::SmartPtr](../smartptr/)-ba.

```cpp
class Details_InvalidTimeZoneException : public System::Details_Exception
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Objektumokat hasonlít a C# [Object.Equals](../object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít C# stílusban. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Az IEC 60559:1989 szerinti NaN valamennyi értéktől, így a NaN-tól is eltérő, de a C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár a szabvány szerint a NaN nem egyenlő egyik értékkel sem, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Az IEC 60559:1989 szerinti NaN valamennyi értéktől, így a NaN-tól is eltérő, de a C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár a szabvány szerint a NaN nem egyenlő egyik értékkel sem, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Szótárat ad vissza egyedi kivétel adatokkal. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | 32 bites egész értéket ad vissza, amely a jelenlegi objektum által reprezentált kivételhez társított HRESULT kód. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Referenciát ad vissza az objektumra, amely a belső kivételt reprezentálja. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | A hibaleírást tartalmazó karakterláncot ad vissza. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | A stack trace-et tartalmazó karakterláncot ad vissza. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Az legbelsőbb kivételt reprezentáló Exception objektum másolatát ad vissza. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Megkapja az objektumhoz kapcsolódó referenciarámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | A C# [Object.GetHashCode()](../object/gethashcode/) metódus analógja. Engedélyezi egyedi objektumok hash-elését. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../object/gettype/) hívás analógja. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrzőobjektumot. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódus analógja. Engedélyezi egyedi típusok klónozását. |
|  [Object](../object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak inicializál egy új objektumot, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak inicializál egy új objektumot, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referencia összehasonlítás értéktípusú objektum és nullptr között. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciarámlálót a megadott értékkel. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Beállítja a HRESULT-et, egy kódolt numerikus értéket, amely egy adott kivételhez van rendelve. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá állítja (nem megosztott). Lehetővé teszi a mutatók tárolókban való weak módra váltását. |
| int [SharedCount](../object/sharedcount/)() const | Lekéri a megosztott referenciarámláló aktuális értékét. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott referenciarámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciarámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Visszaadja a jelenlegi objektum string reprezentációját. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Növeli a gyenge referenciarámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Csökkenti a gyenge referenciarámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual const char * [what](../details_exception/what/)() const | Megvalósítja a [what()](../details_exception/what/) metódust, amelyet a [ExceptionWrapper](../exceptionwrapper/) osztály hív. Annak ellenére, hogy ez az osztály nem örököl a std::exception osztályból, a leszármazottak védett/privát tagokat használhatnak logikájuk megvalósításához. Ennek a metódusnak a [ExceptionWrapper](../exceptionwrapper/)-ba áthelyezése megtörheti azt a logikát. |
| virtual  [~Object](../object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Details_Exception](../details_exception/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)