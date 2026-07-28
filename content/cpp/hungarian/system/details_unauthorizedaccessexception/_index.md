---
title: Details_UnauthorizedAccessException
second_title: Aspose.Slides C++ API Referencia
description: "Az UnauthorizedAccessException akkor kerül dobásra, amikor a hozzáférést az operációs rendszer megtagadja I/O hiba vagy biztonsági hiba miatt. Soha ne hozzon létre példányokat ebből az osztályból manuálisan. Használja helyette az UnauthorizedAccessException osztályt. Soha ne csomagolja be az UnauthorizedAccessException osztály példányait a System::SmartPtr-be."
type: docs
weight: 755
url: /hu/system/details_unauthorizedaccessexception/
---
## Details_UnauthorizedAccessException osztály


UnauthorizedAccessException is thrown when access is denied by the operating system because of an I/O error or a security error. Never create instances of this class manually. Use the UnauthorizedAccessException osztály instead. Never wrap the UnauthorizedAccessException osztály instances into [System::SmartPtr](../smartptr/).

```cpp
class Details_UnauthorizedAccessException : public System::Details_SystemException
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../object/equals/) szemantikája szerint. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Ugyanazt utánozza, mint a C#-stílusú lebegőpontos összehasonlítás, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Ugyanazt utánozza, mint a C#-stílusú lebegőpontos összehasonlítás, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Visszaad egy szótárat egyedi kivételadatokkal. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Visszaad egy 32 bites egész értéket, amely egy HRESULT kód, és a jelenlegi objektum által képviselt kivételhez kapcsolódik. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Visszaad egy referenciát az objektumra, amely a belső kivételt reprezentálja. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Visszaadja a hibaleírást tartalmazó karakterláncot. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Visszaadja a veremnyomot tartalmazó karakterláncot. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Visszaadja a legbelső kivételt reprezentáló Exception objektum másolatát. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Lekéri az objektummal kapcsolatos referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | A C# [Object.GetHashCode()](../object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../object/gettype/) hívás analógja. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívható közvetlenül vagy használhatod a [LockContext](../lockcontext/) őrző objektumot. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával összehasonlítja az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Beállítja a HRESULT-et, egy kódolt numerikus értéket, amely egy adott kivételhez van rendelve. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóként (nem megosztottként). Lehetővé teszi a mutatók konténerekben való weak módra váltását. |
| int [SharedCount](../object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette okos mutatókat vagy ThisProtector-t kell használni. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette okos mutatókat vagy ThisProtector-t kell használni. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Visszaadja a jelenlegi objektum karakterlánc reprezentációját. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívható közvetlenül vagy használhatod a [LockContext](../lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette okos mutatókat vagy ThisProtector-t kell használni. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette okos mutatókat vagy ThisProtector-t kell használni. |
| virtual const char * [what](../details_exception/what/)() const | Megvalósítja a [what()](../details_exception/what/) metódust, amelyet a [ExceptionWrapper](../exceptionwrapper/) osztály hív. Annak ellenére, hogy ez az osztály nem örököl a std::exception-ből, a származtatott osztályok védett/privát tagokat használhatnak a logika megvalósításához. Ennek a metódusnak a [ExceptionWrapper](../exceptionwrapper/)-ba való áthelyezése megtörheti azt a logikát. |
| virtual  [~Object](../object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Details_SystemException](../details_systemexception/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)