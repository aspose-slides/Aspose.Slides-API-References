---
title: Details_NotSupportedException
second_title: Aspose.Slides for C++ API-referencia
description: "A NotSupportedException akkor dobódik, amikor a meghívott metódus nem támogatott, vagy amikor egy stream-en végrehajtott művelet nem támogatott. Soha ne hozzon létre példányokat ebből az osztályból manuálisan. Használja helyette a NotSupportedException osztályt. Soha ne csomagolja a NotSupportedException osztály példányait a System::SmartPtr-be."
type: docs
weight: 586
url: /hu/system/details_notsupportedexception/
---
## Details_NotSupportedException osztály

NotSupportedException akkor dobódik, amikor egy meghívott metódus nem támogatott, vagy amikor egy stream-en végrehajtott művelet nem támogatott. Soha ne hozzon létre példányokat ebből az osztályból manuálisan. Használja helyette a NotSupportedException osztályt. Soha ne csomagolja a NotSupportedException osztály példányait a [System::SmartPtr](../smartptr/)-be.

```cpp
class Details_NotSupportedException : public System::Details_SystemException
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Visszaad egy szótárt egyedi kivételadatokkal. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Visszaad egy 32 bites egész értéket, amely a jelenlegi objektum által képviselt kivételhez kapcsolódó HRESULT kód. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Visszaad egy hivatkozást az objektumra, amely a belső kivételt képviseli. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Visszaadja a hibaleírást tartalmazó karakterláncot. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Visszaadja a veremkövetést tartalmazó karakterláncot. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Visszaadja a legbelső kivételt képviselő Exception objektum másolatát. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Lekéri az objektumhoz tartozó referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | A C# [Object.GetHashCode()](../object/gethashcode/) metódus analógja. Engedélyezi egyedi objektumok hash-elését. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Lekéri az objektum valós típusát. A C# [System.Object.GetType()](../object/gettype/) hívás analógja. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrzőobjektumot. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódus analógja. Engedélyezi egyedi típusok klónozását. |
|  [Object](../object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Objektumokat hivatkozás szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-összehasonlítás értéktípusú objektumok és nullptr között. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Beállítja a HRESULT-et, egy kódolt numerikus értéket, amelyet egy adott kivételhez rendelnek. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóként állítja be (a megosztott helyett). Lehetővé teszi a mutatók konténerekben weak módra váltását. |
| int [SharedCount](../object/sharedcount/)() const | Lekéri a megosztott referencia számláló jelenlegi értékét. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Visszaadja a jelenlegi objektum karakterlánc ábrázolását. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual const char * [what](../details_exception/what/)() const | Megvalósítja a [what()](../details_exception/what/) metódust, amelyet a [ExceptionWrapper](../exceptionwrapper/) osztály hív meg. Annak ellenére, hogy ez az osztály nem örököl a std::exception osztályból, a származtatott osztályok használhatják a védett/privát tagokat a logikájuk megvalósításához. Ennek a metódusnak a [ExceptionWrapper](../exceptionwrapper/)-ba történő áthelyezése tönkreteheti azt a logikát. |
| virtual  [~Object](../object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Details_SystemException](../details_systemexception/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)