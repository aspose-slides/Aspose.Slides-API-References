---
title: XmlSchemaParticle
second_title: Aspose.Slides för C++ API-referens
description: En basklass för detta är basklassen för alla partikeltyper (t.ex. XmlSchemaAny).
type: docs
weight: 729
url: /sv/system.xml.schema/xmlschemaparticle/
---
## XmlSchemaParticle klass


En basklass för detta är basklassen för alla partikeltyper (t.ex. [XmlSchemaAny](../xmlschemaany/)).

```cpp
class XmlSchemaParticle : public System::Xml::Schema::XmlSchemaAnnotated
```

## Metoder

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Returnerar egenskapen **annotation**. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Returnerar sträng-id. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Returnerar radnumret i filen som **schema**-elementet hänvisar till. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Returnerar radpositionen i filen som **schema**-elementet hänvisar till. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](./get_maxoccurs/)() | Returnerar det maximala antalet gånger partikeln kan förekomma. |
| [String](../../system/string/) [get_MaxOccursString](./get_maxoccursstring/)() | Returnerar talet som ett strängvärde. Maximalt antal gånger partikeln kan förekomma. |
| [Decimal](../../system/decimal/) [get_MinOccurs](./get_minoccurs/)() | Returnerar det minsta antalet gånger partikeln kan förekomma. |
| [String](../../system/string/) [get_MinOccursString](./get_minoccursstring/)() | Returnerar talet som ett strängvärde. Det minsta antalet gånger partikeln kan förekomma. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Returnerar XmlSerializerNamespaces som ska användas med detta schemaobjekt. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Returnerar föräldern till detta [XmlSchemaObject](../xmlschemaobject/). |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Returnerar källplatsen för filen som laddade schemat. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Returnerar de kvalificerade attributen som inte tillhör det aktuella schemets mål-namnrymd. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenskontörsdatastrukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Gör det möjligt att hash-värdera anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Gör det möjligt att klona anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Sätter egenskapen **annotation**. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Sätter sträng-id. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Sätter radnumret i filen som **schema**-elementet hänvisar till. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Sätter radpositionen i filen som **schema**-elementet hänvisar till. |
| void [set_MaxOccurs](./set_maxoccurs/)([Decimal](../../system/decimal/)) | Sätter det maximala antalet gånger partikeln kan förekomma. |
| void [set_MaxOccursString](./set_maxoccursstring/)(const [String](../../system/string/)\&) | Sätter talet som ett strängvärde. Maximalt antal gånger partikeln kan förekomma. |
| void [set_MinOccurs](./set_minoccurs/)([Decimal](../../system/decimal/)) | Sätter det minsta antalet gånger partikeln kan förekomma. |
| void [set_MinOccursString](./set_minoccursstring/)(const [String](../../system/string/)\&) | Sätter talet som ett strängvärde. Det minsta antalet gånger partikeln kan förekomma. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Sätter XmlSerializerNamespaces som ska användas med detta schemaobjekt. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Sätter föräldern till detta [XmlSchemaObject](../xmlschemaobject/). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Sätter källplatsen för filen som laddade schemat. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Sätter de kvalificerade attributen som inte tillhör det aktuella schemets mål-namnrymd. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n:te mall-argumentet till en weak-pekare (istället för en shared). Tillåter att byta pekare i behållare till weak-läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Gör det möjligt att konvertera anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar weak-referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar weak-referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initierar en ny instans av klassen [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaParticle](./xmlschemaparticle/)() | Initierar en ny instans av klassen [XmlSchemaParticle](./). |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigerar alla interna datastrukturer. |

## Typdefinitioner

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för smart pekare till en instans av denna klass. |

## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert-fel. Se alltid till att omsluta denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. 

## Se även

* Klass [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namnrymd [System::Xml::Schema](../)
* Bibliotek [Aspose.Slides](../../)