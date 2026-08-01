---
title: Transform()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert de transformatie uit met behulp van het invoerdocument dat is opgegeven door het IXPathNavigable-object en schrijft de resultaten naar een XmlWriter.
type: docs
weight: 40
url: /nl/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) methode

Voert de transformatie uit met behulp van het invoerdocument dat is opgegeven door het IXPathNavigable-object en schrijft de resultaten naar een [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Een object dat de IXPathNavigable-interface implementeert. Het kan een [XmlNode](../../../system.xml/xmlnode/) zijn (meestal een [XmlDocument](../../../system.xml/xmldocument/)), of een XPathDocument dat de te transformeren gegevens bevat. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | De [XmlWriter](../../../system.xml/xmlwriter/) waarnaar u wilt schrijven. Als het stijlsjabloon een **xsl:output**-element bevat, moet u de [XmlWriter](../../../system.xml/xmlwriter/) maken met het [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-object dat wordt geretourneerd vanuit de [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-waarde. Dit zorgt ervoor dat de [XmlWriter](../../../system.xml/xmlwriter/) de juiste uitvoerinstellingen heeft. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) methode

Voert de transformatie uit met behulp van het invoerdocument dat is opgegeven door het IXPathNavigable-object en schrijft de resultaten naar een [XmlWriter](../../../system.xml/xmlwriter/). De [XsltArgumentList](../../xsltargumentlist/) biedt extra runtime-argumenten.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Een object dat de IXPathNavigable-interface implementeert. Het kan een [XmlNode](../../../system.xml/xmlnode/) zijn (meestal een [XmlDocument](../../../system.xml/xmldocument/)), of een XPathDocument dat de te transformeren gegevens bevat. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) met de namespace-gekwalificeerde argumenten die als invoer voor de transformatie worden gebruikt. Deze waarde kan **nullptr** zijn. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | De [XmlWriter](../../../system.xml/xmlwriter/) waarnaar u wilt schrijven. Als het stijlsjabloon een **xsl:output**-element bevat, moet u de [XmlWriter](../../../system.xml/xmlwriter/) maken met het [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-object dat wordt geretourneerd vanuit de [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-waarde. Dit zorgt ervoor dat de [XmlWriter](../../../system.xml/xmlwriter/) de juiste uitvoerinstellingen heeft. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) methode

Voert de transformatie uit met behulp van het invoerdocument dat is opgegeven door het IXPathNavigable-object en schrijft de resultaten naar een TextWriter. De [XsltArgumentList](../../xsltargumentlist/) biedt extra runtime-argumenten.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Een object dat de IXPathNavigable-interface implementeert. Het kan een [XmlNode](../../../system.xml/xmlnode/) zijn (meestal een [XmlDocument](../../../system.xml/xmldocument/)), of een XPathDocument dat de te transformeren gegevens bevat. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) met de namespace-gekwalificeerde argumenten die als invoer voor de transformatie worden gebruikt. Deze waarde kan **nullptr** zijn. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | De TextWriter waarnaar u wilt schrijven. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) methode

Voert de transformatie uit met behulp van het invoerdocument dat is opgegeven door het IXPathNavigable-object en schrijft de resultaten naar een stream. De [XsltArgumentList](../../xsltargumentlist/) biedt extra runtime-argumenten.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Een object dat de IXPathNavigable-interface implementeert. Het kan een [XmlNode](../../../system.xml/xmlnode/) zijn (meestal een [XmlDocument](../../../system.xml/xmldocument/)), of een XPathDocument dat de te transformeren gegevens bevat. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) met de namespace-gekwalificeerde argumenten die als invoer voor de transformatie worden gebruikt. Deze waarde kan **nullptr** zijn. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream waarnaar u wilt schrijven. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) methode

