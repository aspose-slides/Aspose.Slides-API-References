---
title: XmlSchemaType
second_title: Aspose.Slides för C++ API-referens
description: Basklass för alla enkla typer och komplexa typer.
type: docs
weight: 911
url: /sv/system.xml.schema/xmlschematype/
---
## XmlSchemaType klass


Basklass för alla enkla typer och komplexa typer.

```cpp
class XmlSchemaType : public System::Xml::Schema::XmlSchemaAnnotated
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Returnerar egenskapen **annotation**. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](./get_baseschematype/)() | Returnerar post-kompileringsobjekttypen eller den inbyggda XML [Schema](../) Definition Language (XSD)-datatypen, simpleType-elementet eller complexType-elementet. Detta är ett post-schema-kompilerings-infoset-värde. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\> [get_BaseXmlSchemaType](./get_basexmlschematype/)() | Returnerar post-kompileringsvärdet för basklassen av detta schematyp. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](./get_datatype/)() | Returnerar post-kompileringsvärdet för datatypen av den komplexa typen. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](./get_derivedby/)() | Returnerar post-kompileringsinformation om hur detta element härstamades från dess basklass. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | Returnerar det slutgiltiga attributet för typderivationen som indikerar om ytterligare derivationer är tillåtna. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | Returnerar post-kompileringstolkningen av värdet [XmlSchemaType::get_Final](./get_final/). |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Returnerar sträng-id. |
| virtual **bool** [get_IsMixed](./get_ismixed/)() | Returnerar ett värde som indikerar om denna typ har en blandad innehållsmodell. Detta anrop är endast giltigt i en komplex typ. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Returnerar radnumret i filen som **schema**-elementet refererar till. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Returnerar radpositionen i filen som **schema**-elementet refererar till. |
| [String](../../system/string/) [get_Name](./get_name/)() | Returnerar typens namn. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Returnerar XmlSerializerNamespaces att använda med detta schemasobjekt. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Returnerar föräldern till detta [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | Returnerar det kvalificerade namnet för typen byggt från attributet **Name** för denna typ. Detta är ett post-schema-kompileringsvärde. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Returnerar källplatsen för filen som laddade schemat. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](./get_typecode/)() | Returnerar XmlTypeCode för typen. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Returnerar de kvalificerade attributen som inte tillhör det aktuella schemats mål-namnutrymme. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](./getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | Returnerar ett [XmlSchemaComplexType](../xmlschemacomplextype/) som representerar den inbyggda komplexa typen för den angivna komplexa typen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](./getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Returnerar ett [XmlSchemaComplexType](../xmlschemacomplextype/) som representerar den inbyggda komplexa typen för den komplexa typ som anges med kvalificerat namn. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](./getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Returnerar ett [XmlSchemaSimpleType](../xmlschemasimpletype/) som representerar den inbyggda enkla typen för den enkla typ som anges med kvalificerat namn. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](./getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | Returnerar ett [XmlSchemaSimpleType](../xmlschemasimpletype/) som representerar den inbyggda enkla typen för den angivna enkla typen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknar-datastrukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Gör det möjligt att hash-a anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| static **bool** [IsDerivedFrom](./isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Returnerar ett värde som indikerar om den specificerade derivade schematypen är härledd från den specificerade baskschematypen. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satser för låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Gör det möjligt att klona anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, den initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, den initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Sätter egenskapen **annotation**. |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Sätter det slutgiltiga attributet för typderivationen som indikerar om ytterligare derivationer är tillåtna. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Sätter sträng-id. |
| virtual void [set_IsMixed](./set_ismixed/)(**bool**) | Sätter ett värde som indikerar om denna typ har en blandad innehållsmodell. Detta anrop är endast giltigt i en komplex typ. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Sätter radnumret i filen som **schema**-elementet refererar till. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Sätter radpositionen i filen som **schema**-elementet refererar till. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | Sätter typens namn. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Sätter XmlSerializerNamespaces att använda med detta schemasobjekt. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Sätter föräldern till detta [XmlSchemaObject](../xmlschemaobject/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Sätter källplatsen för filen som laddade schemat. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Sätter de kvalificerade attributen som inte tillhör det aktuella schemats mål-namnutrymme. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Gör det möjligt att konvertera anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satser för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initierar en ny instans av [XmlSchemaObject](../xmlschemaobject/)-klass. |
|  [XmlSchemaType](./xmlschematype/)() | Initierar en ny instans av [XmlSchemaType](./)-klass. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |

## Anmärkningar



Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. 

## Se även

* Klass [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namnrymd [System::Xml::Schema](../)
* Bibliotek [Aspose.Slides](../../)