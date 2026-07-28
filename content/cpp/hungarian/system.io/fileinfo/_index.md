---
title: FileInfo
second_title: Aspose.Slides C++ API Referenciája
description: "Útvonalat képvisel egy fájlhoz, valamint a ezen az úton hivatkozott fájlt, és módszereket biztosít annak kezelésére. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mert ez futásidejű hibákat és/vagy assert hibákat okoz. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az objektum függvények argumentumaként történő átadásához."
type: docs
weight: 274
url: /hu/system.io/fileinfo/
---
## FileInfo osztály

Egy fájlra mutató útvonalat és az útvonal által hivatkozott fájlt képviseli, és módszereket biztosít annak kezelésére. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy assert hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az objektum függvények argumentumaként történő átadásához.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Módszerek

| Method | Leírás |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | Megnyit egy fájlt, amelyet az aktuális objektum képvisel, szövegíráshoz UTF-8 kódolással, 'Append' módban, megosztás nélkül. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | Az aktuális objektum által képviselt fájlt a megadott helyre másolja. Ha a célfájl már létezik, a másolás sikertelen. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | Az aktuális objektum által képviselt fájlt a megadott helyre másolja. Egy paraméter meghatározza, hogy a már létező célfájlt felül kell-e írni. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | Létrehozza a fájlt azon a helyen, amelyet az aktuális objektum által képviselt útvonal megad, és megnyitja olvasásra és írásra, truncálás módban, megosztás nélkül. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | Létrehozza a fájlt azon a helyen, amelyet az aktuális objektum által képviselt útvonal megad, és megnyitja szövegírásra UTF-8 kódolással, megosztás nélkül. |
| void [Decrypt](./decrypt/)() | NEM KIVITELEZETT. |
| void [Delete](./delete/)() override | Eltávolítja az aktuális objektum által képviselt fájlt. |
| void [Encrypt](./encrypt/)() | NEM KIVITELEZETT. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat C# [Object.Equals](../../system/object/equals/) szintaxis szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő bármely értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő bármely értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
|  [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | Létrehoz egy új példányt a [FileInfo](./) osztályból, amely a megadott fájlt képviseli. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Nem csinál semmit. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Visszaadja az aktuális objektum által képviselt entitás attribútumait. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Visszaadja az aktuális objektum által képviselt entitás létrehozási időpontját helyi időként. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Visszaadja az aktuális objektum által képviselt entitás létrehozási időpontját UTC időként. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | Visszaad egy [DirectoryInfo](../directoryinfo/) objektumot, amely egy könyvtárat képvisel, amelyben az aktuális objektum által képviselt fájl található. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | Visszaadja a könyvtár teljes nevét, amelyben az aktuális objektum által képviselt fájl található. |
| **bool** [get_Exists](./get_exists/)() override | Visszaad egy értéket, amely azt jelzi, hogy a fájl létezik-e. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Visszaadja a fájl kiterjesztését. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Visszaadja az aktuális objektum által képviselt entitás teljes nevét (beleértve az elérési utat is). |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Visszaad egy értéket, amely azt jelzi, hogy a ReadOnly attribútum be van-e állítva. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Visszaadja az aktuális objektum által képviselt entitás utolsó hozzáférési időpontját helyi időként. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Visszaadja az aktuális objektum által képviselt entitás utolsó hozzáférési időpontját UTC időként. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Visszaadja az aktuális objektum által képviselt entitás utolsó írási időpontját helyi időként. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Visszaadja az aktuális objektum által képviselt entitás utolsó írási időpontját UTC időként. |
| **int64_t** [get_Length](./get_length/)() | Visszaadja a fájl méretét bájtokban. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Visszaadja a fájl nevét. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri a objektumhoz társított hivatkozásszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum egy példány-e a targetType által leírt típusból. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Áthelyezi az aktuális objektum által képviselt fájlt a megadott helyre. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | Megnyitja az aktuális objektum által képviselt fájlt a megadott módban olvasásra és írásra, megosztás nélkül. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | Megnyitja az aktuális objektum által képviselt fájlt a megadott módban, a megadott hozzáférési típussal, megosztás nélkül. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Megnyitja az aktuális objektum által képviselt fájlt a megadott módban, a megadott hozzáférési típussal és megosztási beállítással. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | Megnyit egy fájlt, amelyet az aktuális objektum képvisel, csak olvasásra, 'Open' módban olvasási megosztással. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | Megnyitja a meglévő fájlt a helyen, amelyet az aktuális objektum által képviselt útvonal ad meg, szövegolvasásra UTF-8 kódolással, megosztás nélkül. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | Megnyit egy fájlt, amelyet az aktuális objektum képvisel, csak írásra, 'OpenOrCreate' módban, megosztás nélkül. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlít egy értéktípusú objektumot a nullptr-re. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| void [Refresh](../filesysteminfo/refresh/)() | Frissíti az aktuális objektum állapotát. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott hivatkozásszámot a megadott értékkel. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Lecseréli egy megadott célfájl tartalmát az aktuális [FileInfo](./) objektum által képviselt fájlra, és biztonsági másolatot készít a lecserélt fájlról. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Lecseréli egy megadott célfájl tartalmát az aktuális [FileInfo](./) objektum által képviselt fájlra, és biztonsági másolatot készít a lecserélt fájlról. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Beállítja a megadott attribútumokat az aktuális objektum által képviselt entitáson. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás létrehozási időpontját helyi időként. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás létrehozási időpontját UTC időként. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | Beállítja vagy törli a ReadOnly attribútumot a fájlon. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás utolsó hozzáférési időpontját helyi időként. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás utolsó hozzáférési időpontját UTC időként. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás utolsó írási időpontját helyi időként. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Beállítja az aktuális objektum által képviselt entitás utolsó írási időpontját UTC időként. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (nem megosztottra). Lehetővé teszi a mutatók kontejnerekben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott hivatkozásszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott hivatkozásszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott hivatkozásszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Visszaad egy útvonalat, amelyet az aktuális objektum képvisel. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstruktumot. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge hivatkozásszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge hivatkozásszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [FileSystemInfo](../filesysteminfo/)
* Névterület [System::IO](../)
* Könyvtár [Aspose.Slides](../../)