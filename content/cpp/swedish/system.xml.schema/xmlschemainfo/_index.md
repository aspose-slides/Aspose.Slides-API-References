---
title: XmlSchemaInfo
second_title: Aspose.Slides för C++ API-referens
description: Representerar post-schema-valideringsinfosett för en validerad XML-nod.
type: docs
weight: 521
url: /sv/system.xml.schema/xmlschemainfo/
---
## XmlSchemaInfo klass


Representerar post-schema-validerings-infosettet för en validerad XML-nod.

```cpp
class XmlSchemaInfo : public System::Xml::Schema::IXmlSchemaInfo
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [XmlSchemaContentType](../xmlschemacontenttype/) [get_ContentType](./get_contenttype/)() | Returnerar XmlSchemaContentType-objektet som motsvarar innehållstypen för denna validerade XML-nod. |
| **bool** [get_IsDefault](./get_isdefault/)() override | Returnerar ett värde som indikerar om denna validerade XML-nod sattes som resultat av ett standardvärde som tillämpades under XML [Schema](../) Definition Language (XSD) schemavalidering. |
| **bool** [get_IsNil](./get_isnil/)() override | Returnerar ett värde som indikerar om värdet för denna validerade XML-nod är **nil**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_MemberType](./get_membertype/)() override | Returnerar den dynamiska schematypen för denna validerade XML-nod. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\> [get_SchemaAttribute](./get_schemaattribute/)() override | Returnerar det kompilerade [XmlSchemaAttribute](../xmlschemaattribute/)-objektet som motsvarar denna validerade XML-nod. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaElement](../xmlschemaelement/)\> [get_SchemaElement](./get_schemaelement/)() override | Returnerar det kompilerade [XmlSchemaElement](../xmlschemaelement/)-objektet som motsvarar denna validerade XML-nod. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() override | Returnerar den statiska XML [Schema](../) Definition Language (XSD) schematypen för denna validerade XML-nod. |
| [XmlSchemaValidity](../xmlschemavalidity/) [get_Validity](./get_validity/)() override | Returnerar XmlSchemaValidity-värdet för denna validerade XML-nod. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknar-datastrukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vakt-objekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_ContentType](./set_contenttype/)([XmlSchemaContentType](../xmlschemacontenttype/)) | Ställer in XmlSchemaContentType-objektet som motsvarar innehållstypen för denna validerade XML-nod. |
| void [set_IsDefault](./set_isdefault/)(**bool**) | Ställer in ett värde som indikerar om denna validerade XML-nod sattes som resultat av ett standardvärde som tillämpades under XML [Schema](../) Definition Language (XSD) schemavalidering. |
| void [set_IsNil](./set_isnil/)(**bool**) | Ställer in ett värde som indikerar om värdet för denna validerade XML-nod är **nil**. |
| void [set_MemberType](./set_membertype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\>\&) | Ställer in den dynamiska schematypen för denna validerade XML-nod. |
| void [set_SchemaAttribute](./set_schemaattribute/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\>\&) | Ställer in det kompilerade [XmlSchemaAttribute](../xmlschemaattribute/)-objektet som motsvarar denna validerade XML-nod. |
| void [set_SchemaElement](./set_schemaelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaElement](../xmlschemaelement/)\>\&) | Ställer in det kompilerade [XmlSchemaElement](../xmlschemaelement/)-objektet som motsvarar denna validerade XML-nod. |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | Ställer in den statiska XML [Schema](../) Definition Language (XSD) schematypen för denna validerade XML-nod. |
| void [set_Validity](./set_validity/)([XmlSchemaValidity](../xmlschemavalidity/)) | Ställer in XmlSchemaValidity-värdet för denna validerade XML-nod. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i containrar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar nuvarande värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vakt-objekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
|  [XmlSchemaInfo](./xmlschemainfo/)() | Initierar en ny instans av [XmlSchemaInfo](./)-klassen. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Typdefinitioner

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för delad pekare till en instans av denna klass. |

## Anmärkningar

Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körningstidfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument. 

## Se även

* Klass [IXmlSchemaInfo](../ixmlschemainfo/)
* Namnrymd [System::Xml::Schema](../)
* Bibliotek [Aspose.Slides](../../)