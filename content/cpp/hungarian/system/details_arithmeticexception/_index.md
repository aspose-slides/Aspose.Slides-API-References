---
title: Details_ArithmeticException
second_title: Aspose.Slides C++ API Referencia
description: "Az ArithmeticException akkor kerül dobásra, amikor hiba lép fel az aritmetikai műveletek vagy az átalakítási (casting) műveletek végrehajtása során. Soha ne hozzon létre példányokat ebből az osztályból manuálisan. Használja helyette az ArithmeticException osztályt. Soha ne csomagolja be az ArithmeticException osztály példányait a System::SmartPtr-be."
type: docs
weight: 365
url: /hu/system/details_arithmeticexception/
---
## Details_ArithmeticException osztály

Az ArithmeticException akkor dobásra kerül, amikor hiba lép fel az aritmetikai műveletek vagy az átalakítási (casting) műveletek végrehajtása során. Soha ne hozzon létre példányokat ebből az osztályból manuálisan. Használja helyette az ArithmeticException osztályt. Soha ne csomagolja be az ArithmeticException osztály példányait a [System::SmartPtr](../smartptr/)-be.

```cpp
class Details_ArithmeticException : public System::Details_SystemException
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../object/equals/) szemantikai szabályai szerint. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az érték típusú objektumokat C# stílusban. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Visszaad egy szótárat egyéni kivételadatokkal. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Visszaad egy 32 bites egész értéket, amely egy HRESULT kód, amely a jelenlegi objektum által képviselt kivétellel kapcsolatos. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Visszaad egy referenciát az belső kivételt reprezentáló objektumra. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Visszaadja a hibaleírást tartalmazó karakterláncot. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Visszaadja a veremnyomot tartalmazó karakterláncot. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Visszaadja az Exception objektum másolatát, amely a legbelső kivételt reprezentálja. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Lekéri a referencia számláló adatstruktúrát, amely az objektumhoz kapcsolódik. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | A C# [Object.GetHashCode()](../object/gethashcode/) metódus analógja. Lehetővé teszi egyéni objektumok hash-elését. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../object/gettype/) hívás analógja. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Megvalósítja a C# lock() utasítást. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrző objektumot. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Értékadási operátor. Valójában semmit sem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) speciális változata karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) speciális változata karakterláncok esetére. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Beállítja a HRESULT-et, egy kódolt numerikus értéket, amely egy adott kivételhez van rendelve. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóvá (ahelyett, hogy megosztott) állítja be. Lehetővé teszi a mutatók konténerben való gyenge módba váltását. |
| int [SharedCount](../object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Visszaadja a jelenlegi objektum karakterlánc ábrázolását. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual const char * [what](../details_exception/what/)() const | [what()](../details_exception/what/) metódust valósítja meg, amelyet a [ExceptionWrapper](../exceptionwrapper/) osztály hív. Anélkül, hogy ez az osztály öröklődne a std::exception osztályból, a származtatott osztályok védett/privát tagokat használhatnak logikájuk megvalósításához. Ennek a metódusnak a [ExceptionWrapper](../exceptionwrapper/)-be áthelyezése eltörheti azt a logikát. |
| virtual  [~Object](../object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Details_SystemException](../details_systemexception/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)