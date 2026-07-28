---
title: Details_OverflowException
second_title: Aspose.Slides a C++ API Referencia
description: "Az OverflowException akkor kerül dobásra, amikor egy művelet túlcsordulást eredményez. Soha ne hozza létre ennek az osztálynak a példányait manuálisan. Használja helyette az OverflowException osztályt. Soha ne csomagolja be az OverflowException osztály példányait a System::SmartPtr-ba."
type: docs
weight: 651
url: /hu/system/details_overflowexception/
---
## Details_OverflowException osztály


OverflowException akkor kerül dobásra, amikor egy művelet túlcsordulást eredményez. Soha ne hozza létre ennek az osztálynak a példányait manuálisan. Használja helyette az OverflowException osztályt. Soha ne csomagolja be az OverflowException osztály példányait a [System::SmartPtr](../smartptr/)-ba.

```cpp
class Details_OverflowException : public System::Details_ArithmeticException
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Az objektumokat C# [Object.Equals](../object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | A C#-stílusú lebegőpontos összehasonlítást emulálja, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | A C#-stílusú lebegőpontos összehasonlítást emulálja, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Egy szótárat ad vissza egyéni kivételadatokkal. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | 32 bites egész értéket ad vissza, amely egy HRESULT kód, ami a jelenlegi objektum által képviselt kivételhez kapcsolódik. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Referenciát ad vissza az objektumra, amely a belső kivételt reprezentálja. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | A hibaleírást tartalmazó karakterláncot ad vissza. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | A veremnyomot tartalmazó karakterláncot ad vissza. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Visszaadja a legbelső kivételt reprezentáló Exception objektum másolatát. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát adja vissza. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | A C# [Object.GetHashCode()](../object/gethashcode/) metódus analógja. Lehetővé teszi egyéni objektumok hash-elését. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../object/gettype/) hívás analógja. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrző objektumot. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja az értéktípusú objektumot a nullptr-el. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Beállítja a HRESULT-t, egy kódolt numerikus értéket, amely egy adott kivételhez van rendelve. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonparamétert gyenge mutatóként (a megosztott helyett) állítja be. Lehetővé teszi a mutatók konténerekben weak módra váltását. |
| int [SharedCount](../object/sharedcount/)() const | A megosztott referenciaszámláló aktuális értékét adja vissza. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Visszaadja a jelenlegi objektum karakterlánc ábrázolását. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual const char * [what](../details_exception/what/)() const | Megvalósítja a [what()](../details_exception/what/) metódust, amelyet a [ExceptionWrapper](../exceptionwrapper/) osztály hív. Annak ellenére, hogy ez az osztály nem öröklődik a std::exception-ból, az ebből származtatott osztályok védett/privát tagokat használhatnak a logikájuk megvalósításához. Ennek a metódusnak a [ExceptionWrapper](../exceptionwrapper/)-be történő áthelyezése megtörheti azt a logikát. |
| virtual  [~Object](../object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Details_ArithmeticException](../details_arithmeticexception/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)