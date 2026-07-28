---
title: XmlSchemaValidator
second_title: Aspose.Slides C++ API referencia
description: Egy XML Schema Definition Language (XSD) séma validációs motorját reprezentálja. Az XmlSchemaValidator osztály nem örökölhető.
type: docs
weight: 937
url: /hu/system.xml.schema/xmlschemavalidator/
---
## XmlSchemaValidator osztály


Egy XML [Schema](../) Definition Language (XSD) [Schema](../) validációs motorját reprezentálja. A [XmlSchemaValidator](./) osztály nem örökölhető.

```cpp
class XmlSchemaValidator : public System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| void [AddSchema](./addschema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Hozzáad egy XML [Schema](../) Definition Language (XSD) sémát a validáláshoz használt sémák halmazához. |
| void [EndValidation](./endvalidation/)() | Befejezi a validálást, és ellenőrzi az identitáskorlátozásokat az egész XML dokumentumra vonatkozóan. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [SharedPtr](../../system/sharedptr/)\<[IXmlLineInfo](../../system.xml/ixmllineinfo/)\> [get_LineInfoProvider](./get_lineinfoprovider/)() | Visszaadja a sor száma információt az éppen validált XML csomópontról. |
| [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_SourceUri](./get_sourceuri/)() | Visszaadja az éppen validált XML csomóponthoz tartozó forrás URI-t. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ValidationEventSender](./get_validationeventsender/)() | Visszaadja azt az objektumot, amely a validálási esemény küldő objektumaként lett elküldve. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referencia számláló adatszerkezetet. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\>\> [GetExpectedAttributes](./getexpectedattributes/)() | Visszaadja a várt attribútumokat a jelenlegi elem kontextusában. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\> [GetExpectedParticles](./getexpectedparticles/)() | Visszaadja a várt részecskéket a jelenlegi elem kontextusában. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum aktuális típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| void [GetUnspecifiedDefaultAttributes](./getunspecifieddefaultattributes/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\>\&) | Érvényesíti az identitáskorlátozásokat az alapértelmezett attribútumokon, és felépíti a [XmlSchemaAttribute](../xmlschemaattribute/) objektumokat tartalmazó Listát minden olyan attribútumhoz, amelynek alapértelmezett értéke még nem lett előzőleg validálva a [XmlSchemaValidator::ValidateAttribute](./validateattribute/) metódus használatával az elem kontextusában. |
| void [Initialize](./initialize/)() | Inicializálja a [XmlSchemaValidator](./) objektum állapotát. |
| void [Initialize](./initialize/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Inicializálja a [XmlSchemaValidator](./) objektum állapotát a részleges validáláshoz megadott [XmlSchemaObject](../xmlschemaobject/) használatával. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia összehasonlítja az értéktípusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_LineInfoProvider](./set_lineinfoprovider/)(const [SharedPtr](../../system/sharedptr/)\<[IXmlLineInfo](../../system.xml/ixmllineinfo/)\>\&) | Beállítja a sor száma információt az éppen validált XML csomópontra. |
| void [set_SourceUri](./set_sourceuri/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&) | Beállítja a forrás URI-t az éppen validált XML csomópontra. |
| void [set_ValidationEventSender](./set_validationeventsender/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Beállítja azt az objektumot, amely a validálási esemény küldő objektumaként lesz elküldve. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Beállítja a [XmlResolver](../../system.xml/xmlresolver/) objektumot, amelyet az **xs:import** és **xs:include** elemek, valamint a **xsi:schemaLocation** és **xsi:noNamespaceSchemaLocation** attribútumok feloldásához használnak. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerekben való weak módra történő átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [SkipToEndElement](./skiptoendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Kihagyja a jelenlegi elem tartalmának validálását, és előkészíti a [XmlSchemaValidator](./) objektumot a szülő elem kontextusában lévő tartalom validálására. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateAttribute](./validateattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Érvényesíti az attribútum nevét, a névtér URI-t és az értéket a jelenlegi elem kontextusában. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateAttribute](./validateattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [XmlValueGetter](../xmlvaluegetter/), const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Érvényesíti az attribútum nevét, a névtér URI-t és az értéket a jelenlegi elem kontextusában. |
| void [ValidateElement](./validateelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Érvényesíti az elemet a jelenlegi kontextusban. |
| void [ValidateElement](./validateelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Érvényesíti az elemet a jelenlegi kontextusban a megadott **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation**, és **xsi:NoNamespaceSchemaLocation** attribútumértékekkel. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateEndElement](./validateendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Ellenőrzi, hogy az elem szövegtartalma érvényes-e az adat típusa szerint egyszerű tartalmú elemek esetén, és ellenőrzi, hogy a jelenlegi elem tartalma teljes-e összetett tartalmú elemeknél. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateEndElement](./validateendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Ellenőrzi, hogy a megadott elem szövegtartalma érvényes-e az adat típusa szerint. |
| void [ValidateEndOfAttributes](./validateendofattributes/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Ellenőrzi, hogy az elem kontextusában minden kötelező attribútum jelen van-e, és előkészíti a [XmlSchemaValidator](./) objektumot az elem gyermek tartalmának validálására. |
| void [ValidateText](./validatetext/)(const [String](../../system/string/)\&) | Érvényesíti, hogy a megadott **string** szöveg engedélyezett-e a jelenlegi elem kontextusában, és összegyűjti a szöveget a validáláshoz, ha az elem egyszerű tartalommal rendelkezik. |
| void [ValidateText](./validatetext/)([XmlValueGetter](../xmlvaluegetter/)) | Érvényesíti, hogy az XmlValueGetter objektum által visszaadott szöveg engedélyezett-e a jelenlegi elem kontextusában, és összegyűjti a szöveget a validáláshoz, ha az elem egyszerű tartalommal rendelkezik. |
| void [ValidateWhitespace](./validatewhitespace/)(const [String](../../system/string/)\&) | Érvényesíti, hogy a megadott **string** fehér térköz engedélyezett-e a jelenlegi elem kontextusában, és összegyűjti a fehér térközt a validáláshoz, ha az elem egyszerű tartalommal rendelkezik. |
| void [ValidateWhitespace](./validatewhitespace/)([XmlValueGetter](../xmlvaluegetter/)) | Érvényesíti, hogy az XmlValueGetter objektum által visszaadott fehér térköz engedélyezett-e a jelenlegi elem kontextusában, és összegyűjti a fehér térközt a validáláshoz, ha az elem egyszerű tartalommal rendelkezik. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [XmlSchemaValidator](./xmlschemavalidator/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>\&, [XmlSchemaValidationFlags](../xmlschemavalidationflags/)) | Inicializál egy új példányt a [XmlSchemaValidator](./) osztályból. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Egy alias a megosztott mutatóhoz, amely ezen osztály egy példányát mutatja. |

## Megjegyzések

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## Lásd még

* Osztály [Object](../../system/object/)
* Névtere [System::Xml::Schema](../)
* Könyvtár [Aspose.Slides](../../)