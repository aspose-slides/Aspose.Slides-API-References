---
title: Details_FormatException
second_title: Aspose.Slides for C++ API hivatkozás
description: "A FormatException akkor dobódik, amikor a metódus argumentumának formátuma nem érvényes. Soha ne hozza létre ennek az osztálynak a példányait kézzel. Használja helyette a FormatException osztályt. Soha ne csomagolja be a FormatException osztály példányait a System::SmartPtr-be."
type: docs
weight: 469
url: /hu/system/details_formatexception/
---
## Details_FormatException osztály


A FormatException akkor dobódik, amikor a metódus argumentumának formátuma nem érvényes. Soha ne hozza létre ennek az osztálynak a példányait kézzel. Használja inkább a FormatException osztályt. Soha ne csomagolja be a FormatException osztály példányait a [System::SmartPtr](../smartptr/)-ba.

```cpp
class Details_FormatException : public System::Details_SystemException
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Az objektumokat a C# [Object.Equals](../object/equals/) szintaxis szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Szótárat ad vissza egyedi kivétel adatokkal. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | 32 bites egész értéket ad vissza, amely a jelenlegi objektum által képviselt kivételhez kapcsolódó HRESULT kód. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Referenciát ad vissza az objektumra, amely a belső kivételt reprezentálja. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | A hibaleírást tartalmazó karakterláncot ad vissza. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | A veremnyomot tartalmazó karakterláncot ad vissza. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Az legbelső kivételt reprezentáló Exception objektum másolatát adja vissza. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Referenciaszámláló adatstruktúrát kér le, amely az objektumhoz kapcsolódik. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | A C# [Object.GetHashCode()](../object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../object/gettype/) hívás analógja. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) figyelő objektumot. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstruktorát. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Értékadó operátor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstruktorát. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot nullptr-re hivatkozással hasonlít össze. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Beállítja a HRESULT-et, egy kódolt numerikus értéket, amely egy adott kivételhez van rendelve. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóvá (nem megosztottá) állítja. Lehetővé teszi a mutatók átkapcsolását a konténerekben gyenge módba. |
| int [SharedCount](../object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem kell közvetlenül hívni; helyette okos mutatókat vagy ThisProtector-t használjon. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem kell közvetlenül hívni; helyette okos mutatókat vagy ThisProtector-t használjon. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | A jelenlegi objektum karakterlánc reprezentációját adja vissza. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) figyelő objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem kell közvetlenül hívni; helyette okos mutatókat vagy ThisProtector-t használjon. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem kell közvetlenül hívni; helyette okos mutatókat vagy ThisProtector-t használjon. |
| virtual const char * [what](../details_exception/what/)() const | Megvalósítja a [what()](../details_exception/what/) metódust, amelyet a [ExceptionWrapper](../exceptionwrapper/) osztály hív. Annak ellenére, hogy ez az osztály nem öröklődik a std::exception osztályból, a származtatott osztályok a védett/privát tagjait felhasználhatják saját logikájuk megvalósításához. Ennek a metódusnak a [ExceptionWrapper](../exceptionwrapper/)-be való áthelyezése megtörheti azt a logikát. |
| virtual  [~Object](../object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Details_SystemException](../details_systemexception/)
* Névtere [System](../)
* Könyvtár [Aspose.Slides](../../)