---
title: XmlSchemaComplexType
second_title: Aspose.Slides för C++ API-referens
description: Representerar complexType-elementet från XML-schema enligt World Wide Web Consortium (W3C). Denna klass definierar en komplex typ som bestämmer mängden attribut och innehåll för ett element.
type: docs
weight: 300
url: /sv/system.xml.schema/xmlschemacomplextype/
---
## XmlSchemaComplexType klass


Representerar **complexType**-elementet från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass definierar en komplex typ som bestämmer mängden attribut och innehåll för ett element.

```cpp
class XmlSchemaComplexType : public System::Xml::Schema::XmlSchemaType
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Returnerar **annotation** egenskapen. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AnyAttribute](./get_anyattribute/)() | Returnerar värdet för [XmlSchemaAnyAttribute](../xmlschemaanyattribute/)-komponenten av den komplexa typen. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Attributes](./get_attributes/)() | Returnerar samlingen av attribut för den komplexa typen. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeUses](./get_attributeuses/)() | Returnerar samlingen av alla sammanslagna attribut för denna komplexa typ och dess basklasser. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AttributeWildcard](./get_attributewildcard/)() | Returnerar post-kompileringsvärdet för **anyAttribute** för denna komplexa typ och dess basklass(er). |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](../xmlschematype/get_baseschematype/)() | Returnerar post-kompileringsobjekttypen eller den inbyggda XML [Schema](../) Definition Language (XSD)-datatypen, simpleType-elementet eller complexType-elementet. Detta är ett post-schema-kompilerings-infoset-värde. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_BaseXmlSchemaType](../xmlschematype/get_basexmlschematype/)() | Returnerar post-kompileringsvärdet för basklassen av denna schematyp. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | Returnerar **block**-attributet. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | Returnerar värdet efter att typen har kompilerats till post-schema-validerings-informationssetet (infoset). Detta värde anger hur typen verkställs när **xsi:type** används i instansdokumentet. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\> [get_ContentModel](./get_contentmodel/)() | Returnerar post-kompilerings[XmlSchemaContentModel](../xmlschemacontentmodel/) för denna komplexa typ. |
| [XmlSchemaContentType](../xmlschemacontenttype/) [get_ContentType](./get_contenttype/)() | Returnerar innehållsmodellen för den komplexa typen som innehåller post-kompileringsvärdet. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_ContentTypeParticle](./get_contenttypeparticle/)() | Returnerar partikeln som innehåller post-kompileringsvärdet för [XmlSchemaComplexType::get_ContentType](./get_contenttype/)-partikeln. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](../xmlschematype/get_datatype/)() | Returnerar post-kompileringsvärdet för datatypen för den komplexa typen. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](../xmlschematype/get_derivedby/)() | Returnerar post-kompileringsinformation om hur detta element härleddes från dess basklass. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](../xmlschematype/get_final/)() | Returnerar det slutliga attributet för typderivationen som indikerar om ytterligare härledningar är tillåtna. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](../xmlschematype/get_finalresolved/)() | Returnerar post-kompileringsinterpretationen av [XmlSchemaType::get_Final](../xmlschematype/get_final/)-värdet. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Returnerar sträng-id. |
| **bool** [get_IsAbstract](./get_isabstract/)() | Returnerar informationen som avgör om **complexType**-elementet kan användas i instansdokumentet. |
| **bool** [get_IsMixed](./get_ismixed/)() override | Returnerar information som avgör om den komplexa typen har en blandad innehållsmodell (markup inom innehållet). |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Returnerar radnumret i filen som **schema**-elementet refererar till. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Returnerar radpositionen i filen som **schema**-elementet refererar till. |
| [String](../../system/string/) [get_Name](../xmlschematype/get_name/)() | Returnerar typens namn. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Returnerar XmlSerializerNamespaces att använda med detta schemobjekt. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Returnerar föräldern till detta [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_Particle](./get_particle/)() | Returnerar kompositortypen som en av klasserna [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) eller [XmlSchemaSequence](../xmlschemasequence/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschematype/get_qualifiedname/)() | Returnerar det kvalificerade namnet för typen byggt från **Name**-attributet för denna typ. Detta är ett post-schema-kompileringsvärde. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Returnerar källplatsen för filen som laddade schemat. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](../xmlschematype/get_typecode/)() | Returnerar XmlTypeCode för typen. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Returnerar de kvalificerade attributen som inte tillhör det aktuella schemats mål-namnrymd. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | Returnerar ett [XmlSchemaComplexType](./) som representerar den inbyggda komplexa typen för den angivna komplexa typen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Returnerar ett [XmlSchemaComplexType](./) som representerar den inbyggda komplexa typen för den komplexa typen som anges av ett kvalificerat namn. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Returnerar ett [XmlSchemaSimpleType](../xmlschemasimpletype/) som representerar den inbyggda enkla typen för den enkla typen som anges av ett kvalificerat namn. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | Returnerar ett [XmlSchemaSimpleType](../xmlschemasimpletype/) som representerar den inbyggda enkla typen för den angivna enkla typen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknar-datastrukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen för objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| static **bool** [IsDerivedFrom](../xmlschematype/isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Returnerar ett värde som indikerar om den angivna derivade schematypen är härledd från den angivna baskschematypen. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför en värdetypobjekt med nullptr via referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Sätter **annotation**-egenskapen. |
| void [set_AnyAttribute](./set_anyattribute/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\>\&) | Sätter värdet för [XmlSchemaAnyAttribute](../xmlschemaanyattribute/)-komponenten av den komplexa typen. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Sätter **block**-attributet. |
| void [set_ContentModel](./set_contentmodel/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\>\&) | Sätter post-kompilerings[XmlSchemaContentModel](../xmlschemacontentmodel/) för denna komplexa typ. |
| void [set_Final](../xmlschematype/set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Sätter det slutliga attributet för typderivationen som indikerar om ytterligare härledningar är tillåtna. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Sätter sträng-id-t. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | Sätter informationen som avgör om **complexType**-elementet kan användas i instansdokumentet. |
| void [set_IsMixed](./set_ismixed/)(**bool**) override | Sätter information som avgör om den komplexa typen har en blandad innehållsmodell (markup inom innehållet). |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Sätter radnumret i filen som **schema**-elementet refererar till. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Sätter radpositionen i filen som **schema**-elementet refererar till. |
| void [set_Name](../xmlschematype/set_name/)(const [String](../../system/string/)\&) | Sätter typens namn. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Sätter XmlSerializerNamespaces att använda med detta schemobjekt. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Sätter föräldern till detta [XmlSchemaObject](../xmlschemaobject/). |
| void [set_Particle](./set_particle/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\&) | Sätter kompositortypen som en av klasserna [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) eller [XmlSchemaSequence](../xmlschemasequence/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Sätter källplatsen för filen som laddade schemat. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Sätter de kvalificerade attributen som inte tillhör det aktuella schemats mål-namnrymd. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n't:e mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar nuvarande värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning enligt C# lock()-sats upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
|  [XmlSchemaComplexType](./xmlschemacomplextype/)() | Initierar en ny instans av klassen [XmlSchemaComplexType](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initierar en ny instans av klassen [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaType](../xmlschematype/xmlschematype/)() | Initierar en ny instans av klassen [XmlSchemaType](../xmlschematype/). |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Typedefinitioner

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |

## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körningsfel och/eller påståendefel. Omge alltid denna klass med en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att vidarebefordra den till funktioner som argument. 

## Se även

* Klass [XmlSchemaType](../xmlschematype/)
* Namnrymd [System::Xml::Schema](../)
* Bibliotek [Aspose.Slides](../../)