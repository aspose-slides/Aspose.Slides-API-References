---
title: Transform()
second_title: Aspose.Slides pro C++ API referenci
description: Transformuje XML data v XPathNavigator pomocí zadaných args a výsledek uloží do XmlReaderu.
type: docs
weight: 40
url: /cs/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformuje XML data v objektu XPathNavigator pomocí zadaných **args** a výsledek uloží do [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XPathNavigator obsahující data k transformaci. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) používaný k vyřešení funkce XSLT **document()**. Pokud je **nullptr**, funkce **document()** není vyřešena. [XmlResolver](../../../system.xml/xmlresolver/) není po dokončení této metody uloženo do mezipaměti. |

### Návratová hodnota

[XmlReader](../../../system.xml/xmlreader/) obsahující výsledky transformace.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) method

Transformuje XML data v objektu XPathNavigator pomocí zadaných **args** a výsledek uloží do [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XPathNavigator obsahující data k transformaci. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. |

### Návratová hodnota

[XmlReader](../../../system.xml/xmlreader/) obsahující výsledky transformace.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformuje XML data v objektu XPathNavigator pomocí zadaných **args** a výsledek uloží do [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XPathNavigator obsahující data k transformaci. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), do které chcete výstup zapisovat. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) používaný k vyřešení funkce XSLT **document()**. Pokud je **nullptr**, funkce **document()** není vyřešena. [XmlResolver](../../../system.xml/xmlresolver/) není po dokončení této metody uloženo do mezipaměti. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Transformuje XML data v objektu XPathNavigator pomocí zadaných **args** a výsledek uloží do [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XPathNavigator obsahující data k transformaci. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), do které chcete výstup zapisovat. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformuje XML data v objektu XPathNavigator pomocí zadaných **args** a výsledek uloží do Streamu.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XPathNavigator obsahující data k transformaci. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream, do kterého chcete výstup zapisovat. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) používaný k vyřešení funkce XSLT **document()**. Pokud je **nullptr**, funkce **document()** není vyřešena. [XmlResolver](../../../system.xml/xmlresolver/) není po dokončení této metody uloženo do mezipaměti. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Transformuje XML data v objektu XPathNavigator pomocí zadaných **args** a výsledek uloží do Streamu.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XPathNavigator obsahující data k transformaci. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream, do kterého chcete výstup zapisovat. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformuje XML data v objektu XPathNavigator pomocí zadaných **args** a výsledek uloží do TextWriteru.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XPathNavigator obsahující data k transformaci. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do kterého chcete výstup zapisovat. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) používaný k vyřešení funkce XSLT **document()**. Pokud je **nullptr**, funkce **document()** není vyřešena. [XmlResolver](../../../system.xml/xmlresolver/) není po dokončení této metody uloženo do mezipaměti. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Transformuje XML data v objektu XPathNavigator pomocí zadaných **args** a výsledek uloží do TextWriteru.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XPathNavigator obsahující data k transformaci. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do kterého chcete výstup zapisovat. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformuje XML data v objektu IXPathNavigable pomocí zadaných **args** a výsledek uloží do [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objekt implementující rozhraní IXPathNavigable. Může to být buď [XmlNode](../../../system.xml/xmlnode/) (typicky [XmlDocument](../../../system.xml/xmldocument/)), nebo XPathDocument obsahující data k transformaci. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) používaný k vyřešení funkce XSLT **document()**. Pokud je **nullptr**, funkce **document()** není vyřešena. [XmlResolver](../../../system.xml/xmlresolver/) není po dokončení této metody uloženo do mezipaměti. |

### Návratová hodnota

[XmlReader](../../../system.xml/xmlreader/) obsahující výsledky transformace.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) method

