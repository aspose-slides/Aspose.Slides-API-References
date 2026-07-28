---
title: XmlSchemaAny
second_title: Aspose.Slides for C++ API Referencia
description: A World Wide Web Consortium (W3C) any elemet képviseli.
type: docs
weight: 131
url: /hu/system.xml.schema/xmlschemaany/
---
## XmlSchemaAny osztály


A World Wide [Web](../../system.web/) Consortium (W3C) **any** elemet képviseli.

```cpp
class XmlSchemaAny : public System::Xml::Schema::XmlSchemaParticle
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Visszaadja a **annotation** tulajdonságot. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Visszaadja a karakterlánc azonosítót. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Visszaadja a fájl sor számát, amelyre a **schema** elem mutat. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Visszaadja a fájl sor pozícióját, amelyre a **schema** elem mutat. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | Visszaadja, hogy a részecske legfeljebb hányszor fordulhat elő. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | Visszaadja a számot karakterlánc értékként. A részecske legfeljebb hányszor fordulhat elő. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | Visszaadja, hogy a részecske legalább hányszor fordulhat elő. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | Visszaadja a számot karakterlánc értékként. A részecske legalább hányszor fordulhat elő. |
| [String](../../system/string/) [get_Namespace](./get_namespace/)() | Visszaadja azokat a névtereket, amelyek tartalmazzák a felhasználható elemeket. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Visszaadja a használható XmlSerializerNamespaces-et ezzel a sémaobjektummal. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Visszaadja ennek a [XmlSchemaObject](../xmlschemaobject/) szülőjét. |
| [XmlSchemaContentProcessing](../xmlschemacontentprocessing/) [get_ProcessContents](./get_processcontents/)() | Visszaadja az információt arról, hogyan kell egy alkalmazásnak vagy XML-feldolgozónak kezelnie az XML-dokumentumok validálását a **any** elem által meghatározott elemekhez. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Visszaadja a forráshelyet a sémát betöltő fájlhoz. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Visszaadja a minősített attribútumokat, amelyek nem tartoznak az aktuális séma cél névteréhez. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciacsökkentő adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrizze, hogy az objektum a targetType által leírt típus példányát képviseli-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlít össze értéktípusú objektumot a nullptr-fel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciacsökkentőt a megadott értékkel. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Beállítja a **annotation** tulajdonságot. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Beállítja a karakterlánc azonosítót. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Beállítja a sor számát a fájlban, amelyre a **schema** elem mutat. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Beállítja a sor pozícióját a fájlban, amelyre a **schema** elem mutat. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | Beállítja a részecske legfeljebb előfordulási számát. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | Beállítja a számot karakterlánc értékként. A részecske legfeljebb előfordulási száma. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | Beállítja a részecske legkevesebb előfordulási számát. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | Beállítja a számot karakterlánc értékként. A részecske legkevesebb előfordulási száma. |
| void [set_Namespace](./set_namespace/)(const [String](../../system/string/)\&) | Beállítja a használható elemeket tartalmazó névtereket. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Beállítja a használható XmlSerializerNamespaces-et ezzel a sémaobjektummal. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Beállítja ennek a [XmlSchemaObject](../xmlschemaobject/) szülőjét. |
| void [set_ProcessContents](./set_processcontents/)([XmlSchemaContentProcessing](../xmlschemacontentprocessing/)) | Beállítja az információt arról, hogyan kell egy alkalmazásnak vagy XML-feldolgozónak kezelnie az XML-dokumentumok validálását a **any** elem által meghatározott elemekhez. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Beállítja a forráshelyet a sémát betöltő fájlhoz. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Beállítja a minősített attribútumokat, amelyek nem tartoznak az aktuális séma cél névteréhez. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóként állítja be (ahelyett, hogy megosztott lenne). Lehetővé teszi a mutatók konténerekben gyenge módba való váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciacsökkentő jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciacsökkentőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciacsökkentőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciacsökkentőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciacsökkentőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [XmlSchemaAny](./xmlschemaany/)() | Inicializál egy új példányt a [XmlSchemaAny](./) osztályból. |
| [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Inicializál egy új példányt a [XmlSchemaObject](../xmlschemaobject/) osztályból. |
| [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | Inicializál egy új példányt a [XmlSchemaParticle](../xmlschemaparticle/) osztályból. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Olyan alias, amely megosztott mutatót jelent erre az osztályra mutató példányra. |

## Megjegyzések

Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányokat a stacken vagy az operator new használatával, mivel runtime hibákhoz és/vagy assertion hibákhoz vezethet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az objektum argumentumként történő átadásához a függvényeknek. 

## Lásd még

* Osztály [XmlSchemaParticle](../xmlschemaparticle/)
* Névterület [System::Xml::Schema](../)
* Könyvtár [Aspose.Slides](../../)