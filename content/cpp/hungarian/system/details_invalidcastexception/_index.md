---
title: Details_InvalidCastException
second_title: Aspose.Slides for C++ API Referencia
description: "Az InvalidCastException akkor dobódik, amikor érvénytelen átalakítási műveletet próbálnak végrehajtani érvénytelen explicit konverzió esetén. Soha ne hozzon létre példányt ebből az osztályból kézzel. Használja helyette az InvalidCastException osztályt. Soha ne csomagolja az InvalidCastException osztály példányait a System::SmartPtr-ba."
type: docs
weight: 495
url: /hu/system/details_invalidcastexception/
---
## Details_InvalidCastException osztály

InvalidCastException akkor dobódik, amikor érvénytelen alakváltoztatási műveletet próbálnak végrehajtani. Soha ne hozza létre ennek az osztálynak a példányait kézzel. Használja az InvalidCastException osztályt helyette. Soha ne csomagolja az InvalidCastException osztály példányait [System::SmartPtr](../smartptr/)-ba.

```cpp
class Details_InvalidCastException : public System::Details_SystemException
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az érték típusú objektumokat C# stílusban. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Visszaad egy szótárat egyedi kivételadatokkal. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Visszaad egy 32 bites egész értéket, amely egy HRESULT kód, a jelenlegi objektum által képviselt kivételhez társítva. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Visszaad egy hivatkozást az objektumra, amely a belső kivételt képviseli. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Visszaad egy karakterláncot, amely a hiba leírását tartalmazza. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Visszaad egy karakterláncot, amely a veremnyomot tartalmazza. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Visszaad az Exception objektum másolatát, amely a legbelső kivételt képviseli. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Lekéri a referenciacsámláló adatstruktúrát, amely az objektumhoz kapcsolódik. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | A C# [Object.GetHashCode()](../object/gethashcode/) metódus analógja. Lehetővé teszi az egyéni objektumok hash-elését. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../object/gettype/) hívás analógja. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Megvalósítja a C# lock() utasítást zárolásra. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrző objektumot. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az érték típusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Beállítja a HRESULT-et, egy kódolt numerikus értéket, amely egy konkrét kivételhez van rendelve. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett) állítja. Lehetővé teszi a mutatók tárolókban való gyenge módra való átkapcsolását. |
| int [SharedCount](../object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Visszaadja a jelenlegi objektum karakterlánc reprezentációját. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Megvalósítja a C# lock() utasítást feloldásra. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual const char * [what](../details_exception/what/)() const | Megvalósítja a [what()](../details_exception/what/) metódust, amelyet a [ExceptionWrapper](../exceptionwrapper/) osztály hív. Annak ellenére, hogy ez az osztály nem örököl a std::exception osztályból, az örökölt osztályok a védett/privát tagokat használhatják saját logikájuk megvalósításához. Ennek a metódusnak a [ExceptionWrapper](../exceptionwrapper/)-ba való áthelyezése megsértheti azt a logikát. |
| virtual  [~Object](../object/~object/)() | Lerombolja az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Details_SystemException](../details_systemexception/)
* Névtere [System](../)
* Könyvtár [Aspose.Slides](../../)