Transformuje XML data v objektu IXPathNavigable pomocí zadaných **args** a výsledek uloží do [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objekt implementující rozhraní IXPathNavigable. Může to být buď [XmlNode](../../../system.xml/xmlnode/) (typicky [XmlDocument](../../../system.xml/xmldocument/)), nebo XPathDocument obsahující data k transformaci. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. |

### Návratová hodnota

[XmlReader](../../../system.xml/xmlreader/) obsahující výsledky transformace.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformuje XML data v objektu IXPathNavigable pomocí zadaných **args** a výsledek uloží do TextWriteru.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objekt implementující rozhraní IXPathNavigable. Může to být buď [XmlNode](../../../system.xml/xmlnode/) (typicky [XmlDocument](../../../system.xml/xmldocument/)), nebo XPathDocument obsahující data k transformaci. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do kterého chcete výstup zapisovat. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) používaný k vyřešení funkce XSLT **document()**. Pokud je **nullptr**, funkce **document()** není vyřešena. [XmlResolver](../../../system.xml/xmlresolver/) není po dokončení této metody uloženo do mezipaměti. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Transformuje XML data v objektu IXPathNavigable pomocí zadaných **args** a výsledek uloží do TextWriteru.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objekt implementující rozhraní IXPathNavigable. Může to být buď [XmlNode](../../../system.xml/xmlnode/) (typicky [XmlDocument](../../../system.xml/xmldocument/)), nebo XPathDocument obsahující data k transformaci. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do kterého chcete výstup zapisovat. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformuje XML data v objektu IXPathNavigable pomocí zadaných **args** a výsledek uloží do Streamu.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objekt implementující rozhraní IXPathNavigable. Může to být buď [XmlNode](../../../system.xml/xmlnode/) (typicky [XmlDocument](../../../system.xml/xmldocument/)), nebo XPathDocument obsahující data k transformaci. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream, do kterého chcete výstup zapisovat. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) používaný k vyřešení funkce XSLT **document()**. Pokud je **nullptr**, funkce **document()** není vyřešena. [XmlResolver](../../../system.xml/xmlresolver/) není po dokončení [XslTransform::Transform](./) metody uloženo do mezipaměti. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Transformuje XML data v objektu IXPathNavigable pomocí zadaných **args** a výsledek uloží do Streamu.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objekt implementující rozhraní IXPathNavigable. Může to být buď [XmlNode](../../../system.xml/xmlnode/) (typicky [XmlDocument](../../../system.xml/xmldocument/)), nebo XPathDocument obsahující data k transformaci. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream, do kterého chcete výstup zapisovat. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformuje XML data v objektu IXPathNavigable pomocí zadaných **args** a výsledek uloží do [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objekt implementující rozhraní IXPathNavigable. Může to být buď [XmlNode](../../../system.xml/xmlnode/) (typicky [XmlDocument](../../../system.xml/xmldocument/)), nebo XPathDocument obsahující data k transformaci. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), do které chcete výstup zapisovat. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) používaný k vyřešení funkce XSLT **document()**. Pokud je **nullptr**, funkce **document()** není vyřešena. [XmlResolver](../../../system.xml/xmlresolver/) není po dokončení této metody uloženo do mezipaměti. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Transformuje XML data v objektu IXPathNavigable pomocí zadaných **args** a výsledek uloží do [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objekt implementující rozhraní IXPathNavigable. Může to být buď [XmlNode](../../../system.xml/xmlnode/) (typicky [XmlDocument](../../../system.xml/xmldocument/)), nebo XPathDocument obsahující data k transformaci. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), do které chcete výstup zapisovat. |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transformuje XML data v vstupním souboru a výsledek uloží do výstupního souboru.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | URL zdrojového dokumentu, který má být transformován. |
| outputfile | const [String](../../../system/string/)\& | URL výstupního souboru. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) používaný k vyřešení funkce XSLT **document()**. Pokud je **nullptr**, funkce **document()** není vyřešena. [XmlResolver](../../../system.xml/xmlresolver/) není po dokončení [XslTransform::Transform](./) metody uloženo do mezipaměti. |

## XslTransform::Transform(const String\&, const String\&) method

Transformuje XML data v vstupním souboru a výsledek uloží do výstupního souboru.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | URL zdrojového dokumentu, který má být transformován. |
| outputfile | const [String](../../../system/string/)\& | URL výstupního souboru. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlReader](../../../system.xml/xmlreader/)
* Třída [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Třída [XsltArgumentList](../../xsltargumentlist/)
* Třída [XmlResolver](../../../system.xml/xmlresolver/)
* Třída [XslTransform](../)
* Třída [XmlWriter](../../../system.xml/xmlwriter/)
* Třída [Stream](../../../system.io/stream/)
* Třída [TextWriter](../../../system.io/textwriter/)
* Třída [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml::Xsl](../../)
* Knihovna [Aspose.Slides](../../../)