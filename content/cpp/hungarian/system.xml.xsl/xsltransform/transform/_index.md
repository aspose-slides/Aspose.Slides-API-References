---
title: Transform()
second_title: Aspose.Slides C++ API Referencia
description: Az XPathNavigatorben lévő XML adatot a megadott args használatával alakítja át, és az eredményt egy XmlReader-be írja ki.
type: docs
weight: 40
url: /hu/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Az XPathNavigator-ben lévő XML adatot a megadott **args** használatával alakítja át, és az eredményt egy [XmlReader](../../../system.xml/xmlreader/)-ba írja ki.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Egy XPathNavigator, amely a transzformálandó adatot tartalmazza. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/), amely a névtérrel ellátott argumentumokat tartalmazza a transzformáció bemeneteként. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) a XSLT **document()** függvény feloldásához használt. Ha ez **nullptr**, a **document()** függvény nem kerül feloldásra. A [XmlResolver](../../../system.xml/xmlresolver/) nem kerül gyorsítótárazásra a metódus befejezése után. |

### Return Value

Egy [XmlReader](../../../system.xml/xmlreader/) a transzformáció eredményeivel.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) method


Az XPathNavigator-ben lévő XML adatot a megadott **args** használatával alakítja át, és az eredményt egy [XmlReader](../../../system.xml/xmlreader/)-ba írja ki.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Egy XPathNavigator, amely a transzformálandó adatot tartalmazza. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/), amely a névtérrel ellátott argumentumokat tartalmazza a transzformáció bemeneteként. |

### Return Value

Egy [XmlReader](../../../system.xml/xmlreader/) a transzformáció eredményeivel.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Az XPathNavigator-ben lévő XML adatot a megadott args használatával alakítja át, és az eredményt egy [XmlWriter](../../../system.xml/xmlwriter/)-ba írja ki.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Egy XPathNavigator, amely a transzformálandó adatot tartalmazza. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/), amely a névtérrel ellátott argumentumokat tartalmazza a transzformáció bemeneteként. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | A [XmlWriter](../../../system.xml/xmlwriter/), amelybe a kimenetet szeretné írni. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) a XSLT **document()** függvény feloldásához használt. Ha ez **nullptr**, a **document()** függvény nem kerül feloldásra. A [XmlResolver](../../../system.xml/xmlresolver/) nem kerül gyorsítótárazásra a metódus befejezése után. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Az XPathNavigator-ben lévő XML adatot a megadott args használatával alakítja át, és az eredményt egy [XmlWriter](../../../system.xml/xmlwriter/)-ba írja ki.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Egy XPathNavigator, amely a transzformálandó adatot tartalmazza. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/), amely a névtérrel ellátott argumentumokat tartalmazza a transzformáció bemeneteként. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | A [XmlWriter](../../../system.xml/xmlwriter/), amelybe a kimenetet szeretné írni. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Az XPathNavigator-ben lévő XML adatot a megadott **args** használatával alakítja át, és az eredményt egy Stream-be írja ki.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Egy XPathNavigator, amely a transzformálandó adatot tartalmazza. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/), amely a névtérrel ellátott argumentumokat tartalmazza a transzformáció bemeneteként. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | A stream, amelybe a kimenetet szeretné írni. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) a XSLT **document()** függvény feloldásához használt. Ha ez **nullptr**, a **document()** függvény nem kerül feloldásra. A [XmlResolver](../../../system.xml/xmlresolver/) nem kerül gyorsítótárazásra a metódus befejezése után. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Az XPathNavigator-ben lévő XML adatot a megadott **args** használatával alakítja át, és az eredményt egy Stream-be írja ki.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Egy XPathNavigator, amely a transzformálandó adatot tartalmazza. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/), amely a névtérrel ellátott argumentumokat tartalmazza a transzformáció bemeneteként. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | A stream, amelybe a kimenetet szeretné írni. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Az XPathNavigator-ben lévő XML adatot a megadott **args** használatával alakítja át, és az eredményt egy TextWriter-be írja ki.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Egy XPathNavigator, amely a transzformálandó adatot tartalmazza. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/), amely a névtérrel ellátott argumentumokat tartalmazza a transzformáció bemeneteként. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | A TextWriter, amelybe a kimenetet szeretné írni. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) a XSLT **document()** függvény feloldásához használt. Ha ez **nullptr**, a **document()** függvény nem kerül feloldásra. A [XmlResolver](../../../system.xml/xmlresolver/) nem kerül gyorsítótárazásra a metódus befejezése után. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Az XPathNavigator-ben lévő XML adatot a megadott **args** használatával alakítja át, és az eredményt egy TextWriter-be írja ki.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Egy XPathNavigator, amely a transzformálandó adatot tartalmazza. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/), amely a névtérrel ellátott argumentumokat tartalmazza a transzformáció bemeneteként. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | A TextWriter, amelybe a kimenetet szeretné írni. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Az IXPathNavigable-ban lévő XML adatot a megadott **args** használatával alakítja át, és az eredményt egy [XmlReader](../../../system.xml/xmlreader/)-ba írja ki.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Egy objektum, amely megvalósítja az IXPathNavigable interfészt. Lehet ez egy [XmlNode](../../../system.xml/xmlnode/) (általában egy [XmlDocument](../../../system.xml/xmldocument/)), vagy egy XPathDocument, amely a transzformálandó adatot tartalmazza. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/), amely a névtérrel ellátott argumentumokat tartalmazza a transzformáció bemeneteként. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) a XSLT **document()** függvény feloldásához használt. Ha ez **nullptr**, a **document()** függvény nem kerül feloldásra. A [XmlResolver](../../../system.xml/xmlresolver/) nem kerül gyorsítótárazásra a metódus befejezése után. |

