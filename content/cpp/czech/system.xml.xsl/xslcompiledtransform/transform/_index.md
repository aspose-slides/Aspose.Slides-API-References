---
title: Transform()
second_title: Aspose.Slides pro C++ API Reference
description: Provádí transformaci pomocí vstupního dokumentu určeného objektem IXPathNavigable a výstup ukládá do XmlWriteru.
type: docs
weight: 40
url: /cs/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) method

Provede transformaci pomocí vstupního dokumentu určeného objektem IXPathNavigable a výstup uloží do [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objekt implementující rozhraní IXPathNavigable. Může to být buď [XmlNode](../../../system.xml/xmlnode/) (obvykle [XmlDocument](../../../system.xml/xmldocument/)) nebo XPathDocument obsahující data k transformaci. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) do kterého chcete výstup. Pokud stylový list obsahuje prvek **xsl:output**, měli byste vytvořit [XmlWriter](../../../system.xml/xmlwriter/) pomocí objektu [XmlWriterSettings](../../../system.xml/xmlwritersettings/) vráceného z hodnoty [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Tím zajistíte, že [XmlWriter](../../../system.xml/xmlwriter/) má správná nastavení výstupu. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Provede transformaci pomocí vstupního dokumentu určeného objektem IXPathNavigable a výstup uloží do [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) poskytuje další argumenty za běhu.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objekt implementující rozhraní IXPathNavigable. Může to být buď [XmlNode](../../../system.xml/xmlnode/) (obvykle [XmlDocument](../../../system.xml/xmldocument/)) nebo XPathDocument obsahující data k transformaci. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. Tato hodnota může být **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) do kterého chcete výstup. Pokud stylový list obsahuje prvek **xsl:output**, měli byste vytvořit [XmlWriter](../../../system.xml/xmlwriter/) pomocí objektu [XmlWriterSettings](../../../system.xml/xmlwritersettings/) vráceného z hodnoty [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Tím zajistíte, že [XmlWriter](../../../system.xml/xmlwriter/) má správná nastavení výstupu. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Provede transformaci pomocí vstupního dokumentu určeného objektem IXPathNavigable a výstup uloží do TextWriter. [XsltArgumentList](../../xsltargumentlist/) poskytuje další argumenty za běhu.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objekt implementující rozhraní IXPathNavigable. Může to být buď [XmlNode](../../../system.xml/xmlnode/) (obvykle [XmlDocument](../../../system.xml/xmldocument/)) nebo XPathDocument obsahující data k transformaci. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. Tato hodnota může být **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do kterého chcete výstup. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Provede transformaci pomocí vstupního dokumentu určeného objektem IXPathNavigable a výstup uloží do proudu. [XsltArgumentList](../../xsltargumentlist/) poskytuje další argumenty za běhu.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objekt implementující rozhraní IXPathNavigable. Může to být buď [XmlNode](../../../system.xml/xmlnode/) (obvykle [XmlDocument](../../../system.xml/xmldocument/)) nebo XPathDocument obsahující data k transformaci. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. Tato hodnota může být **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Proud, do kterého chcete výstup. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) method

Provede transformaci pomocí vstupního dokumentu určeného objektem [XmlReader](../../../system.xml/xmlreader/) a výstup uloží do [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) obsahující vstupní dokument. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), do kterého chcete výstup. Pokud stylový list obsahuje prvek **xsl:output**, měli byste vytvořit [XmlWriter](../../../system.xml/xmlwriter/) pomocí objektu [XmlWriterSettings](../../../system.xml/xmlwritersettings/) vráceného z hodnoty [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Tím zajistíte, že [XmlWriter](../../../system.xml/xmlwriter/) má správná nastavení výstupu. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Provede transformaci pomocí vstupního dokumentu určeného objektem [XmlReader](../../../system.xml/xmlreader/) a výstup uloží do [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) poskytuje další argumenty za běhu.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) obsahující vstupní dokument. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. Tato hodnota může být **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), do kterého chcete výstup. Pokud stylový list obsahuje prvek **xsl:output**, měli byste vytvořit [XmlWriter](../../../system.xml/xmlwriter/) pomocí objektu [XmlWriterSettings](../../../system.xml/xmlwritersettings/) vráceného z hodnoty [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Tím zajistíte, že [XmlWriter](../../../system.xml/xmlwriter/) má správná nastavení výstupu. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Provede transformaci pomocí vstupního dokumentu určeného objektem [XmlReader](../../../system.xml/xmlreader/) a výstup uloží do TextWriter. [XsltArgumentList](../../xsltargumentlist/) poskytuje další argumenty za běhu.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) obsahující vstupní dokument. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. Tato hodnota může být **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do kterého chcete výstup. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Provede transformaci pomocí vstupního dokumentu určeného objektem [XmlReader](../../../system.xml/xmlreader/) a výstup uloží do proudu. [XsltArgumentList](../../xsltargumentlist/) poskytuje další argumenty za běhu.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) obsahující vstupní dokument. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. Tato hodnota může být **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Proud, do kterého chcete výstup. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) method

