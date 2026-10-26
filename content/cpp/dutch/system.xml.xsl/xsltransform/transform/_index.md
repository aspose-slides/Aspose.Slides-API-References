---
title: Transform()
second_title: Aspose.Slides voor C++ API-referentie
description: Transformeert de XML-gegevens in de XPathNavigator met behulp van de opgegeven args en geeft het resultaat uit naar een XmlReader.
type: docs
weight: 40
url: /nl/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformeert de XML-gegevens in de XPathNavigator met behulp van de opgegeven **args** en geeft het resultaat uit naar een [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Een XPathNavigator die de te transformeren gegevens bevat. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) die de naamruimtegerelateerde argumenten bevat die als invoer voor de transformatie worden gebruikt. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om de XSLT **document()**-functie op te lossen. Als dit **nullptr** is, wordt de **document()**-functie niet opgelost. De [XmlResolver](../../../system.xml/xmlresolver/) wordt niet in de cache bewaard nadat deze methode is voltooid. |

### Retourwaarde

Een [XmlReader](../../../system.xml/xmlreader/) die de resultaten van de transformatie bevat.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) method

Transformeert de XML-gegevens in de XPathNavigator met behulp van de opgegeven **args** en geeft het resultaat uit naar een [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Een XPathNavigator die de te transformeren gegevens bevat. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) die de naamruimtegerelateerde argumenten bevat die als invoer voor de transformatie worden gebruikt. |

### Retourwaarde

Een [XmlReader](../../../system.xml/xmlreader/) die de resultaten van de transformatie bevat.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformeert de XML-gegevens in de XPathNavigator met behulp van de opgegeven args en geeft het resultaat uit naar een [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Een XPathNavigator die de te transformeren gegevens bevat. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) die de naamruimtegerelateerde argumenten bevat die als invoer voor de transformatie worden gebruikt. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | De [XmlWriter](../../../system.xml/xmlwriter/) waarin u wilt uitgeven. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om de XSLT **document()**-functie op te lossen. Als dit **nullptr** is, wordt de **document()**-functie niet opgelost. De [XmlResolver](../../../system.xml/xmlresolver/) wordt niet in de cache bewaard nadat deze methode is voltooid. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Transformeert de XML-gegevens in de XPathNavigator met behulp van de opgegeven args en geeft het resultaat uit naar een [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Een XPathNavigator die de te transformeren gegevens bevat. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) die de naamruimtegerelateerde argumenten bevat die als invoer voor de transformatie worden gebruikt. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | De [XmlWriter](../../../system.xml/xmlwriter/) waarin u wilt uitgeven. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformeert de XML-gegevens in de XPathNavigator met behulp van de opgegeven **args** en geeft het resultaat uit naar een Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Een XPathNavigator die de te transformeren gegevens bevat. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) die de naamruimtegerelateerde argumenten bevat die als invoer voor de transformatie worden gebruikt. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream waarin u wilt uitgeven. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om de XSLT **document()**-functie op te lossen. Als dit **nullptr** is, wordt de **document()**-functie niet opgelost. De [XmlResolver](../../../system.xml/xmlresolver/) wordt niet in de cache bewaard nadat deze methode is voltooid. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Transformeert de XML-gegevens in de XPathNavigator met behulp van de opgegeven **args** en geeft het resultaat uit naar een Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Een XPathNavigator die de te transformeren gegevens bevat. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) die de naamruimtegerelateerde argumenten bevat die als invoer voor de transformatie worden gebruikt. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream waarin u wilt uitgeven. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformeert de XML-gegevens in de XPathNavigator met behulp van de opgegeven **args** en geeft het resultaat uit naar een TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Een XPathNavigator die de te transformeren gegevens bevat. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) die de naamruimtegerelateerde argumenten bevat die als invoer voor de transformatie worden gebruikt. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | De TextWriter waarin u wilt uitgeven. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om de XSLT **document()**-functie op te lossen. Als dit **nullptr** is, wordt de **document()**-functie niet opgelost. De [XmlResolver](../../../system.xml/xmlresolver/) wordt niet in de cache bewaard nadat deze methode is voltooid. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Transformeert de XML-gegevens in de XPathNavigator met behulp van de opgegeven **args** en geeft het resultaat uit naar een TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Een XPathNavigator die de te transformeren gegevens bevat. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) die de naamruimtegerelateerde argumenten bevat die als invoer voor de transformatie worden gebruikt. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | De TextWriter waarin u wilt uitgeven. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformeert de XML-gegevens in de IXPathNavigable met behulp van de opgegeven **args** en geeft het resultaat uit naar een [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Een object dat de IXPathNavigable-interface implementeert. Het kan een [XmlNode](../../../system.xml/xmlnode/) (meestal een [XmlDocument](../../../system.xml/xmldocument/)) of een XPathDocument zijn die de te transformeren gegevens bevat. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) die de naamruimtegerelateerde argumenten bevat die als invoer voor de transformatie worden gebruikt. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om de XSLT **document()**-functie op te lossen. Als dit **nullptr** is, wordt de **document()**-functie niet opgelost. De [XmlResolver](../../../system.xml/xmlresolver/) wordt niet in de cache bewaard nadat deze methode is voltooid. |

### Retourwaarde

Een [XmlReader](../../../system.xml/xmlreader/) die de resultaten van de transformatie bevat.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) method

Transformeert de XML-gegevens in de IXPathNavigable met behulp van de opgegeven **args** en geeft het resultaat uit naar een [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Een object dat de IXPathNavigable-interface implementeert. Het kan een [XmlNode](../../../system.xml/xmlnode/) (meestal een [XmlDocument](../../../system.xml/xmldocument/)) of een XPathDocument zijn die de te transformeren gegevens bevat. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) die de naamruimtegerelateerde argumenten bevat die als invoer voor de transformatie worden gebruikt. |