### Return Value

Egy [XmlReader](../../../system.xml/xmlreader/) a transzformáció eredményeivel.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) method


Az IXPathNavigable-ban lévő XML adatot a megadott **args** használatával alakítja át, és az eredményt egy [XmlReader](../../../system.xml/xmlreader/)-ba írja ki.

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Egy objektum, amely megvalósítja az IXPathNavigable interfészt. Lehet ez egy [XmlNode](../../../system.xml/xmlnode/) (általában egy [XmlDocument](../../../system.xml/xmldocument/)), vagy egy XPathDocument, amely a transzformálandó adatot tartalmazza. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/), amely a névtérrel ellátott argumentumokat tartalmazza a transzformáció bemeneteként. |

### Return Value

Egy [XmlReader](../../../system.xml/xmlreader/) a transzformáció eredményeivel.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Az IXPathNavigable-ban lévő XML adatot a megadott **args** használatával alakítja át, és az eredményt egy TextWriter-be írja ki.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Egy objektum, amely megvalósítja az IXPathNavigable interfészt. Lehet ez egy [XmlNode](../../../system.xml/xmlnode/) (általában egy [XmlDocument](../../../system.xml/xmldocument/)), vagy egy XPathDocument, amely a transzformálandó adatot tartalmazza. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/), amely a névtérrel ellátott argumentumokat tartalmazza a transzformáció bemeneteként. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | A TextWriter, amelybe a kimenetet szeretné írni. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) a XSLT **document()** függvény feloldásához használt. Ha ez **nullptr**, a **document()** függvény nem kerül feloldásra. A [XmlResolver](../../../system.xml/xmlresolver/) nem kerül gyorsítótárazásra a metódus befejezése után. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Az IXPathNavigable-ban lévő XML adatot a megadott **args** használatával alakítja át, és az eredményt egy TextWriter-be írja ki.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Egy objektum, amely megvalósítja az IXPathNavigable interfészt. Lehet ez egy [XmlNode](../../../system.xml/xmlnode/) (általában egy [XmlDocument](../../../system.xml/xmldocument/)), vagy egy XPathDocument, amely a transzformálandó adatot tartalmazza. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/), amely a névtérrel ellátott argumentumokat tartalmazza a transzformáció bemeneteként. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | A TextWriter, amelybe a kimenetet szeretné írni. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Az IXPathNavigable-ban lévő XML adatot a megadott **args** használatával alakítja át, és az eredményt egy Stream-be írja ki.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Egy objektum, amely megvalósítja az IXPathNavigable interfészt. Lehet ez egy [XmlNode](../../../system.xml/xmlnode/) (általában egy [XmlDocument](../../../system.xml/xmldocument/)), vagy egy XPathDocument, amely a transzformálandó adatot tartalmazza. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/), amely a névtérrel ellátott argumentumokat tartalmazza a transzformáció bemeneteként. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | A stream, amelybe a kimenetet szeretné írni. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) a XSLT **document()** függvény feloldásához használt. Ha ez **nullptr**, a **document()** függvény nem kerül feloldásra. A [XmlResolver](../../../system.xml/xmlresolver/) nem kerül gyorsítótárazásra a [XslTransform::Transform](./) metódus befejezése után. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Az IXPathNavigable-ban lévő XML adatot a megadott **args** használatával alakítja át, és az eredményt egy Stream-be írja ki.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Egy objektum, amely megvalósítja az IXPathNavigable interfészt. Lehet ez egy [XmlNode](../../../system.xml/xmlnode/) (általában egy [XmlDocument](../../../system.xml/xmldocument/)), vagy egy XPathDocument, amely a transzformálandó adatot tartalmazza. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/), amely a névtérrel ellátott argumentumokat tartalmazza a transzformáció bemeneteként. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | A stream, amelybe a kimenetet szeretné írni. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Az IXPathNavigable-ban lévő XML adatot a megadott **args** használatával alakítja át, és az eredményt egy [XmlWriter](../../../system.xml/xmlwriter/)-ba írja ki.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Egy objektum, amely megvalósítja az IXPathNavigable interfészt. Lehet ez egy [XmlNode](../../../system.xml/xmlnode/) (általában egy [XmlDocument](../../../system.xml/xmldocument/)), vagy egy XPathDocument, amely a transzformálandó adatot tartalmazza. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/), amely a névtérrel ellátott argumentumokat tartalmazza a transzformáció bemeneteként. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | A [XmlWriter](../../../system.xml/xmlwriter/), amelybe a kimenetet szeretné írni. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) a XSLT **document()** függvény feloldásához használt. Ha ez **nullptr**, a **document()** függvény nem kerül feloldásra. A [XmlResolver](../../../system.xml/xmlresolver/) nem kerül gyorsítótárazásra a metódus befejezése után. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Az IXPathNavigable-ban lévő XML adatot a megadott **args** használatával alakítja át, és az eredményt egy [XmlWriter](../../../system.xml/xmlwriter/)-ba írja ki.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Egy objektum, amely megvalósítja az IXPathNavigable interfészt. Lehet ez egy [XmlNode](../../../system.xml/xmlnode/) (általában egy [XmlDocument](../../../system.xml/xmldocument/)), vagy egy XPathDocument, amely a transzformálandó adatot tartalmazza. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/), amely a névtérrel ellátott argumentumokat tartalmazza a transzformáció bemeneteként. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | A [XmlWriter](../../../system.xml/xmlwriter/), amelybe a kimenetet szeretné írni. |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Az bemeneti fájlban lévő XML adatot átalakítja, és az eredményt egy kimeneti fájlba írja.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | A forrásdokumentum URL-je, amelyet transzformálni kell. |
| outputfile | const [String](../../../system/string/)\& | A kimeneti fájl URL-je. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) a XSLT **document()** függvény feloldásához használt. Ha ez **nullptr**, a **document()** függvény nem kerül feloldásra. A [XmlResolver](../../../system.xml/xmlresolver/) nem kerül gyorsítótárazásra a [XslTransform::Transform](./) metódus befejezése után. |

## XslTransform::Transform(const String\&, const String\&) method


Az bemeneti fájlban lévő XML adatot átalakítja, és az eredményt egy kimeneti fájlba írja.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | A forrásdokumentum URL-je, amelyet transzformálni kell. |
| outputfile | const [String](../../../system/string/)\& | A kimeneti fájl URL-je. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)