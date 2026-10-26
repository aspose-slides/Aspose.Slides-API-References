---
title: XmlSerializer
second_title: Aspose.Slides för C++ API-referens
description: "Utför serialisering och deserialisering av objekt till och från XML-dokument. Objekt av den här klassen bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Inlind alltid den här klassen i en System::SmartPtr-pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 66
url: /sv/system.xml.serialization/xmlserializer/
---
## XmlSerializer-klass

Utför serialisering och deserialisering av objekt till och från XML-dokument. Objekt av den här klassen bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertionsfel. Inlind alltid den här klassen i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class XmlSerializer : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [CanDeserialize](./candeserialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Kontrollerar om en specifik läsare är i ett deserialiserbart tillstånd. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | Deserialiserar XML-dokument till ett objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>) | Deserialiserar XML-dokument till ett objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Deserialiserar XML-dokument till ett objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>, [String](../../system/string/)) | Deserialiserar XML-dokument till ett objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska typen för objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Serialiserar dokument till XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Serialiserar dokument till XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Serialiserar dokument till XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>) | Serialiserar dokument till XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>) | Serialiserar dokument till XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>) | Serialiserar dokument till XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>, [String](../../system/string/)) | Serialiserar dokument till XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>, [String](../../system/string/), [String](../../system/string/)) | Serialiserar dokument till XML. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n-te template-argumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för den delade referensräknaren. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräknaren. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning med C# lock()-sats upphävd. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [EncodingNamespace](./encodingnamespace/) | Kodningsnamnrymdens namn. |
| static [WsdlNamespace](./wsdlnamespace/) | WSDL-namnområdets namn. |
| static [WsdlTypesNamespace](./wsdltypesnamespace/) | WSDL-typernas namnrymdsnamn. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [System::Xml::Serialization](../)
* Bibliotek [Aspose.Slides](../../)