Voert de transformatie uit met behulp van het invoerdocument dat is opgegeven door het [XmlReader](../../../system.xml/xmlreader/)-object en schrijft de resultaten naar een [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | De [XmlReader](../../../system.xml/xmlreader/) die het invoerdocument bevat. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | De [XmlWriter](../../../system.xml/xmlwriter/) waarnaar u wilt schrijven. Als het stijlsjabloon een **xsl:output**-element bevat, moet u de [XmlWriter](../../../system.xml/xmlwriter/) maken met het [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-object dat wordt geretourneerd vanuit de [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-waarde. Dit zorgt ervoor dat de [XmlWriter](../../../system.xml/xmlwriter/) de juiste uitvoerinstellingen heeft. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) methode

Voert de transformatie uit met behulp van het invoerdocument dat is opgegeven door het [XmlReader](../../../system.xml/xmlreader/)-object en schrijft de resultaten naar een [XmlWriter](../../../system.xml/xmlwriter/). De [XsltArgumentList](../../xsltargumentlist/) biedt extra runtime-argumenten.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Een [XmlReader](../../../system.xml/xmlreader/) die het invoerdocument bevat. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) met de namespace-gekwalificeerde argumenten die als invoer voor de transformatie worden gebruikt. Deze waarde kan **nullptr** zijn. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | De [XmlWriter](../../../system.xml/xmlwriter/) waarnaar u wilt schrijven. Als het stijlsjabloon een **xsl:output**-element bevat, moet u de [XmlWriter](../../../system.xml/xmlwriter/) maken met het [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-object dat wordt geretourneerd vanuit de [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-waarde. Dit zorgt ervoor dat de [XmlWriter](../../../system.xml/xmlwriter/) de juiste uitvoerinstellingen heeft. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) methode

Voert de transformatie uit met behulp van het invoerdocument dat is opgegeven door het [XmlReader](../../../system.xml/xmlreader/)-object en schrijft de resultaten naar een TextWriter. De [XsltArgumentList](../../xsltargumentlist/) biedt extra runtime-argumenten.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Een [XmlReader](../../../system.xml/xmlreader/) die het invoerdocument bevat. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) met de namespace-gekwalificeerde argumenten die als invoer voor de transformatie worden gebruikt. Deze waarde kan **nullptr** zijn. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | De TextWriter waarnaar u wilt schrijven. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) methode

Voert de transformatie uit met behulp van het invoerdocument dat is opgegeven door het [XmlReader](../../../system.xml/xmlreader/)-object en schrijft de resultaten naar een stream. De [XsltArgumentList](../../xsltargumentlist/) biedt extra runtime-argumenten.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Een [XmlReader](../../../system.xml/xmlreader/) die het invoerdocument bevat. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) met de namespace-gekwalificeerde argumenten die als invoer voor de transformatie worden gebruikt. Deze waarde kan **nullptr** zijn. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream waarnaar u wilt schrijven. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) methode

Voert de transformatie uit met behulp van het invoerdocument dat is opgegeven door de URI en schrijft de resultaten naar een [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | De URI van het invoerdocument. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | De [XmlWriter](../../../system.xml/xmlwriter/) waarnaar u wilt schrijven. Als het stijlsjabloon een **xsl:output**-element bevat, moet u de [XmlWriter](../../../system.xml/xmlwriter/) maken met het [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-object dat wordt geretourneerd vanuit de [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-waarde. Dit zorgt ervoor dat de [XmlWriter](../../../system.xml/xmlwriter/) de juiste uitvoerinstellingen heeft. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) methode

Voert de transformatie uit met behulp van het invoerdocument dat is opgegeven door de URI en schrijft de resultaten naar een [XmlWriter](../../../system.xml/xmlwriter/). De [XsltArgumentList](../../xsltargumentlist/) biedt extra runtime-argumenten.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | De URI van het invoerdocument. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) met de namespace-gekwalificeerde argumenten die als invoer voor de transformatie worden gebruikt. Deze waarde kan **nullptr** zijn. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | De [XmlWriter](../../../system.xml/xmlwriter/) waarnaar u wilt schrijven. Als het stijlsjabloon een **xsl:output**-element bevat, moet u de [XmlWriter](../../../system.xml/xmlwriter/) maken met het [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-object dat wordt geretourneerd vanuit de [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-waarde. Dit zorgt ervoor dat de [XmlWriter](../../../system.xml/xmlwriter/) de juiste uitvoerinstellingen heeft. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) methode

Voert de transformatie uit met behulp van het invoerdocument dat is opgegeven door de URI en schrijft de resultaten naar een TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | De URI van het invoerdocument. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) met de namespace-gekwalificeerde argumenten die als invoer voor de transformatie worden gebruikt. Deze waarde kan **nullptr** zijn. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | De TextWriter waarnaar u wilt schrijven. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) methode

