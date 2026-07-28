---
title: XmlSchemaKey
second_title: Aspose.Slides C++ API Referencia
description: Ez az osztály a World Wide Web Consortium (W3C) által meghatározott XMLSchema kulcselemét képviseli.
type: docs
weight: 534
url: /hu/system.xml.schema/xmlschemakey/
---
## XmlSchemaKey osztály


Ez az osztály a **key** elemet képviseli az XMLSchema-ból, ahogy a World Wide [Web](../../system.web/) Consortium (W3C) határozza meg.

```cpp
class XmlSchemaKey : public System::Xml::Schema::XmlSchemaIdentityConstraint
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Visszaadja az **annotation** tulajdonságot. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Fields](../xmlschemaidentityconstraint/get_fields/)() | Visszaadja a mezők gyűjteményét, amelyek a XML Path Language ([XPath](../../system.xml.xpath/)) kifejezésválasztó gyermekeként érvényesülnek. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Visszaadja a karakterlánc azonosítót. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Visszaadja a sor számát a fájlban, amelyhez a **schema** elem tartozik. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Visszaadja a sor pozícióját a fájlban, amelyhez a **schema** elem tartozik. |
| [String](../../system/string/) [get_Name](../xmlschemaidentityconstraint/get_name/)() | Visszaadja az identitás-korlátozás nevét. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Visszaadja a XmlSerializerNamespaces értéket, amelyet ezzel a sémaobjektummal kell használni. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Visszaadja ennek a [XmlSchemaObject](../xmlschemaobject/) szülőjét. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschemaidentityconstraint/get_qualifiedname/)() | Visszaadja az identitás-korlátozás minősített nevét, amely a **QualifiedName** érték utólagos fordítás utáni értelmezését tartalmazza. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaXPath](../xmlschemaxpath/)\> [get_Selector](../xmlschemaidentityconstraint/get_selector/)() | Visszaadja a [XPath](../../system.xml.xpath/) kifejezés **selector** elemét. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Visszaadja a forrás helyét a sémát betöltő fájl számára. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Visszaadja a minősített attribútumokat, amelyek nem tartoznak a jelenlegi séma cél névtéréhez. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektummal kapcsolatos referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi a leszármazottak másolókonstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi a leszármazottak másolókonstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint összehasonlítja az érték típusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Beállítja az **annotation** tulajdonságot. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Beállítja a karakterlánc azonosítót. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Beállítja a sor számát a fájlban, amelyhez a **schema** elem tartozik. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Beállítja a sor pozícióját a fájlban, amelyhez a **schema** elem tartozik. |
| void [set_Name](../xmlschemaidentityconstraint/set_name/)(const [String](../../system/string/)\&) | Beállítja az identitás-korlátozás nevét. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Beállítja a XmlSerializerNamespaces értéket, amelyet ezzel a sémaobjektummal kell használni. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Beállítja ennek a [XmlSchemaObject](../xmlschemaobject/) szülőjét. |
| void [set_Selector](../xmlschemaidentityconstraint/set_selector/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaXPath](../xmlschemaxpath/)\>\&) | Beállítja a [XPath](../../system.xml.xpath/) kifejezés **selector** elemét. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Beállítja a forrás helyét a sémát betöltő fájl számára. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Beállítja a minősített attribútumokat, amelyek nem tartoznak a jelenlegi séma cél névtérhez. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-dik sablonargumentumot gyenge mutatóként állítja be (a megosztott helyett). Lehetővé teszi a mutatók konténerekben való gyenge módba való átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon intelligens mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon intelligens mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon intelligens mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon intelligens mutatókat vagy ThisProtector-t. |
|  [XmlSchemaIdentityConstraint](../xmlschemaidentityconstraint/xmlschemaidentityconstraint/)() | Inicializál egy új példányt a [XmlSchemaIdentityConstraint](../xmlschemaidentityconstraint/) osztályból. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Inicializál egy új példányt a [XmlSchemaObject](../xmlschemaobject/) osztályból. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Typedef-ek

| Típusdefiníció | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Egy álnév a megosztott mutatóhoz, amely ennek az osztálynak egy példányára mutat. |
## Megjegyzések



Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányokat ebben a típusban a stack-en vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként való átadásához a függvényeknek. 

## Lásd még

* Osztály [XmlSchemaIdentityConstraint](../xmlschemaidentityconstraint/)
* Névtér [System::Xml::Schema](../)
* Könyvtár [Aspose.Slides](../../)