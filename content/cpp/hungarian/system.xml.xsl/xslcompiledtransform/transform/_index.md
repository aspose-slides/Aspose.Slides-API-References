---
title: Transform()
second_title: Aspose.Slides for C++ API referencia
description: Végrehajtja az átalakítást a IXPathNavigable objektum által megadott bemeneti dokumentum használatával, és az eredményeket egy XmlWriter-be írja ki.
type: docs
weight: 40
url: /hu/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) metódus

Végrehajtja az átalakítást a IXPathNavigable objektum által megadott bemeneti dokumentum használatával, és az eredményeket egy [XmlWriter](../../../system.xml/xmlwriter/)-ba írja ki.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Az IXPathNavigable interfészt megvalósító objektum. Lehet egy [XmlNode](../../../system.xml/xmlnode/) (általában egy [XmlDocument](../../../system.xml/xmldocument/)), vagy egy adatokat tartalmazó XPathDocument, amelyet át kell alakítani. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | A [XmlWriter](../../../system.xml/xmlwriter/), amelybe ki szeretné írni az eredményt. Ha a stíluslap tartalmaz **xsl:output** elemet, akkor a [XmlWriter](../../../system.xml/xmlwriter/)-t a [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) értékből visszaadott [XmlWriterSettings](../../../system.xml/xmlwritersettings/) objektummal kell létrehozni. Ez biztosítja, hogy a [XmlWriter](../../../system.xml/xmlwriter/) megfelelő kimeneti beállításokkal rendelkezzen. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) metódus

Végrehajtja az átalakítást a IXPathNavigable objektum által megadott bemeneti dokumentum használatával, és az eredményeket egy [XmlWriter](../../../system.xml/xmlwriter/)-ba írja ki. A [XsltArgumentList](../../xsltargumentlist/) további futásidejű argumentumokat biztosít.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Az IXPathNavigable interfészt megvalósító objektum. Lehet egy [XmlNode](../../../system.xml/xmlnode/) (általában egy [XmlDocument](../../../system.xml/xmldocument/)), vagy egy adatokat tartalmazó XPathDocument, amelyet át kell alakítani. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/) amely a névtérrel ellátott argumentumokat tartalmazza, és bemenetként szolgál az átalakításhoz. Ez az érték lehet **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | A [XmlWriter](../../../system.xml/xmlwriter/), amelybe ki szeretné írni az eredményt. Ha a stíluslap tartalmaz **xsl:output** elemet, akkor a [XmlWriter](../../../system.xml/xmlwriter/)-t a [XmlWriterSettings](../../../system.xml/xmlwritersettings/) objektummal kell létrehozni, amely a [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) értékből visszaadott. Ez biztosítja, hogy a [XmlWriter](../../../system.xml/xmlwriter/) megfelelő kimeneti beállításokkal rendelkezzen. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) metódus

Végrehajtja az átalakítást a IXPathNavigable objektum által megadott bemeneti dokumentum használatával, és az eredményeket egy TextWriter-be írja ki. A [XsltArgumentList](../../xsltargumentlist/) további futásidejű argumentumokat biztosít.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Az IXPathNavigable interfészt megvalósító objektum. Lehet egy [XmlNode](../../../system.xml/xmlnode/) (általában egy [XmlDocument](../../../system.xml/xmldocument/)), vagy egy adatokat tartalmazó XPathDocument, amelyet át kell alakítani. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/) amely a névtérrel ellátott argumentumokat tartalmazza, és bemenetként szolgál az átalakításhoz. Ez az érték lehet **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | A TextWriter, amelybe ki szeretné írni az eredményt. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) metódus

Végrehajtja az átalakítást a IXPathNavigable objektum által megadott bemeneti dokumentum használatával, és az eredményeket egy adatfolyamba írja ki. A [XsltArgumentList](../../xsltargumentlist/) további futásidejű argumentumokat biztosít.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Az IXPathNavigable interfészt megvalósító objektum. Lehet egy [XmlNode](../../../system.xml/xmlnode/) (általában egy [XmlDocument](../../../system.xml/xmldocument/)), vagy egy adatokat tartalmazó XPathDocument, amelyet át kell alakítani. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/) amely a névtérrel ellátott argumentumokat tartalmazza, és bemenetként szolgál az átalakításhoz. Ez az érték lehet **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | A stream, amelybe ki szeretné írni az eredményt. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) metódus

