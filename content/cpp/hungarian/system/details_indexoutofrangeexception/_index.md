---
title: Details_IndexOutOfRangeException
second_title: Aspose.Slides C++ API hivatkozás
description: "Az IndexOutOfRangeException akkor kerül dobásra, amikor egy gyűjtemény eleméhez való hozzáférés egy olyan index használatával történik, amely kívül esik a határain. Soha ne hozd létre ennek az osztálynak a példányait manuálisan. Használd helyette az IndexOutOfRangeException osztályt. Soha ne csomagold be az IndexOutOfRangeException osztály példányait a System::SmartPtr-be."
type: docs
weight: 482
url: /hu/system/details_indexoutofrangeexception/
---
## Details_IndexOutOfRangeException osztály


IndexOutOfRangeException akkor kerül kivételként dobásra, amikor egy gyűjtemény eleméhez való hozzáférés egy olyan index használatával történik, amely kívül esik a határain. Soha ne hozd létre ennek az osztálynak az példányait manuálisan. Használd az IndexOutOfRangeException osztályt helyette. Soha ne csomagold be az IndexOutOfRangeException osztály példányait a [System::SmartPtr](../smartptr/)-be.

```cpp
class Details_IndexOutOfRangeException : public System::Details_SystemException
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | A C#-stílusú lebegőpontos összehasonlítást emulálja, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | A C#-stílusú lebegőpontos összehasonlítást emulálja, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Szótárat ad vissza egyedi kivételadatokkal. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | 32 bites egész értéket ad vissza, amely a jelen objektum által reprezentált kivételhez tartozó HRESULT kód. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Referenciát ad vissza a belső kivételt reprezentáló objektumra. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | A hibaleírást tartalmazó karakterláncot ad vissza. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | A veremnyomkövetést tartalmazó karakterláncot ad vissza. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | A legbelsőbb kivételt reprezentáló Exception objektum másolatát adja vissza. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Az objektumhoz társított referenciaszámláló adatstruktúrát adja vissza. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | A C# [Object.GetHashCode()](../object/gethashcode/) metódus analogja. Lehetővé teszi egyedi objektumok hash-elését. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../object/gettype/) hívás analogja. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | A C# lock() utasítás zárolását valósítja meg. Hívd közvetlenül vagy használd a [LockContext](../lockcontext/) védőobjektumot. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódus analogja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot hasonlít össze nullptr-val referencia szerint. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | A megosztott referencia számlálót a megadott értékkel csökkenti. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Beállítja a HRESULT-et, egy kódolt numerikus értéket, amely egy adott kivételhez van rendelve. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonparamétert gyenge mutatóval (nem megosztott) állítja be. Lehetővé teszi a mutatók átkapcsolását konténerekben gyenge módra. |
| int [SharedCount](../object/sharedcount/)() const | A megosztott referencia számláló jelenlegi értékét adja vissza. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; használj okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; használj okos mutatókat vagy ThisProtector-t. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Az aktuális objektum karakterlánc ábrázolását adja vissza. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | A C# lock() utasítás feloldását valósítja meg. Hívd közvetlenül vagy használd a [LockContext](../lockcontext/) védőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Gyenge referencia számlálót növel. Nem szabad közvetlenül hívni; használj okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Gyenge referencia számlálót csökkent. Nem szabad közvetlenül hívni; használj okos mutatókat vagy ThisProtector-t. |
| virtual const char * [what](../details_exception/what/)() const | Implementálja a [what()](../details_exception/what/) metódust, amelyet a [ExceptionWrapper](../exceptionwrapper/) osztály hív meg. Annak ellenére, hogy ez az osztály nem örököl a std::exception-ból, a leszármazottak védett/privát tagokat használhatnak a logikájuk megvalósításához. Ennek a metódusnak a [ExceptionWrapper](../exceptionwrapper/)-be való áthelyezése megtörheti azt a logikát. |
| virtual  [~Object](../object/~object/)() | Az objektumot megsemmisíti. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Details_SystemException](../details_systemexception/)
* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)