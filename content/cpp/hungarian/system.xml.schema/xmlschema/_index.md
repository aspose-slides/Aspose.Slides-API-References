---
title: XmlSchema
second_title: Aspose.Slides C++ API Referencia
description: Memóriában tárolt reprezentációja egy XML sémának, ahogyan azt a World Wide Web Consortium (W3C) és .
type: docs
weight: 79
url: /hu/system.xml.schema/xmlschema/
---
## XmlSchema osztály

Az XML [Schema](../) memóriabeli reprezentációja, ahogy a World Wide [Web](../../system.web/) Consortium (W3C) [XML Schema Part 1: Structures](https://www.w3.org/TR/xmlschema-1/) és [XML Schema Part 2: Datatypes](https://www.w3.org/TR/xmlschema-2/) határozza meg.

```cpp
class XmlSchema : public System::Xml::Schema::XmlSchemaObject
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/)) | Lefordítja az XML [Schema](../)[Object](../../system/object/) Modellt (SOM) séma információvá az érvényesítéshez. A programozottan felépített SOM szintaktikai és szemantikai struktúrájának ellenőrzésére szolgál. A szemantikai érvényesítési ellenőrzés a fordítás során történik. |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/), const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | Lefordítja az XML [Schema](../)[Object](../../system/object/) Modellt (SOM) séma információvá az érvényesítéshez. A programozottan felépített SOM szintaktikai és szemantikai struktúrájának ellenőrzésére szolgál. A szemantikai érvényesítési ellenőrzés a fordítás során történik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| [XmlSchemaForm](../xmlschemaform/) [get_AttributeFormDefault](./get_attributeformdefault/)() | Visszaadja az attribútumok formáját, amely a séma célnevterében van deklarálva. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeGroups](./get_attributegroups/)() | Visszaadja a séma összes globális attribútumcsoportjának sémakompiláció utáni értékét. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Attributes](./get_attributes/)() | Visszaadja a séma összes attribútumának sémakompiláció utáni értékét. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockDefault](./get_blockdefault/)() | Visszaadja a **blockDefault** attribútumot, amely beállítja a **block** attribútum alapértelmezett értékét az elem és összetett típusok **targetNamespace**-ében a sémában. |
| [XmlSchemaForm](../xmlschemaform/) [get_ElementFormDefault](./get_elementformdefault/)() | Visszaadja az elemek formáját, amely a séma célnevterében van deklarálva. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Elements](./get_elements/)() | Visszaadja a sémában lévő összes elem sémakompiláció utáni értékét. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalDefault](./get_finaldefault/)() | Visszaadja a **finalDefault** attribútumot, amely beállítja a **final** attribútum alapértelmezett értékét az elemek és összetett típusok célnevterében a sémában. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Groups](./get_groups/)() | Visszaadja a sémában lévő összes csoport sémakompiláció utáni értékét. |
| [String](../../system/string/) [get_Id](./get_id/)() | Visszaadja a karakterlánc azonosítót. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Includes](./get_includes/)() | Visszaadja a beillesztett és importált sémák gyűjteményét. |
| **bool** [get_IsCompiled](./get_iscompiled/)() | Jelzi, hogy a séma le van-e fordítva. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Items](./get_items/)() | Visszaadja a sémában lévő sémaelemek gyűjteményét, és új elem típusok hozzáadására szolgál a **schema** elem szinten. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Visszaadja a sor számát a fájlban, amelyre a **schema** elem hivatkozik. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Visszaadja a sor pozícióját a fájlban, amelyre a **schema** elem hivatkozik. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Visszaadja a XmlSerializerNamespaces értékét, amelyet ezzel a sémaobjektummal kell használni. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Notations](./get_notations/)() | Visszaadja a sémában lévő összes jelölés sémakompiláció utáni értékét. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Visszaadja ennek a [XmlSchemaObject](../xmlschemaobject/) szülőjét. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_SchemaTypes](./get_schematypes/)() | Visszaadja a sémában lévő összes séma típus sémakompiláció utáni értékét. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Visszaadja a forrás helyét annak a fájlnak, amely betöltötte a sémát. |
| [String](../../system/string/) [get_TargetNamespace](./get_targetnamespace/)() | Visszaadja a séma célnevterének egységes erőforrás-azonosítóját (URI). |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](./get_unhandledattributes/)() | Visszaadja a minősített attribútumokat, amelyek nem tartoznak a séma célnevteréhez. |
| [String](../../system/string/) [get_Version](./get_version/)() | Visszaadja a séma verzióját. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyeleti objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és engedélyezi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és engedélyezi az alosztályok másolókonstrukcióját. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | Olvas egy XML [Schema](../)-t a megadott [IO::TextReader](../../system.io/textreader/)-ból. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | Olvas egy XML [Schema](../)-t a megadott adatfolyamból. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | Olvas egy XML [Schema](../)-t a megadott [XmlReader](../../system.xml/xmlreader/)-ból. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlít össze értéktípus objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_AttributeFormDefault](./set_attributeformdefault/)([XmlSchemaForm](../xmlschemaform/)) | Beállítja az attribútumok formáját, amely a séma célnevterében van deklarálva. |
| void [set_BlockDefault](./set_blockdefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Beállítja a **blockDefault** attribútumot, amely beállítja a **block** attribútum alapértelmezett értékét az elem és összetett típusok **targetNamespace**-ében a sémában. |
| void [set_ElementFormDefault](./set_elementformdefault/)([XmlSchemaForm](../xmlschemaform/)) | Beállítja az elemek formáját, amely a séma célnevterében van deklarálva. |
| void [set_FinalDefault](./set_finaldefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Beállítja a **finalDefault** attribútumot, amely beállítja a **final** attribútum alapértelmezett értékét az elemek és összetett típusok célnevterében a sémában. |
| void [set_Id](./set_id/)(const [String](../../system/string/)\&) | Beállítja a karakterlánc azonosítót. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Beállítja a sor számát a fájlban, amelyre a **schema** elem hivatkozik. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Beállítja a sor pozícióját a fájlban, amelyre a **schema** elem hivatkozik. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Beállítja a XmlSerializerNamespaces-t, amelyet ezzel a sémaobjektummal kell használni. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Beállítja ennek a [XmlSchemaObject](../xmlschemaobject/) szülőjét. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Beállítja a forrás helyét annak a fájlnak, amely betöltötte a sémát. |
| void [set_TargetNamespace](./set_targetnamespace/)(const [String](../../system/string/)\&) | Beállítja a séma célnevterének egységes erőforrás-azonosítóját (URI). |
| void [set_UnhandledAttributes](./set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Beállítja a minősített attribútumokat, amelyek nem tartoznak a séma célnevteréhez. |
| void [set_Version](./set_version/)(const [String](../../system/string/)\&) | Beállítja a séma verzióját. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóként (nem megosztottként) állítja be. Lehetővé teszi a mutatók átkapcsolását a tárolókban gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyeleti objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Kiírja az XML [Schema](../)-t a megadott adatfolyamba. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | Kiírja az XML [Schema](../)-t a megadott Stream-re a megadott [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/) használatával. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Kiírja az XML [Schema](../)-t a megadott [IO::TextWriter](../../system.io/textwriter/)-ba. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | Kiírja az XML [Schema](../)-t a megadott TextWriter-be. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | Kiírja az XML [Schema](../)-t a megadott [XmlWriter](../../system.xml/xmlwriter/)-ba. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | Kiírja az XML [Schema](../)-t a megadott [XmlWriter](../../system.xml/xmlwriter/)-ba. |
| [XmlSchema](./xmlschema/)() | Új példányt inicializál a [XmlSchema](./) osztályból. |
| [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Új példányt inicializál a [XmlSchemaObject](../xmlschemaobject/) osztályból. |
| virtual [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [InstanceNamespace](./instancenamespace/) | Az XML séma példány névtere. Ez a mező állandó. |
| static [Namespace](./namespace/) | Az XML séma névtér. Ez a mező állandó. |

## Típedefiníciók

| Típedefiníció | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Megosztott mutató aliasa ennek az osztálynak egy példányára. |

## Megjegyzések

Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányokat ebből a típusból a stack-en vagy az operator new segítségével, mert futásidejű hibákat és/vagy assert hibákat okoz. Mindig csomagolja be ezt az osztályt [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek.

## Lásd még

* Osztály [XmlSchemaObject](../xmlschemaobject/)
* Névtér [System::Xml::Schema](../)
* Könyvtár [Aspose.Slides](../../)