---
title: XmlSchemaComplexType
second_title: Aspose.Slides pro C++ API Reference
description: Representuje element complexType ze schématu XML podle specifikace World Wide Web Consortium (W3C). Třída definuje komplexní typ, který určuje sadu atributů a obsah elementu.
type: docs
weight: 300
url: /cs/system.xml.schema/xmlschemacomplextype/
---
## XmlSchemaComplexType třída

Představuje prvek **complexType** z XML [Schema](../) podle specifikace World Wide [Web](../../system.web/) Consortium (W3C). Tato třída definuje komplexní typ, který určuje sadu atributů a obsah elementu.

```cpp
class XmlSchemaComplexType : public System::Xml::Schema::XmlSchemaType
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za stejné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za stejné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Vrací vlastnost **annotation**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AnyAttribute](./get_anyattribute/)() | Vrací hodnotu pro komponentu [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) komplexního typu. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Attributes](./get_attributes/)() | Vrací kolekci atributů pro komplexní typ. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeUses](./get_attributeuses/)() | Vrací kolekci všech zkompilovaných atributů tohoto komplexního typu a jeho základních typů. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AttributeWildcard](./get_attributewildcard/)() | Vrací hodnotu po kompilaci pro **anyAttribute** tohoto komplexního typu a jeho základních typů. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](../xmlschematype/get_baseschematype/)() | Vrací typ objektu po kompilaci nebo vestavěný XML [Schema](../) Definition Language (XSD) datový typ, prvek simpleType nebo complexType. Jedná se o hodnotu infosetu po kompilaci schématu. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_BaseXmlSchemaType](../xmlschematype/get_basexmlschematype/)() | Vrací hodnotu po kompilaci pro základní typ tohoto typu schématu. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | Vrací atribut **block**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | Vrací hodnotu po kompilaci typu do infosetu po validaci schématu. Tato hodnota určuje, jak je typ vynucen, když je v dokumentu instance použito **xsi:type**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\> [get_ContentModel](./get_contentmodel/)() | Vrací po-kompilační [XmlSchemaContentModel](../xmlschemacontentmodel/) tohoto komplexního typu. |
| [XmlSchemaContentType](../xmlschemacontenttype/) [get_ContentType](./get_contenttype/)() | Vrací obsahový model komplexního typu, který obsahuje hodnotu po kompilaci. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_ContentTypeParticle](./get_contenttypeparticle/)() | Vrací částici, která obsahuje hodnotu po kompilaci částice [XmlSchemaComplexType::get_ContentType](./get_contenttype/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](../xmlschematype/get_datatype/)() | Vrací hodnotu po kompilaci pro datový typ komplexního typu. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](../xmlschematype/get_derivedby/)() | Vrací informace po kompilaci o tom, jak byl tento prvek odvozen od svého základního typu. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](../xmlschematype/get_final/)() | Vrací poslední atribut odvození typu, který udává, zda jsou povoleny další odvození. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](../xmlschematype/get_finalresolved/)() | Vrací po-kompilační interpretaci hodnoty [XmlSchemaType::get_Final](../xmlschematype/get_final/). |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Vrací řetězcové ID. |
| **bool** [get_IsAbstract](./get_isabstract/)() | Vrací informace určující, zda může být prvek **complexType** použit v dokumentu instance. |
| **bool** [get_IsMixed](./get_ismixed/)() override | Vrací informace určující, zda komplexní typ má smíšený obsahový model (značení uvnitř obsahu). |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Vrací číslo řádku v souboru, na který odkazuje prvek **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Vrací pozici řádku v souboru, na který odkazuje prvek **schema**. |
| [String](../../system/string/) [get_Name](../xmlschematype/get_name/)() | Vrací název typu. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Vrací XmlSerializerNamespaces k použití s tímto objektem schématu. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Vrací rodiče tohoto [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_Particle](./get_particle/)() | Vrací typ kompozitoru jako jeden z tříd [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) nebo [XmlSchemaSequence](../xmlschemasequence/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschematype/get_qualifiedname/)() | Vrací kvalifikovaný název typu vytvořený z atributu **Name** tohoto typu. Jedná se o hodnotu po kompilaci schématu. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Vrací umístění zdroje souboru, který načetl schéma. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](../xmlschematype/get_typecode/)() | Vrací XmlTypeCode typu. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Vrací kvalifikované atributy, které nepatří do cílového jmenného prostoru aktuálního schématu. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | Vrací [XmlSchemaComplexType](./) představující vestavěný komplexní typ uvedeného komplexního typu. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Vrací [XmlSchemaComplexType](./) představující vestavěný komplexní typ komplexního typu určený kvalifikovaným názvem. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Vrací [XmlSchemaSimpleType](../xmlschemasimpletype/) představující vestavěný jednoduchý typ, který je určen kvalifikovaným názvem. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | Vrací [XmlSchemaSimpleType](../xmlschemasimpletype/) představující vestavěný jednoduchý typ uvedeného typu. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| static **bool** [IsDerivedFrom](../xmlschematype/isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Vrací hodnotu udávající, zda je uvedený odvozený typ schématu odvozen od uvedeného základního typu schématu. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání podle C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje počítadlo sdílených referencí o zadanou hodnotu. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Nastavuje vlastnost **annotation**. |
| void [set_AnyAttribute](./set_anyattribute/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\>\&) | Nastavuje hodnotu komponenty [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) komplexního typu. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Nastavuje atribut **block**. |
| void [set_ContentModel](./set_contentmodel/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\>\&) | Nastavuje po-kompilační [XmlSchemaContentModel](../xmlschemacontentmodel/) tohoto komplexního typu. |
| void [set_Final](../xmlschematype/set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Nastavuje poslední atribut odvození typu, který udává, zda jsou povoleny další odvození. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Nastavuje řetězcové ID. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | Nastavuje informace určující, zda může být prvek **complexType** použit v dokumentu instance. |
| void [set_IsMixed](./set_ismixed/)(**bool**) override | Nastavuje informace určující, zda komplexní typ má smíšený obsahový model (značení uvnitř obsahu). |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Nastavuje číslo řádku v souboru, na který odkazuje prvek **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Nastavuje pozici řádku v souboru, na který odkazuje prvek **schema**. |
| void [set_Name](../xmlschematype/set_name/)(const [String](../../system/string/)\&) | Nastavuje název typu. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Nastavuje XmlSerializerNamespaces k použití s tímto objektem schématu. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Nastavuje rodiče tohoto [XmlSchemaObject](../xmlschemaobject/). |
| void [set_Particle](./set_particle/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\&) | Nastavuje typ kompozitoru jako jeden z tříd [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) nebo [XmlSchemaSequence](../xmlschemasequence/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Nastavuje umístění zdroje souboru, který načetl schéma. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Nastavuje kvalifikované atributy, které nepatří do cílového jmenného prostoru aktuálního schématu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílené počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílené počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje konverzi vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí podle C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabé počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabé počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [XmlSchemaComplexType](./xmlschemacomplextype/)() | Inicializuje novou instanci třídy [XmlSchemaComplexType](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Inicializuje novou instanci třídy [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaType](../xmlschematype/xmlschematype/)() | Inicializuje novou instanci třídy [XmlSchemaType](../xmlschematype/). |
| virtual  [~Object](../../system/object/~object/)() | Niči objekt. Uvolní všechny vnitřní datové struktury. |

## Typedefs

| Typedef | Popis |
| --- | --- |
| [Ptr](./ptr/) | Alias pro sdílený ukazatel na instanci této třídy. |

## Poznámky

Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním assertu. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. 

## Viz také

* Třída [XmlSchemaType](../xmlschematype/)
* Jmenný prostor [System::Xml::Schema](../)
* Knihovna [Aspose.Slides](../../)