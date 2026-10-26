---
title: XslCompiledTransform
second_title: Aspose.Slides för C++ API-referens
description: Transformerar XML-data med en XSLT-stilmall.
type: docs
weight: 53
url: /sv/system.xml.xsl/xslcompiledtransform/
---
## XslCompiledTransform klass

Transformerar XML-data med en XSLT-stilmall.

```cpp
class XslCompiledTransform : public System::Object
```

## Metoder

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../../system.xml/xmlwritersettings/)\> [get_OutputSettings](./get_outputsettings/)() | Returnerar ett [XmlWriterSettings](../../system.xml/xmlwritersettings/)-objekt som innehåller utdatainformation hämtad från **xsl:output**-elementet i stilmallen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | Kompilerar stilmallen som finns i [XmlReader](../../system.xml/xmlreader/). |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | Kompilerar XSLT-stilmallen som finns i [XmlReader](../../system.xml/xmlreader/). [XmlResolver](../../system.xml/xmlresolver/) löser upp eventuella XSLT **import**- eller **include**-element och XSLT-inställningarna bestämmer behörigheterna för stilmallen. |
| void [Load](./load/)(const [String](../../system/string/)\&) | Läser in och kompilerar stilmallen som finns på den angivna URI:n. |
| void [Load](./load/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | Läser in och kompilerar den XSLT-stilmall som anges av URI:n. [XmlResolver](../../system.xml/xmlresolver/) löser upp eventuella XSLT **import**- eller **include**-element och XSLT-inställningarna bestämmer behörigheterna för stilmallen. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&) | Kompilerar stilmallen som finns i IXPathNavigable-objektet. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>) | Kompilerar XSLT-stilmallen som finns i IXPathNavigable. [XmlResolver](../../system.xml/xmlresolver/) löser upp eventuella XSLT **import**- eller **include**-element och XSLT-inställningarna bestämmer behörigheterna för stilmallen. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning för C# lock()-satser. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypobjekt med nullptr via referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in det n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i containrar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | Utför transformationen med indatat dokument som specificeras av IXPathNavigable-objektet och skriver resultaten till ett [XmlWriter](../../system.xml/xmlwriter/). |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | Utför transformationen med indatat dokument som specificeras av IXPathNavigable-objektet och skriver resultaten till ett [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körningsargument. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Utför transformationen med indatat dokument som specificeras av IXPathNavigable-objektet och skriver resultaten till en TextWriter. [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körningsargument. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Utför transformationen med indatat dokument som specificeras av IXPathNavigable-objektet och skriver resultaten till ett flöde. [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körningsargument. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | Utför transformationen med indatat dokument som specificeras av [XmlReader](../../system.xml/xmlreader/)-objektet och skriver resultaten till ett [XmlWriter](../../system.xml/xmlwriter/). |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | Utför transformationen med indatat dokument som specificeras av [XmlReader](../../system.xml/xmlreader/)-objektet och skriver resultaten till ett [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körningsargument. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Utför transformationen med indatat dokument som specificeras av [XmlReader](../../system.xml/xmlreader/)-objektet och skriver resultaten till en TextWriter. [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körningsargument. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Utför transformationen med indatat dokument som specificeras av [XmlReader](../../system.xml/xmlreader/)-objektet och skriver resultaten till ett flöde. [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körningsargument. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | Utför transformationen med indatat dokument som specificeras av URI:n och skriver resultaten till ett [XmlWriter](../../system.xml/xmlwriter/). |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | Utför transformationen med indatat dokument som specificeras av URI:n och skriver resultaten till ett [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körningsargument. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Utför transformationen med indatat dokument som specificeras av URI:n och skriver resultaten till en TextWriter. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Utför transformationen med indatat dokument som specificeras av URI:n och skriver resultaten till ett flöde. [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körningsargument. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Utför transformationen med indatat dokument som specificeras av URI:n och skriver resultaten till en fil. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | Utför transformationen med indatat dokument som specificeras av [XmlReader](../../system.xml/xmlreader/)-objektet och skriver resultaten till ett [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körningsargument och [XmlResolver](../../system.xml/xmlresolver/) löser XSLT **document()**-funktionen. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | Utför transformationen genom att använda indatat dokumentet som specificeras av IXPathNavigable-objektet och skriver resultaten till ett [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körningsargument och [XmlResolver](../../system.xml/xmlresolver/) löser XSLT **document()**-funktionen. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning för C# lock()-satser. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
|  [XslCompiledTransform](./xslcompiledtransform/)() | Initierar en ny instans av [XslCompiledTransform](./)-klassen. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Typdefinitioner

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |

## Anmärkningar

Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument. 

## Se också

* Klass [Object](../../system/object/)
* Namnrymd [System::Xml::Xsl](../)
* Bibliotek [Aspose.Slides](../../)