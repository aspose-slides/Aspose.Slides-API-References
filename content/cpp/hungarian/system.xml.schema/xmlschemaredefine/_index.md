---
title: XmlSchemaRedefine
second_title: Aspose.Slides for C++ API referenciája
description: A World Wide Web Consortium (W3C) által meghatározott XML Schema redefine elemet ábrázolja. Ez az osztály lehetővé teszi egyszerű és összetett típusok, csoportok és attribútumcsoportok külső sémafájlokból történő újradefiniálását az aktuális sémában. Emellett a sémaelemek verziókezelésére is használható.
type: docs
weight: 755
url: /hu/system.xml.schema/xmlschemaredefine/
---
## XmlSchemaRedefine osztály


A **redefine** elemet képviseli az XML [Schema](../)-ből a World Wide [Web](../../system.web/) Consortium (W3C) által meghatározottak szerint. Ez az osztály használható egyszerű és összetett típusok, csoportok és attribútumcsoportok külső sémafájlokból történő újradefiniálására az aktuális sémában. Ez az osztály a sémaelemek verziókezelésére is használható.

```cpp
class XmlSchemaRedefine : public System::Xml::Schema::XmlSchemaExternal
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeGroups](./get_attributegroups/)() | Visszaadja a [XmlSchemaObjectTable](../xmlschemaobjecttable/) , a séma összes attribútumához, amely a **AttributeGroups** érték fordítás utáni értelmezését tartalmazza. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Groups](./get_groups/)() | Visszaadja a [XmlSchemaObjectTable](../xmlschemaobjecttable/)-t, a séma összes csoportjához, amely a **Groups** érték fordítás utáni értelmezését tartalmazza. |
| [String](../../system/string/) [get_Id](../xmlschemaexternal/get_id/)() | Visszaadja a karakterlánc-azonosítót. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Items](./get_items/)() | Visszaadja az alábbi osztályok gyűjteményét: [XmlSchemaAnnotation](../xmlschemaannotation/), [XmlSchemaAttributeGroup](../xmlschemaattributegroup/), [XmlSchemaComplexType](../xmlschemacomplextype/), [XmlSchemaSimpleType](../xmlschemasimpletype/) és [XmlSchemaGroup](../xmlschemagroup/). |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Visszaadja a fájl sor számát, amelyhez a **schema** elem hivatkozik. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Visszaadja a fájl sorpozícióját, amelyhez a **schema** elem hivatkozik. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Visszaadja a XmlSerializerNamespaces-t, amelyet ezzel a sémaobjektummal kell használni. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Visszaadja ennek a [XmlSchemaObject](../xmlschemaobject/) szülőjét. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [get_Schema](../xmlschemaexternal/get_schema/)() | Visszaadja a [XmlSchema](../xmlschema/)-t a hivatkozott sémához. |
| [String](../../system/string/) [get_SchemaLocation](../xmlschemaexternal/get_schemalocation/)() | Visszaadja a Uniform Resource Identifier (URI) helyét a sémához, amely megmutatja a sémafeldolgozónak, hogy a séma hol található fizikailag. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_SchemaTypes](./get_schematypes/)() | Visszaadja a [XmlSchemaObjectTable](../xmlschemaobjecttable/)-t, a séma összes egyszerű és összetett típusához, amely a **SchemaTypes** érték fordítás utáni értelmezését tartalmazza. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Visszaadja a forráshelyet a sémát betöltő fájlhoz. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaexternal/get_unhandledattributes/)() | Visszaadja a kvalifikált attribútumokat, amelyek nem tartoznak a séma célnevtérhez. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektummal társított referenciacsounter adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) senti objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktőr. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolásával történő konstrukciót. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolásával történő konstrukciót. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Id](../xmlschemaexternal/set_id/)(const [String](../../system/string/)\&) | Beállítja a karakterlánc-azonosítót. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Beállítja a fájl sor számát, amelyhez a **schema** elem hivatkozik. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Beállítja a fájl sorpozícióját, amelyhez a **schema** elem hivatkozik. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Beállítja a XmlSerializerNamespaces-t, amelyet ezzel a sémaobjektummal kell használni. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Beállítja ennek a [XmlSchemaObject](../xmlschemaobject/) szülőjét. |
| void [set_Schema](../xmlschemaexternal/set_schema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Beállítja a [XmlSchema](../xmlschema/)-t a hivatkozott sémához. |
| void [set_SchemaLocation](../xmlschemaexternal/set_schemalocation/)(const [String](../../system/string/)\&) | Beállítja a Uniform Resource Identifier (URI) helyét a sémához, amely megmondja a sémafeldolgozónak, hogy a séma hol található fizikailag. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Beállítja a forráshelyet a sémát betöltő fájlra. |
| void [set_UnhandledAttributes](../xmlschemaexternal/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Beállítja a kvalifikált attribútumokat, amelyek nem tartoznak a séma célnevtérhez. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablon argumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerekben történő gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi az egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [XmlSchemaExternal](../xmlschemaexternal/xmlschemaexternal/)() | Inicializál egy új példányt a [XmlSchemaExternal](../xmlschemaexternal/) osztályból. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Inicializál egy új példányt a [XmlSchemaObject](../xmlschemaobject/) osztályból. |
|  [XmlSchemaRedefine](./xmlschemaredefine/)() | Inicializál egy új példányt a [XmlSchemaRedefine](./) osztályból. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Typedefek

| Typedef | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Az osztály egy példányára mutató megosztott mutató aliasa. |

## Megjegyzések



Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányokat ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy assert hibákat okoz. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az objektum argumentumként való átadásához a függvényeknek. 

## Lásd még

* Osztály [XmlSchemaExternal](../xmlschemaexternal/)
* Névtér [System::Xml::Schema](../)
* Könyvtár [Aspose.Slides](../../)