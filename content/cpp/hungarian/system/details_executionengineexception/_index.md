---
title: Details_ExecutionEngineException
second_title: Aspose.Slides C++ API hivatkozás
description: Az ExecutionEngineException csak kompatibilitási okokból van jelen.
type: docs
weight: 456
url: /hu/system/details_executionengineexception/
---
## Details_ExecutionEngineException osztály


Az ExecutionEngineException csak kompatibilitási okokból van jelen.

```cpp
class Details_ExecutionEngineException : public System::Details_SystemException
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Szótárat ad vissza egyedi kivétel adatokkal. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | 32 bites egész értéket ad vissza, amely a jelen objektum által képviselt kivételhez társított HRESULT kód. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Referenciát ad vissza az objektumra, amely a belső kivételt képviseli. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Visszaadja a hibaleírást tartalmazó karakterláncot. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Visszaadja a veremnyomot tartalmazó karakterláncot. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Visszaadja a legbelső kivételt képviselő Exception objektum másolatát. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Megkapja az objektumhoz társított hivatkozásszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | A C# [Object.GetHashCode()](../object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Megkapja az objektum valós típusát. A C# [System.Object.GetType()](../object/gettype/) hívás analógja. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrző objektumot. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktálását. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktálását. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja össze az értéktípusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Csökkenti a megosztott hivatkozásszámot a megadott értékkel. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Beállítja a HRESULT-et, egy kódolt numerikus értéket, amely egy adott kivételhez van rendelve. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablon argumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a konténerekben a mutatók gyenge módba váltását. |
| int [SharedCount](../object/sharedcount/)() const | Lekéri a megosztott hivatkozásszámláló aktuális értékét. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott hivatkozásszámot. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott hivatkozásszámot. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Visszaadja a jelen objektum karakterlánc ábrázolását. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Növeli a gyenge hivatkozásszámot. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Csökkenti a gyenge hivatkozásszámot. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual const char * [what](../details_exception/what/)() const | Megvalósítja a [what()](../details_exception/what/) metódust, amelyet a [ExceptionWrapper](../exceptionwrapper/) osztály hív. Annak ellenére, hogy ez az osztály nem örököl a std::exception osztályból, a származtatott osztályok használhatják a védett/privát tagokat a logika megvalósításához. Ennek a metódusnak a [ExceptionWrapper](../exceptionwrapper/)-ba való áthelyezése megbontja ezt a logikát. |
| virtual  [~Object](../object/~object/)() | Megsemmísíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Lásd még

* Osztály [Details_SystemException](../details_systemexception/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)