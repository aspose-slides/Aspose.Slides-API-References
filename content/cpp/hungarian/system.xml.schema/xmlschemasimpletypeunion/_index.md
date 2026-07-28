---
title: XmlSchemaSimpleTypeUnion
second_title: Aspose.Slides C++ API referencia
description: Ábrázolja a World Wide Web Consortium (W3C) által meghatározott XML Schema egyszerű típusaihoz tartozó union elemet. Egy union adat típus használható a simpleType tartalmának meghatározására. A simpleType elem értékének a union által megadott alternatív adat típusok egyike kell legyen. Az union típusok mindig származtatott típusok, és legalább két alternatív adat típust kell tartalmazzanak.
type: docs
weight: 885
url: /hu/system.xml.schema/xmlschemasimpletypeunion/
---
## XmlSchemaSimpleTypeUnion osztály

Ábrázolja a **union** elemet az XML [Schema](../) egyszerű típusai számára, ahogyan a World Wide [Web](../../system.web/) Consortium (W3C) előírja. A **union** adat típust használhatjuk egy **simpleType** tartalmának meghatározására. A **simpleType** elem értékének a unionban megadott alternatív adat típusok bármelyikének kell lennie. Az union típusok mindig származtatott típusok, és legalább két alternatív adat típust kell tartalmazzanak.

```cpp
class XmlSchemaSimpleTypeUnion : public System::Xml::Schema::XmlSchemaSimpleTypeContent
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemiántikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Visszaadja a **annotation** tulajdonságot. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\>\> [get_BaseMemberTypes](./get_basemembertypes/)() | Visszaad egy tömböt [XmlSchemaSimpleType](../xmlschemasimpletype/) objektumokból, amelyek a **simpleType** elem típusát képviselik a [XmlSchemaSimpleTypeUnion::get_BaseTypes](./get_basetypes/) és [XmlSchemaSimpleTypeUnion::get_MemberTypes](./get_membertypes/) értékek alapján a egyszerű típusnál. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_BaseTypes](./get_basetypes/)() | Visszaadja az alaptípusok gyűjteményét. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Visszaadja a karakterlánc azonosítót. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Visszaadja a sor számát a fájlban, amelyre a **schema** elem hivatkozik. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Visszaadja a sor pozícióját a fájlban, amelyre a **schema** elem hivatkozik. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\> [get_MemberTypes](./get_membertypes/)() | Visszaadja a minősített tagnevek tömbjét a beépített adat típusok vagy **simpleType** elemek számára, amelyeket ebben a sémában (vagy egy másik, a megadott névtér által jelzett sémában) definiáltak. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Visszaadja az XmlSerializerNamespaces-t, amelyet ezzel a schema objektummal lehet használni. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Visszaadja ennek a [XmlSchemaObject](../xmlschemaobject/) szülőjét. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Visszaadja a forrás helyét a sémát betöltő fájlhoz. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Visszaadja a minősített attribútumokat, amelyek nem tartoznak a jelenlegi séma célnevteréhez. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Engedélyezi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus egy példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Engedélyezi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolás-konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolás-konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja az érték típusú objektumot a nullptr-vel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Beállítja a **annotation** tulajdonságot. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Beállítja a karakterlánc azonosítót. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Beállítja a sor számát a fájlban, amelyre a **schema** elem hivatkozik. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Beállítja a sor pozícióját a fájlban, amelyre a **schema** elem hivatkozik. |
| void [set_MemberTypes](./set_membertypes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\>\&) | Beállítja a minősített tagnevek tömbjét a beépített adat típusok vagy **simpleType** elemek számára, amelyeket ebben a sémában (vagy a megadott névtér által jelzett másik sémában) definiáltak. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Beállítja az XmlSerializerNamespaces-t, amelyet ezzel a schema objektummal használ. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Beállítja ennek a [XmlSchemaObject](../xmlschemaobject/) szülőjét. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Beállítja a forrás helyét a sémát betöltő fájlhoz. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Beállítja a minősített attribútumokat, amelyek nem tartoznak a jelenlegi séma célnevteréhez. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablon argumentumot gyenge mutatóvá (ahelyett, hogy megosztott) állítja. Lehetővé teszi a mutatók átkapcsolását a gyenge módba a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Engedélyezi az egyedi objektumok karakterlánccá alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Inicializál egy új példányt a [XmlSchemaObject](../xmlschemaobject/) osztályból. |
|  [XmlSchemaSimpleTypeUnion](./xmlschemasimpletypeunion/)() | Inicializál egy új példányt a [XmlSchemaSimpleTypeUnion](./) osztályból. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Typedefek

| Typedef | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Az osztály egy példányára mutató megosztott mutató álneve. |

## Megjegyzések

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## Lásd még

* Osztály [XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)
* Névterület [System::Xml::Schema](../)
* Könyvtár [Aspose.Slides](../../)