Provede transformaci pomocí vstupního dokumentu určeného URI a výstup uloží do [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI vstupního dokumentu. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), do kterého chcete výstup. Pokud stylový list obsahuje prvek **xsl:output**, měli byste vytvořit [XmlWriter](../../../system.xml/xmlwriter/) pomocí objektu [XmlWriterSettings](../../../system.xml/xmlwritersettings/) vráceného z hodnoty [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Tím zajistíte, že [XmlWriter](../../../system.xml/xmlwriter/) má správná nastavení výstupu. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Provede transformaci pomocí vstupního dokumentu určeného URI a výstup uloží do [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) poskytuje další argumenty za běhu.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI vstupního dokumentu. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. Tato hodnota může být **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), do kterého chcete výstup. Pokud stylový list obsahuje prvek **xsl:output**, měli byste vytvořit [XmlWriter](../../../system.xml/xmlwriter/) pomocí objektu [XmlWriterSettings](../../../system.xml/xmlwritersettings/) vráceného z hodnoty [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Tím zajistíte, že [XmlWriter](../../../system.xml/xmlwriter/) má správná nastavení výstupu. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Provede transformaci pomocí vstupního dokumentu určeného URI a výstup uloží do TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI vstupního dokumentu. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. Tato hodnota může být **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do kterého chcete výstup. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Provede transformaci pomocí vstupního dokumentu určeného URI a výstup uloží do proudu. [XsltArgumentList](../../xsltargumentlist/) poskytuje další argumenty za běhu.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI vstupního dokumentu. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. Tato hodnota může být **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Proud, do kterého chcete výstup. |

## XslCompiledTransform::Transform(const String\&, const String\&) method

Provede transformaci pomocí vstupního dokumentu určeného URI a výstup uloží do souboru.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI vstupního dokumentu. |
| resultsFile | const [String](../../../system/string/)\& | URI výstupního souboru. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method

Provede transformaci pomocí vstupního dokumentu určeného objektem [XmlReader](../../../system.xml/xmlreader/) a výstup uloží do [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) poskytuje další argumenty za běhu a [XmlResolver](../../../system.xml/xmlresolver/) řeší funkci XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) obsahující vstupní dokument. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) obsahující jmenně kvalifikované argumenty použité jako vstup pro transformaci. Tato hodnota může být **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), do kterého chcete výstup. Pokud stylový list obsahuje prvek **xsl:output**, měli byste vytvořit [XmlWriter](../../../system.xml/xmlwriter/) pomocí objektu [XmlWriterSettings](../../../system.xml/xmlwritersettings/) vráceného z hodnoty [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Tím zajistíte, že [XmlWriter](../../../system.xml/xmlwriter/) má správná nastavení výstupu. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) použité k řešení funkce XSLT **document()**. Pokud je tato hodnota **nullptr**, funkce **document()** není řešena. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method

Provede transformaci pomocí vstupního dokumentu určeného objektem IXPathNavigable a výstup uloží do [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) poskytuje další argumenty za běhu a [XmlResolver](../../../system.xml/xmlresolver/) řeší funkci XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Dokument k transformaci, který je určen objektem IXPathNavigable. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Seznam argumentů jako [XsltArgumentList](../../xsltargumentlist/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), do kterého chcete výstup. Pokud stylový list obsahuje prvek **xsl:output**, měli byste vytvořit [XmlWriter](../../../system.xml/xmlwriter/) pomocí objektu [XmlWriterSettings](../../../system.xml/xmlwritersettings/) vráceného z hodnoty [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Tím zajistíte, že [XmlWriter](../../../system.xml/xmlwriter/) má správná nastavení výstupu. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) použité k řešení funkce XSLT **document()**. Pokud je tato hodnota **nullptr**, funkce **document()** není řešena. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)