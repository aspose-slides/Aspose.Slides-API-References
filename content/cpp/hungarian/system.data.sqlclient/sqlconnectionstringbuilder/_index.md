---
title: SqlConnectionStringBuilder
second_title: Aspose.Slides C++ API referencia
description: "SQL-alapú kapcsolati építő. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és ezt a mutatót használja az objektumok függvényeknek argumentumként való átadásához."
type: docs
weight: 1
url: /hu/system.data.sqlclient/sqlconnectionstringbuilder/
---
## SqlConnectionStringBuilder osztály

SQL-alapú kapcsolati építő. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és ezt a mutatót használja az objektumok argumentumként való átadásához a függvényeknek.

```cpp
class SqlConnectionStringBuilder : public System::Data::Common::DbConnectionStringBuilder
```

## Methods

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az érték típusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual [String](../../system/string/) [get_ConnectionString](../../system.data.common/dbconnectionstringbuilder/get_connectionstring/)() const | Lekéri a teljes kapcsolati karakterláncot. |
| [String](../../system/string/) [get_DataSource](./get_datasource/)() const | Lekéri az adatforrást (pl. gazdagép név és port). |
| **bool** [get_Encrypt](./get_encrypt/)() const | Ellenőrzi, hogy a titkosítás engedélyezve van-e. |
| [String](../../system/string/) [get_InitialCatalog](./get_initialcatalog/)() const | Lekéri a kapcsolathoz tartozó adatbázis nevét. |
| [String](../../system/string/) [get_NetworkLibrary](./get_networklibrary/)() const | Lekéri a használt hálózati könyvtár nevét. |
| [String](../../system/string/) [get_Password](./get_password/)() const | Lekéri az adatbázishoz való kapcsolódáshoz használt jelszót. |
| **bool** [get_TrustServerCertificate](./get_trustservercertificate/)() const | Ellenőrzi, hogy a kapcsolat megbízható szerver tanúsítvánnyal védett-e. |
| [String](../../system/string/) [get_UserID](./get_userid/)() const | Lekéri a kapcsolathoz használt felhasználóazonosítót. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciak számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| [Object::ptr](../../system/object/ptr/) [idx_get](./idx_get/)([String](../../system/string/)) override | RTTI információ. |
| [Object::ptr](../../system/object/ptr/) [idx_set](./idx_set/)([String](../../system/string/), [Object::ptr](../../system/object/ptr/)) override | Beállít egy kulcsos objektumot. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Átruházó operátor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával összehasonlítja az érték típusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) speciális megvalósítása string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) speciális megvalósítása stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciak számát a megadott értékkel. |
| virtual void [set_ConnectionString](../../system.data.common/dbconnectionstringbuilder/set_connectionstring/)([String](../../system/string/)) | Beállítja a teljes kapcsolati karakterláncot. |
| void [set_DataSource](./set_datasource/)(const [String](../../system/string/)\&) | Lekéri az adatforrást (pl. gazdagép név és port). |
| void [set_Encrypt](./set_encrypt/)(**bool**) | Bekapcsolja vagy kikapcsolja a titkosítást. |
| void [set_InitialCatalog](./set_initialcatalog/)(const [String](../../system/string/)\&) | Beállítja a kapcsolathoz tartozó adatbázis nevét. |
| void [set_NetworkLibrary](./set_networklibrary/)(const [String](../../system/string/)\&) | Kiválasztja a használandó hálózati könyvtárat. |
| void [set_Password](./set_password/)(const [String](../../system/string/)\&) | Beállítja az adatbázishoz való csatlakozáshoz használt jelszót. |
| void [set_TrustServerCertificate](./set_trustservercertificate/)(**bool**) | Meghatározza, hogy a kapcsolat megbízható szerver tanúsítvánnyal védett-e. |
| void [set_UserID](./set_userid/)(const [String](../../system/string/)\&) | Beállítja a kapcsolathoz használandó felhasználóazonosítót. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóként állítja be (a shared helyett). Lehetővé teszi a tárolókban lévő mutatók weak módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciak számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciak számát. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciak számát. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciak számát. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciak számát. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [DbConnectionStringBuilder](../../system.data.common/dbconnectionstringbuilder/)
* Névtér [System::Data::SqlClient](../)
* Könyvtár [Aspose.Slides](../../)