Végrehajtja az átalakítást a [XmlReader](../../../system.xml/xmlreader/) objektum által megadott bemeneti dokumentum használatával, és az eredményeket egy [XmlWriter](../../../system.xml/xmlwriter/)-ba írja ki.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | A [XmlReader](../../../system.xml/xmlreader/), amely a bemeneti dokumentumot tartalmazza. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | A [XmlWriter](../../../system.xml/xmlwriter/), amelybe ki szeretné írni az eredményt. Ha a stíluslap tartalmaz **xsl:output** elemet, akkor a [XmlWriter](../../../system.xml/xmlwriter/)-t a [XmlWriterSettings](../../../system.xml/xmlwritersettings/) objektummal kell létrehozni, amely a [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) értékből visszaadott. Ez biztosítja, hogy a [XmlWriter](../../../system.xml/xmlwriter/) megfelelő kimeneti beállításokkal rendelkezzen. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) metódus

Végrehajtja az átalakítást a [XmlReader](../../../system.xml/xmlreader/) objektum által megadott bemeneti dokumentum használatával, és az eredményeket egy [XmlWriter](../../../system.xml/xmlwriter/)-ba írja ki. A [XsltArgumentList](../../xsltargumentlist/) további futásidejű argumentumokat biztosít.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Egy [XmlReader](../../../system.xml/xmlreader/), amely a bemeneti dokumentumot tartalmazza. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/) amely a névtérrel ellátott argumentumokat tartalmazza, és bemenetként szolgál az átalakításhoz. Ez az érték lehet **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | A [XmlWriter](../../../system.xml/xmlwriter/), amelybe ki szeretné írni az eredményt. Ha a stíluslap tartalmaz **xsl:output** elemet, akkor a [XmlWriter](../../../system.xml/xmlwriter/)-t a [XmlWriterSettings](../../../system.xml/xmlwritersettings/) objektummal kell létrehozni, amely a [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) értékből visszaadott. Ez biztosítja, hogy a [XmlWriter](../../../system.xml/xmlwriter/) megfelelő kimeneti beállításokkal rendelkezzen. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) metódus

Végrehajtja az átalakítást a [XmlReader](../../../system.xml/xmlreader/) objektum által megadott bemeneti dokumentum használatával, és az eredményeket egy TextWriter-be írja ki. A [XsltArgumentList](../../xsltargumentlist/) további futásidejű argumentumokat biztosít.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Egy [XmlReader](../../../system.xml/xmlreader/), amely a bemeneti dokumentumot tartalmazza. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/) amely a névtérrel ellátott argumentumokat tartalmazza, és bemenetként szolgál az átalakításhoz. Ez az érték lehet **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | A TextWriter, amelybe ki szeretné írni az eredményt. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) metódus

Végrehajtja az átalakítást a [XmlReader](../../../system.xml/xmlreader/) objektum által megadott bemeneti dokumentum használatával, és az eredményeket egy adatfolyamba írja ki. A [XsltArgumentList](../../xsltargumentlist/) további futásidejű argumentumokat biztosít.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Egy [XmlReader](../../../system.xml/xmlreader/), amely a bemeneti dokumentumot tartalmazza. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/) amely a névtérrel ellátott argumentumokat tartalmazza, és bemenetként szolgál az átalakításhoz. Ez az érték lehet **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | A stream, amelybe ki szeretné írni az eredményt. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) metódus

Végrehajtja az átalakítást a URI által megadott bemeneti dokumentum használatával, és az eredményeket egy [XmlWriter](../../../system.xml/xmlwriter/)-ba írja ki.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | A bemeneti dokumentum URI-ja. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | A [XmlWriter](../../../system.xml/xmlwriter/), amelybe ki szeretné írni az eredményt. Ha a stíluslap tartalmaz **xsl:output** elemet, akkor a [XmlWriter](../../../system.xml/xmlwriter/)-t a [XmlWriterSettings](../../../system.xml/xmlwritersettings/) objektummal kell létrehozni, amely a [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) értékből visszaadott. Ez biztosítja, hogy a [XmlWriter](../../../system.xml/xmlwriter/) megfelelő kimeneti beállításokkal rendelkezzen. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) metódus

Végrehajtja az átalakítást a URI által megadott bemeneti dokumentum használatával, és az eredményeket egy [XmlWriter](../../../system.xml/xmlwriter/)-ba írja ki. A [XsltArgumentList](../../xsltargumentlist/) további futásidejű argumentumokat biztosít.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | A bemeneti dokumentum URI-ja. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/) amely a névtérrel ellátott argumentumokat tartalmazza, és bemenetként szolgál az átalakításhoz. Ez az érték lehet **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | A [XmlWriter](../../../system.xml/xmlwriter/), amelybe ki szeretné írni az eredményt. Ha a stíluslap tartalmaz **xsl:output** elemet, akkor a [XmlWriter](../../../system.xml/xmlwriter/)-t a [XmlWriterSettings](../../../system.xml/xmlwritersettings/) objektummal kell létrehozni, amely a [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) értékből visszaadott. Ez biztosítja, hogy a [XmlWriter](../../../system.xml/xmlwriter/) megfelelő kimeneti beállításokkal rendelkezzen. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) metódus

