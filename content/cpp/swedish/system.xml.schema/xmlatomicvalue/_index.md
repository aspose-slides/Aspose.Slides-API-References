---
title: XmlAtomicValue
second_title: Aspose.Slides för C++ API-referens
description: Representerar det typade värdet av ett validerat XML-element eller attribut. Klassen XmlAtomicValue kan inte ärvas.
type: docs
weight: 66
url: /sv/system.xml.schema/xmlatomicvalue/
---
## XmlAtomicValue klass

Representerar det typade värdet av ett validerat XML-element eller attribut. Klassen [XmlAtomicValue](./) kan inte ärvas.

```cpp
class XmlAtomicValue : public System::Xml::XPath::XPathItem
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlAtomicValue](./)\> [Clone](./clone/)() | Returnerar en kopia av detta [XmlAtomicValue](./)-objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| **bool** [get_IsNode](./get_isnode/)() override | Returnerar ett värde som indikerar om det validerade XML-elementet eller attributet är en [XPath](../../system.xml.xpath/)-nod eller ett atomärt värde. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | Returnerar det aktuella validerade XML-elementet eller attributet som ett inramat objekt av den mest lämpliga typen enligt dess schematyp. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Returnerar [String](../../system/string/)-värdet för det validerade XML-elementet eller attributet. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | Returnerar det validerade XML-elementets eller attributets värde som en [Boolean](../../system/boolean/). |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | Returnerar det validerade XML-elementets eller attributets värde som en [DateTime](../../system/datetime/). |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | Returnerar det validerade XML-elementets eller attributets värde som en [Double](../../system/double/). |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | Returnerar det validerade XML-elementets eller attributets värde som en [Int32](../../system/int32/). |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | Returnerar det validerade XML-elementets eller attributets värde som en [Int64](../../system/int64/). |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | Returnerar typen för det validerade XML-elementet eller attributet. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | Returnerar [XmlSchemaType](../xmlschematype/) för det validerade XML-elementet eller attributet. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-uttalandet. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktör. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypobjekt med nullptr via referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n:te mallargumentet till en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Returnerar [String](../../system/string/)-värdet för det validerade XML-elementet eller attributet. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning enligt C# lock()-uttalandet. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | Returnerar det validerade XML-elementet eller attributets värde som den typ som angivits med [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-objektet för att lösa namnrymdsprefix. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../../system.xml.xpath/xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | Returnerar objektets värde som den angivna typen. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |

## Anmärkningar



Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktion. Skapa aldrig instanser av denna typ på stacken eller med operator new, eftersom det kommer att resultera i körningsfel och/eller påståendefel. Omslut alltid denna klass med [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. 

## Se också

* Klass [XPathItem](../../system.xml.xpath/xpathitem/)
* Namnrymd [System::Xml::Schema](../)
* Bibliotek [Aspose.Slides](../../)