### Retourwaarde

Een [XmlReader](../../../system.xml/xmlreader/) die de resultaten van de transformatie bevat.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformeert de XML-gegevens in de IXPathNavigable met behulp van de opgegeven **args** en geeft het resultaat uit naar een TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Een object dat de IXPathNavigable-interface implementeert. Het kan een [XmlNode](../../../system.xml/xmlnode/) (meestal een [XmlDocument](../../../system.xml/xmldocument/)) of een XPathDocument zijn die de te transformeren gegevens bevat. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) die de naamruimtegerelateerde argumenten bevat die als invoer voor de transformatie worden gebruikt. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | De TextWriter waarin u wilt uitgeven. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om de XSLT **document()**-functie op te lossen. Als dit **nullptr** is, wordt de **document()**-functie niet opgelost. De [XmlResolver](../../../system.xml/xmlresolver/) wordt niet in de cache bewaard nadat deze methode is voltooid. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Transformeert de XML-gegevens in de IXPathNavigable met behulp van de opgegeven **args** en geeft het resultaat uit naar een TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Een object dat de IXPathNavigable-interface implementeert. Het kan een [XmlNode](../../../system.xml/xmlnode/) (meestal een [XmlDocument](../../../system.xml/xmldocument/)) of een XPathDocument zijn die de te transformeren gegevens bevat. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) die de naamruimtegerelateerde argumenten bevat die als invoer voor de transformatie worden gebruikt. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | De TextWriter waarin u wilt uitgeven. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformeert de XML-gegevens in de IXPathNavigable met behulp van de opgegeven **args** en geeft het resultaat uit naar een Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Een object dat de IXPathNavigable-interface implementeert. Het kan een [XmlNode](../../../system.xml/xmlnode/) (meestal een [XmlDocument](../../../system.xml/xmldocument/)) of een XPathDocument zijn die de te transformeren gegevens bevat. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) die de naamruimtegerelateerde argumenten bevat die als invoer voor de transformatie worden gebruikt. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream waarin u wilt uitgeven. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om de XSLT **document()**-functie op te lossen. Als dit **nullptr** is, wordt de **document()**-functie niet opgelost. De [XmlResolver](../../../system.xml/xmlresolver/) wordt niet in de cache bewaard nadat de [XslTransform::Transform](./)-methode is voltooid. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Transformeert de XML-gegevens in de IXPathNavigable met behulp van de opgegeven **args** en geeft het resultaat uit naar een Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Een object dat de IXPathNavigable-interface implementeert. Het kan een [XmlNode](../../../system.xml/xmlnode/) (meestal een [XmlDocument](../../../system.xml/xmldocument/)) of een XPathDocument zijn die de te transformeren gegevens bevat. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) die de naamruimtegerelateerde argumenten bevat die als invoer voor de transformatie worden gebruikt. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream waarin u wilt uitgeven. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformeert de XML-gegevens in de IXPathNavigable met behulp van de opgegeven **args** en geeft het resultaat uit naar een [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Een object dat de IXPathNavigable-interface implementeert. Het kan een [XmlNode](../../../system.xml/xmlnode/) (meestal een [XmlDocument](../../../system.xml/xmldocument/)) of een XPathDocument zijn die de te transformeren gegevens bevat. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) die de naamruimtegerelateerde argumenten bevat die als invoer voor de transformatie worden gebruikt. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | De [XmlWriter](../../../system.xml/xmlwriter/) waarin u wilt uitgeven. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om de XSLT **document()**-functie op te lossen. Als dit **nullptr** is, wordt de **document()**-functie niet opgelost. De [XmlResolver](../../../system.xml/xmlresolver/) wordt niet in de cache bewaard nadat deze methode is voltooid. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Transformeert de XML-gegevens in de IXPathNavigable met behulp van de opgegeven **args** en geeft het resultaat uit naar een [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Een object dat de IXPathNavigable-interface implementeert. Het kan een [XmlNode](../../../system.xml/xmlnode/) (meestal een [XmlDocument](../../../system.xml/xmldocument/)) of een XPathDocument zijn die de te transformeren gegevens bevat. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) die de naamruimtegerelateerde argumenten bevat die als invoer voor de transformatie worden gebruikt. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | De [XmlWriter](../../../system.xml/xmlwriter/) waarin u wilt uitgeven. |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformeert de XML-gegevens in het invoerbestand en geeft het resultaat uit naar een uitvoerbestand.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | De URL van het bron-document dat moet worden getransformeerd. |
| outputfile | const [String](../../../system/string/)\& | De URL van het uitvoerbestand. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om de XSLT **document()**-functie op te lossen. Als dit **nullptr** is, wordt de **document()**-functie niet opgelost. De [XmlResolver](../../../system.xml/xmlresolver/) wordt niet in de cache bewaard nadat de [XslTransform::Transform](./)-methode is voltooid. |

## XslTransform::Transform(const String\&, const String\&) method

Transformeert de XML-gegevens in het invoerbestand en geeft het resultaat uit naar een uitvoerbestand.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | De URL van het bron-document dat moet worden getransformeerd. |
| outputfile | const [String](../../../system/string/)\& | De URL van het uitvoerbestand. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Klasse [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Klasse [XsltArgumentList](../../xsltargumentlist/)
* Klasse [XmlResolver](../../../system.xml/xmlresolver/)
* Klasse [XslTransform](../)
* Klasse [XmlWriter](../../../system.xml/xmlwriter/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [TextWriter](../../../system.io/textwriter/)
* Klasse [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Xml::Xsl](../../)
* Bibliotheek [Aspose.Slides](../../../)