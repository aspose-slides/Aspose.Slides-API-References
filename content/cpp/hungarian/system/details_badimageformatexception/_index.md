---
title: Details_BadImageFormatException
second_title: Aspose.Slides C++ API referencia
description: "Kivétel, amelyet akkor dobunk, amikor egy dinamikus linkkönyvtár (DLL) vagy egy végrehajtható program fájlképe érvénytelen. Soha ne hozzon létre példányokat ebből az osztályból manuálisan. Használja helyette a BadImageFormatException osztályt. Soha ne csomagolja a BadImageFormatException osztály példányait a System::SmartPtr-be."
type: docs
weight: 378
url: /hu/system/details_badimageformatexception/
---
## Details_BadImageFormatException osztály


A kivétel, amelyet akkor dobunk, amikor egy dinamikus linkkönyvtár (DLL) vagy egy végrehajtható program fájl képe érvénytelen. Soha ne hozzon létre példányokat ebből az osztályból manuálisan. Használja a BadImageFormatException osztályt helyette. Soha ne csomagolja a BadImageFormatException osztály példányait a [System::SmartPtr](../smartptr/)-ba.

```cpp
class Details_BadImageFormatException : public System::Details_ExceptionWithFilename<Details_SystemException>
```

## Módszerek

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Szótárat ad vissza egyéni kivételadatokkal. |
| virtual [String](../string/) [get_FileName](../details_exceptionwithfilename/get_filename/)() const | Lekéri a fájl nevét, amely ezt a kivételt okozza. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | 32-bites egész értéket ad vissza, amely egy HRESULT kód, a jelenlegi objektum által képviselt kivételhez társítva. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Referenciát ad vissza az objektumra, amely a belső kivételt képviseli. |
| [String](../string/) [get_Message](../details_exceptionwithfilename/get_message/)() const override |  |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Visszaadja a veremnyomot tartalmazó karakterláncot. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Visszaadja az Exception objektum másolatát, amely a legbelső kivételt képviseli. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Lekéri a objektummal társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | A C# [Object.GetHashCode()](../object/gethashcode/) metódus analógiája. Lehetővé teszi egyéni objektumok hash-elését. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](../details_systemexception/gettype/)() const override | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../object/gettype/) hívás analógiája. |
| **bool** [Is](../details_systemexception/is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) sentinel objektumot. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstruktálását. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Hozzárendelési operátor. Valójában semmit nem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstruktálását. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referencia összehasonlítás érték típusú objektum és nullptr között. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Beállítja a HRESULT-et, egy kódolt numerikus értéket, amely egy adott kivételhez van rendelve. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóra (nem megosztott) állítja. Lehetővé teszi a mutatók átváltását gyenge módra a tárolókban. |
| int [SharedCount](../object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtectort. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtectort. |
| [String](../string/) [ToString](../details_exceptionwithfilename/tostring/)() const override |  |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../details_systemexception/type/)() |  |
| void [Unlock](../object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtectort. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtectort. |
| virtual const char * [what](../details_exception/what/)() const | [what()](../details_exception/what/) metódust valósítja meg, amelyet a [ExceptionWrapper](../exceptionwrapper/) osztály hív. Annak ellenére, hogy ez az osztály nem örököl a std::exception osztályból, a leszármazottak védett/privát tagokat használhatnak a logika megvalósításához. Ennek a metódusnak a [ExceptionWrapper](../exceptionwrapper/)-ba való áthelyezése megtörheti azt a logikát. |
| virtual  [~Object](../object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Details_ExceptionWithFilename](../details_exceptionwithfilename/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)