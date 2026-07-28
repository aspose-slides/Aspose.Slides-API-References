---
title: BlobManagementOptions
second_title: Aspose.Slides C++ API hivatkozás
description: Olyan beállításokat képvisel, amelyeket a BLOB kezelési szabályok és egyéb BLOB beállítások kezelésére lehet használni.
type: docs
weight: 196
url: /hu/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions osztály


A BLOB kezelési szabályok és egyéb BLOB beállítások kezelésére használható beállításokat képviseli.

```cpp
class BlobManagementOptions : public Aspose::Slides::IBlobManagementOptions
```

## Módszerek

| Method | Leírás |
| --- | --- |
|  [BlobManagementOptions](./blobmanagementoptions/)() | Létrehozza az új alapértelmezett blob kezelési beállításokat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika használatával hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN semelyik értékkel, így a NaN-nal sem egyenlő. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN semelyik értékkel, így a NaN-nal sem egyenlő. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() override | Ez a tulajdonság meghatározza, hogy a BLOB-ok használata során létrehozhatók-e ideiglenes fájlok, ami jelentősen csökkenti a memóriahasználatot, de fájlok létrehozásához jogosultságot igényel. |
| **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() override | Meghatározza a maximális teljes méretet (bájtban), amelyet az összes BLOB a memóriában elfoglalhat. Alapértelmezés szerint az összes BLOB a memóriába töltődik; csak a határ elérése után alkalmaznak alternatív mechanizmusokat (például ideiglenes fájlok). A BLOB-ok memóriában tartása maximalizálja a teljesítményt, de magas memóriahasználathoz vezethet. Használja ezt a tulajdonságot a viselkedés testreszabásához a környezet vagy követelmények szerint. |
| [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() override | Ez a tulajdonság meghatározza, hogy a [Presentation](../presentation/) osztály egy példánya lehet-e a forrás (fájl vagy adatfolyam) tulajdonosa az élettartama során. Ha a példány tulajdonos, zárolja a forrást. Ez segít csökkenteni a memóriahasználatot és javítja a teljesítményt a BLOB-ok használata közben, de a forrás (adatfolyam vagy fájl) nem módosítható a [Presentation](../presentation/) példányának élettartama alatt. |
| [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() override | A gyökérútvonal, ahol az ideiglenes fájlok létrejönnek. [System](../../system/) ideiglenes könyvtár lesz használva alapértelmezés szerint. A hosztoló folyamatnak rendelkeznie kell jogosultsággal fájlok és mappák létrehozásához ott. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot nullptr-vel hasonlít össze referenciaként. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) override | Ez a tulajdonság meghatározza, hogy a BLOB-ok használata során létrehozhatók-e ideiglenes fájlok, ami jelentősen csökkenti a memóriahasználatot, de fájlok létrehozásához jogosultságot igényel. |
| void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) override | Meghatározza a maximális teljes méretet (bájtban), amelyet az összes BLOB a memóriában elfoglalhat. Alapértelmezés szerint az összes BLOB a memóriába töltődik; csak a határ elérése után alkalmaznak alternatív mechanizmusokat (például ideiglenes fájlok). A BLOB-ok memóriában tartása maximalizálja a teljesítményt, de magas memóriahasználathoz vezethet. Használja ezt a tulajdonságot a viselkedés testreszabásához a környezet vagy követelmények szerint. |
| void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) override | Ez a tulajdonság meghatározza, hogy a [Presentation](../presentation/) osztály egy példánya lehet-e a forrás (fájl vagy adatfolyam) tulajdonosa az élettartama során. Ha a példány tulajdonos, zárolja a forrást. Ez segít csökkenteni a memóriahasználatot és javítja a teljesítményt a BLOB-ok használata közben, de a forrás (adatfolyam vagy fájl) nem módosítható a [Presentation](../presentation/) példányának élettartama alatt. |
| void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) override | A gyökérútvonal, ahol az ideiglenes fájlok létrejönnek. [System](../../system/) ideiglenes könyvtár lesz használva alapértelmezés szerint. A hosztoló folyamatnak rendelkeznie kell jogosultsággal fájlok és mappák létrehozásához ott. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóvá (nem megosztottá) állítja be. Lehetővé teszi a mutatók konténerekben való átváltását gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IBlobManagementOptions](../iblobmanagementoptions/)
* Névterület [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)