Végrehajtja az átalakítást a URI által megadott bemeneti dokumentum használatával, és az eredményeket egy TextWriter-be írja ki.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | A bemeneti dokumentum URI-ja. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/) amely a névtérrel ellátott argumentumokat tartalmazza, és bemenetként szolgál az átalakításhoz. Ez az érték lehet **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | A TextWriter, amelybe ki szeretné írni az eredményt. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) metódus

Végrehajtja az átalakítást a URI által megadott bemeneti dokumentum használatával, és az eredményeket egy adatfolyamba írja ki. A [XsltArgumentList](../../xsltargumentlist/) további futásidejű argumentumokat biztosít.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | A bemeneti dokumentum URI-ja. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/) amely a névtérrel ellátott argumentumokat tartalmazza, és bemenetként szolgál az átalakításhoz. Ez az érték lehet **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | A stream, amelybe ki szeretné írni az eredményt. |

## XslCompiledTransform::Transform(const String\&, const String\&) metódus

Végrehajtja az átalakítást a URI által megadott bemeneti dokumentum használatával, és az eredményeket egy fájlba írja ki.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | A bemeneti dokumentum URI-ja. |
| resultsFile | const [String](../../../system/string/)\& | A kimeneti fájl URI-ja. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) metódus

Végrehajtja az átalakítást a [XmlReader](../../../system.xml/xmlreader/) objektum által megadott bemeneti dokumentum használatával, és az eredményeket egy [XmlWriter](../../../system.xml/xmlwriter/)-ba írja ki. A [XsltArgumentList](../../xsltargumentlist/) további futásidejű argumentumokat biztosít, a [XmlResolver](../../../system.xml/xmlresolver/) pedig az XSLT **document()** függvényt oldja fel.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Egy [XmlReader](../../../system.xml/xmlreader/), amely a bemeneti dokumentumot tartalmazza. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Egy [XsltArgumentList](../../xsltargumentlist/) amely a névtérrel ellátott argumentumokat tartalmazza, és bemenetként szolgál az átalakításhoz. Ez az érték lehet **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | A [XmlWriter](../../../system.xml/xmlwriter/), amelybe ki szeretné írni az eredményt. Ha a stíluslap tartalmaz **xsl:output** elemet, akkor a [XmlWriter](../../../system.xml/xmlwriter/)-t a [XmlWriterSettings](../../../system.xml/xmlwritersettings/) objektummal kell létrehozni, amely a [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) értékből visszaadott. Ez biztosítja, hogy a [XmlWriter](../../../system.xml/xmlwriter/) megfelelő kimeneti beállításokkal rendelkezzen. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/), amely a XSLT **document()** függvény feloldásáért felel. Ha ez **nullptr**, a **document()** függvény nem lesz feloldva. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) metódus

Végrehajtja az átalakítást a IXPathNavigable objektum által megadott bemeneti dokumentum használatával, és az eredményeket egy [XmlWriter](../../../system.xml/xmlwriter/)-ba írja ki. A [XsltArgumentList](../../xsltargumentlist/) további futásidejű argumentumokat biztosít, a [XmlResolver](../../../system.xml/xmlresolver/) pedig az XSLT **document()** függvényt oldja fel.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | A dokumentum, amelyet át kell alakítani, és amelyet a IXPathNavigable objektum határoz meg. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Argumentumlista, mint [XsltArgumentList](../../xsltargumentlist/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | A [XmlWriter](../../../system.xml/xmlwriter/), amelybe ki szeretné írni az eredményt. Ha a stíluslap tartalmaz **xsl:output** elemet, akkor a [XmlWriter](../../../system.xml/xmlwriter/)-t a [XmlWriterSettings](../../../system.xml/xmlwritersettings/) objektummal kell létrehozni, amely a [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) értékből visszaadott. Ez biztosítja, hogy a [XmlWriter](../../../system.xml/xmlwriter/) megfelelő kimeneti beállításokkal rendelkezzen. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/), amely a XSLT **document()** függvény feloldásáért felel. Ha ez **nullptr**, a **document()** függvény nem lesz feloldva. |

## Lásd még

* Tipedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Osztály [XmlWriter](../../../system.xml/xmlwriter/)
* Osztály [XslCompiledTransform](../)
* Osztály [XsltArgumentList](../../xsltargumentlist/)
* Osztály [TextWriter](../../../system.io/textwriter/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [XmlReader](../../../system.xml/xmlreader/)
* Osztály [String](../../../system/string/)
* Osztály [XmlResolver](../../../system.xml/xmlresolver/)
* Névtér [System::Xml::Xsl](../../)
* Könyvtár [Aspose.Slides](../../../)