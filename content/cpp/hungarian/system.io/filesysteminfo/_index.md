---
title: FileSystemInfo
second_title: Aspose.Slides C++ API referencia
description: "Az alap osztály a FileInfo és DirectoryInfo számára. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mert futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként történő függvényhívásokhoz."
type: docs
weight: 300
url: /hu/system.io/filesysteminfo/
---
## FileSystemInfo osztály

Az alaposztály a [FileInfo](../fileinfo/) és [DirectoryInfo](../directoryinfo/) számára. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az objektum függvényeknek argumentumként történő átadásához.

```cpp
class FileSystemInfo : public System::Object
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual void [Delete](./delete/)() | Törli az aktuális objektum által képviselt entitást. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| virtual void [Finalize](./finalize/)() | Semmit sem csinál. |
| [FileAttributes](../fileattributes/) [get_Attributes](./get_attributes/)() | Visszaadja az aktuális objektum által képviselt entitás attribútumait. |
| [DateTime](../../system/datetime/) [get_CreationTime](./get_creationtime/)() | Visszaadja az aktuális objektum által képviselt entitás létrehozási idejét helyi időben. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](./get_creationtimeutc/)() | Visszaadja az aktuális objektum által képviselt entitás létrehozási idejét UTC időben. |
| virtual **bool** [get_Exists](./get_exists/)() | Megállapítja, hogy létezik-e a jelenlegi objektum által képviselt útvonal által hivatkozott entitás. |
| [String](../../system/string/) [get_Extension](./get_extension/)() | Visszaadja a jelenlegi objektum által képviselt fájl kiterjesztését. |
| virtual [String](../../system/string/) [get_FullName](./get_fullname/)() | Visszaadja a jelenlegi objektum által képviselt entitás teljes nevét (az úttal együtt). |
| [DateTime](../../system/datetime/) [get_LastAccessTime](./get_lastaccesstime/)() | Visszaadja az aktuális objektum által képviselt entitás legutóbbi elérési idejét helyi időben. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](./get_lastaccesstimeutc/)() | Visszaadja az aktuális objektum által képviselt entitás legutóbbi elérési idejét UTC időben. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](./get_lastwritetime/)() | Visszaadja az aktuális objektum által képviselt entitás legutóbbi írási idejét helyi időben. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](./get_lastwritetimeutc/)() | Visszaadja az aktuális objektum által képviselt entitás legutóbbi írási idejét UTC időben. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Visszaad egy nevet az aktuális objektum által képviselt entitáshoz. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot hasonlít össze referenciaként a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| void [Refresh](./refresh/)() | Frissíti az aktuális objektum állapotát. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Attributes](./set_attributes/)([FileAttributes](../fileattributes/)) | Beállítja a megadott attribútumokat az aktuális objektum által képviselt entitáson. |
| void [set_CreationTime](./set_creationtime/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás létrehozási idejét helyi időben. |
| void [set_CreationTimeUtc](./set_creationtimeutc/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás létrehozási idejét UTC időben. |
| void [set_LastAccessTime](./set_lastaccesstime/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás legutóbbi elérési idejét helyi időben. |
| void [set_LastAccessTimeUtc](./set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás legutóbbi elérési idejét UTC időben. |
| void [set_LastWriteTime](./set_lastwritetime/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás legutóbbi írási idejét helyi időben. |
| void [set_LastWriteTimeUtc](./set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás legutóbbi írási idejét UTC időben. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a tárolókban gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtere [System::IO](../)
* Könyvtár [Aspose.Slides](../../)