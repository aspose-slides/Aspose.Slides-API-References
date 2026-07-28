---
title: DirectoryInfo
second_title: Aspose.Slides C++ API referencia
description: "Képviseli a fájlrendszer egy útvonalát, a ezen az útvonalon hivatkozott könyvtárat, és példánymetódusokat biztosít a könyvtárak manipulálásához. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek."
type: docs
weight: 248
url: /hu/system.io/directoryinfo/
---
## DirectoryInfo osztály

Képviseli a fájlrendszer útvonalát, a ezen az útvonalon hivatkozott könyvtárat, és példánymetódusokat biztosít a könyvtárak manipulálásához. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az new operátor használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) pointerbe, és használja ezt a pointert, hogy argumentumként átadja a függvényeknek.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [Create](./create/)() | Létrehoz egy könyvtárat az aktuális objektum által képviselt útvonalon. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [CreateSubdirectory](./createsubdirectory/)(const [String](../../system/string/)\&) | Létrehozza az almappákat a megadott útvonalon. |
| void [Delete](./delete/)() override | Eltávolítja a könyvtárat, amelyre az aktuális objektum által képviselt útvonal hivatkozik, ha a könyvtár üres. |
| void [Delete](./delete/)(**bool**) | Eltávolítja a könyvtárat, amelyre az aktuális objektum által képviselt útvonal hivatkozik. A paraméter megadja, hogy a könyvtár tartalma rekurzívan legyen-e eltávolítva, ha a könyvtár nem üres. |
|  [DirectoryInfo](./directoryinfo/)(const [String](../../system/string/)\&) | Létrehoz egy példányt a [DirectoryInfo](./) osztályból a megadott útvonalon. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)() | Visszaad egy felsorolható gyűjteményt, amely tartalmazza az aktuális objektum által képviselt könyvtárban található összes könyvtárat. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&) | Keres a könyvtárak között, amelyek megfelelnek a megadott keresési feltételeknek az aktuális objektum által képviselt könyvtárban. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Keres a könyvtárak között, amelyek megfelelnek a megadott keresési feltételeknek vagy az aktuális objektum által képviselt könyvtárban, vagy az azt gyökérnek tekintő teljes könyvtár fastruktúrában. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)() | Visszaad egy felsorolható gyűjteményt, amely tartalmazza az aktuális objektum által képviselt könyvtárban található összes fájlt. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&) | Keres a fájlok között, amelyek megfelelnek a megadott keresési feltételeknek az aktuális objektum által képviselt könyvtárban. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Keres a fájlok között, amelyek megfelelnek a megadott keresési feltételeknek vagy az aktuális objektum által képviselt könyvtárban, vagy az azt gyökérnek tekintő teljes könyvtár fastruktúrában. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | Visszaad egy felsorolható gyűjteményt, amely tartalmazza az aktuális objektum által képviselt könyvtárban található összes fájlt és könyvtárat. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&) | Keres a fájlok és könyvtárak között, amelyek megfelelnek a megadott keresési feltételeknek az aktuális objektum által képviselt könyvtárban. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Keres a fájlok és könyvtárak között, amelyek megfelelnek a megadott keresési feltételeknek vagy az aktuális objektum által képviselt könyvtárban, vagy az azt gyökérnek tekintő teljes könyvtár fastruktúrában. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Nem csinál semmit. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Visszaadja az aktuális objektum által képviselt entitás attribútumait. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Visszaadja az aktuális objektum által képviselt entitás létrehozási időpontját helyi időben. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Visszaadja az aktuális objektum által képviselt entitás létrehozási időpontját UTC időben. |
| **bool** [get_Exists](./get_exists/)() override | Megállapítja, hogy az aktuális objektum által képviselt útvonal egy létező könyvtárra mutat-e. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Visszaadja az aktuális objektum által képviselt fájl kiterjesztését. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Visszaadja az aktuális objektum által képviselt entitás teljes nevét (beleértve az útvonalat is). |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Visszaadja az aktuális objektum által képviselt entitás legutóbbi hozzáférési időpontját helyi időben. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Visszaadja az aktuális objektum által képviselt entitás legutóbbi hozzáférési időpontját UTC időben. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Visszaadja az aktuális objektum által képviselt entitás legutóbbi írási időpontját helyi időben. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Visszaadja az aktuális objektum által képviselt entitás legutóbbi írási időpontját UTC időben. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Visszaadja az aktuális objektum által képviselt útvonal által hivatkozott entitás nevét. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Parent](./get_parent/)() | Visszaad egy megosztott mutatót egy [DirectoryInfo](./) objektumra, amely egy olyan útvonalat képvisel, amely a jelenlegi objektum által képviselt könyvtár szülőkönyvtárára mutat. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Root](./get_root/)() | Visszaad egy megosztott mutatót egy [DirectoryInfo](./) objektumra, amely egy olyan útvonalat képvisel, amely a jelenlegi objektum által képviselt könyvtár gyökérkönyvtárára mutat. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)() | Visszaad egy tömböt, amely megosztott mutatókat tartalmaz [DirectoryInfo](./) objektumokra, amelyek az aktuális objektum által képviselt könyvtárban található összes könyvtárat képviselik. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&) | Keres a könyvtárak között, amelyek megfelelnek a megadott keresési feltételeknek az aktuális objektum által képviselt könyvtárban. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Keres a könyvtárak között, amelyek megfelelnek a megadott keresési feltételeknek vagy az aktuális objektum által képviselt könyvtárban, vagy az azt gyökérnek tekintő teljes könyvtár fastruktúrában. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)() | Visszaad egy tömböt, amely megosztott mutatókat tartalmaz [FileInfo](../fileinfo/) objektumokra, amelyek az aktuális objektum által képviselt könyvtárban található összes könyvtárat képviselik. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&) | Keres a fájlok között, amelyek megfelelnek a megadott keresési feltételeknek az aktuális objektum által képviselt könyvtárban. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Keres a fájlok között, amelyek megfelelnek a megadott keresési feltételeknek vagy az aktuális objektum által képviselt könyvtárban, vagy az azt gyökérnek tekintő teljes könyvtár fastruktúrában. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)() | Visszaad egy tömböt, amely megosztott mutatókat tartalmaz [FileSystemInfo](../filesysteminfo/) objektumokra, amelyek az aktuális objektum által képviselt könyvtárban található összes fájlt és könyvtárat képviselik. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&) | Keres a fájlok és könyvtárak között, amelyek megfelelnek a megadott keresési feltételeknek az aktuális objektum által képviselt könyvtárban. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Keres a fájlok és könyvtárak között, amelyek megfelelnek a megadott keresési feltételeknek vagy az aktuális objektum által képviselt könyvtárban, vagy az azt gyökérnek tekintő teljes könyvtár fastruktúrában. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi a saját objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Áthelyezi az aktuális objektum által képviselt könyvtárat és annak teljes tartalmát a megadott helyre. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata stringek esetére. |
| void [Refresh](../filesysteminfo/refresh/)() | Frissíti az aktuális objektum állapotát. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Beállítja a megadott attribútumokat az aktuális objektum által képviselt entitáson. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás létrehozási időpontját helyi időben. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás létrehozási időpontját UTC időben. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás legutóbbi hozzáférési időpontját helyi időben. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás legutóbbi hozzáférési időpontját UTC időben. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás legutóbbi írási időpontját helyi időben. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás legutóbbi írási időpontját UTC időben. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók átváltását gyengére a konténerekben. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Visszaad egy karakterláncot, amely tartalmazza az aktuális objektum által képviselt útvonalat. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [FileSystemInfo](../filesysteminfo/)
* Névterület [System::IO](../)
* Könyvtár [Aspose.Slides](../../)