Voert de transformatie uit met behulp van het invoerdocument dat is opgegeven door de URI en schrijft de resultaten naar een stream. De [XsltArgumentList](../../xsltargumentlist/) biedt extra runtime-argumenten.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | De URI van het invoerdocument. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) met de namespace-gekwalificeerde argumenten die als invoer voor de transformatie worden gebruikt. Deze waarde kan **nullptr** zijn. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream waarnaar u wilt schrijven. |

## XslCompiledTransform::Transform(const String\&, const String\&) methode

Voert de transformatie uit met behulp van het invoerdocument dat is opgegeven door de URI en schrijft de resultaten naar een bestand.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | De URI van het invoerdocument. |
| resultsFile | const [String](../../../system/string/)\& | De URI van het uitvoerbestand. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) methode

Voert de transformatie uit met behulp van het invoerdocument dat is opgegeven door het [XmlReader](../../../system.xml/xmlreader/)-object en schrijft de resultaten naar een [XmlWriter](../../../system.xml/xmlwriter/). De [XsltArgumentList](../../xsltargumentlist/) biedt extra runtime-argumenten en de [XmlResolver](../../../system.xml/xmlresolver/) lost de XSLT **document()**-functie op.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Een [XmlReader](../../../system.xml/xmlreader/) die het invoerdocument bevat. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Een [XsltArgumentList](../../xsltargumentlist/) met de namespace-gekwalificeerde argumenten die als invoer voor de transformatie worden gebruikt. Deze waarde kan **nullptr** zijn. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | De [XmlWriter](../../../system.xml/xmlwriter/) waarnaar u wilt schrijven. Als het stijlsjabloon een **xsl:output**-element bevat, moet u de [XmlWriter](../../../system.xml/xmlwriter/) maken met het [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-object dat wordt geretourneerd vanuit de [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-waarde. Dit zorgt ervoor dat de [XmlWriter](../../../system.xml/xmlwriter/) de juiste uitvoerinstellingen heeft. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om de XSLT **document()**-functie op te lossen. Als dit **nullptr** is, wordt de **document()**-functie niet opgelost. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) methode

Voert de transformatie uit met behulp van het invoerdocument dat is opgegeven door het IXPathNavigable-object en schrijft de resultaten naar een [XmlWriter](../../../system.xml/xmlwriter/). De [XsltArgumentList](../../xsltargumentlist/) biedt extra runtime-argumenten en de [XmlResolver](../../../system.xml/xmlresolver/) lost de XSLT **document()**-functie op.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Het document dat moet worden getransformeerd, opgegeven door het IXPathNavigable-object. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Argumentenlijst als [XsltArgumentList](../../xsltargumentlist/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | De [XmlWriter](../../../system.xml/xmlwriter/) waarnaar u wilt schrijven. Als het stijlsjabloon een **xsl:output**-element bevat, moet u de [XmlWriter](../../../system.xml/xmlwriter/) maken met het [XmlWriterSettings](../../../system.xml/xmlwritersettings/)-object dat wordt geretourneerd vanuit de [XslCompiledTransform::get_OutputSettings](../get_outputsettings/)-waarde. Dit zorgt ervoor dat de [XmlWriter](../../../system.xml/xmlwriter/) de juiste uitvoerinstellingen heeft. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om de XSLT **document()**-functie op te lossen. Als dit **nullptr** is, wordt de **document()**-functie niet opgelost. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Klasse [XmlWriter](../../../system.xml/xmlwriter/)
* Klasse [XslCompiledTransform](../)
* Klasse [XsltArgumentList](../../xsltargumentlist/)
* Klasse [TextWriter](../../../system.io/textwriter/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Klasse [String](../../../system/string/)
* Klasse [XmlResolver](../../../system.xml/xmlresolver/)
* namespace [System::Xml::Xsl](../../)
* Bibliotheek [Aspose.Slides](../../../)