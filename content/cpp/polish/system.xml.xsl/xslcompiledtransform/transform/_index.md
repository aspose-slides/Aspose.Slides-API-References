---
title: Transform()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wykonuje transformację przy użyciu dokumentu wejściowego określonego przez obiekt IXPathNavigable i zapisuje wyniki do XmlWriter.
type: docs
weight: 40
url: /pl/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) metoda

Wykonuje transformację przy użyciu dokumentu wejściowego określonego przez obiekt IXPathNavigable i zapisuje wyniki do [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Obiekt implementujący interfejs IXPathNavigable. Może to być [XmlNode](../../../system.xml/xmlnode/) (zwykle [XmlDocument](../../../system.xml/xmldocument/)) lub XPathDocument zawierający dane do przekształcenia. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) do którego chcesz zapisać wynik. Jeśli arkusz stylów zawiera element **xsl:output**, należy utworzyć [XmlWriter](../../../system.xml/xmlwriter/) przy użyciu obiektu [XmlWriterSettings](../../../system.xml/xmlwritersettings/) zwróconego z wartości [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Zapewnia to, że [XmlWriter](../../../system.xml/xmlwriter/) ma prawidłowe ustawienia wyjścia. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) metoda

Wykonuje transformację przy użyciu dokumentu wejściowego określonego przez obiekt IXPathNavigable i zapisuje wyniki do [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) zapewnia dodatkowe argumenty czasu wykonywania.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Obiekt implementujący interfejs IXPathNavigable. Może to być [XmlNode](../../../system.xml/xmlnode/) (zwykle [XmlDocument](../../../system.xml/xmldocument/)) lub XPathDocument zawierający dane do przekształcenia. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty kwalifikowane przestrzenią nazw używane jako wejście do transformacji. Ta wartość może być **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) do którego chcesz zapisać wynik. Jeśli arkusz stylów zawiera element **xsl:output**, należy utworzyć [XmlWriter](../../../system.xml/xmlwriter/) przy użyciu obiektu [XmlWriterSettings](../../../system.xml/xmlwritersettings/) zwróconego z wartości [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Zapewnia to, że [XmlWriter](../../../system.xml/xmlwriter/) ma prawidłowe ustawienia wyjścia. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) metoda

Wykonuje transformację przy użyciu dokumentu wejściowego określonego przez obiekt IXPathNavigable i zapisuje wyniki do TextWriter. [XsltArgumentList](../../xsltargumentlist/) zapewnia dodatkowe argumenty czasu wykonywania.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Obiekt implementujący interfejs IXPathNavigable. Może to być [XmlNode](../../../system.xml/xmlnode/) (zwykle [XmlDocument](../../../system.xml/xmldocument/)) lub XPathDocument zawierający dane do przekształcenia. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty kwalifikowane przestrzenią nazw używane jako wejście do transformacji. Ta wartość może być **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter do którego chcesz zapisać wynik. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) metoda

Wykonuje transformację przy użyciu dokumentu wejściowego określonego przez obiekt IXPathNavigable i zapisuje wyniki do strumienia. [XsltArgumentList](../../xsltargumentlist/) zapewnia dodatkowe argumenty czasu wykonywania.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Obiekt implementujący interfejs IXPathNavigable. Może to być [XmlNode](../../../system.xml/xmlnode/) (zwykle [XmlDocument](../../../system.xml/xmldocument/)) lub XPathDocument zawierający dane do przekształcenia. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty kwalifikowane przestrzenią nazw używane jako wejście do transformacji. Ta wartość może być **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień do którego chcesz zapisać wynik. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) metoda

Wykonuje transformację przy użyciu dokumentu wejściowego określonego przez obiekt [XmlReader](../../../system.xml/xmlreader/) i zapisuje wyniki do [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) zawierający dokument wejściowy. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) do którego chcesz zapisać wynik. Jeśli arkusz stylów zawiera element **xsl:output**, należy utworzyć [XmlWriter](../../../system.xml/xmlwriter/) przy użyciu obiektu [XmlWriterSettings](../../../system.xml/xmlwritersettings/) zwróconego z wartości [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Zapewnia to, że [XmlWriter](../../../system.xml/xmlwriter/) ma prawidłowe ustawienia wyjścia. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) metoda

Wykonuje transformację przy użyciu dokumentu wejściowego określonego przez obiekt [XmlReader](../../../system.xml/xmlreader/) i zapisuje wyniki do [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) zapewnia dodatkowe argumenty czasu wykonywania.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) zawierający dokument wejściowy. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty kwalifikowane przestrzenią nazw używane jako wejście do transformacji. Ta wartość może być **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) do którego chcesz zapisać wynik. Jeśli arkusz stylów zawiera element **xsl:output**, należy utworzyć [XmlWriter](../../../system.xml/xmlwriter/) przy użyciu obiektu [XmlWriterSettings](../../../system.xml/xmlwritersettings/) zwróconego z wartości [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Zapewnia to, że [XmlWriter](../../../system.xml/xmlwriter/) ma prawidłowe ustawienia wyjścia. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) metoda

Wykonuje transformację przy użyciu dokumentu wejściowego określonego przez obiekt [XmlReader](../../../system.xml/xmlreader/) i zapisuje wyniki do TextWriter. [XsltArgumentList](../../xsltargumentlist/) zapewnia dodatkowe argumenty czasu wykonywania.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) zawierający dokument wejściowy. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty kwalifikowane przestrzenią nazw używane jako wejście do transformacji. Ta wartość może być **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter do którego chcesz zapisać wynik. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) metoda

Wykonuje transformację przy użyciu dokumentu wejściowego określonego przez obiekt [XmlReader](../../../system.xml/xmlreader/) i zapisuje wyniki do strumienia. [XsltArgumentList](../../xsltargumentlist/) zapewnia dodatkowe argumenty czasu wykonywania.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) zawierający dokument wejściowy. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty kwalifikowane przestrzenią nazw używane jako wejście do transformacji. Ta wartość może być **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień do którego chcesz zapisać wynik. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) metoda

Wykonuje transformację przy użyciu dokumentu wejściowego określonego przez identyfikator URI i zapisuje wyniki do [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Identyfikator URI dokumentu wejściowego. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) do którego chcesz zapisać wynik. Jeśli arkusz stylów zawiera element **xsl:output**, należy utworzyć [XmlWriter](../../../system.xml/xmlwriter/) przy użyciu obiektu [XmlWriterSettings](../../../system.xml/xmlwritersettings/) zwróconego z wartości [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Zapewnia to, że [XmlWriter](../../../system.xml/xmlwriter/) ma prawidłowe ustawienia wyjścia. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) metoda

Wykonuje transformację przy użyciu dokumentu wejściowego określonego przez identyfikator URI i zapisuje wyniki do [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) zapewnia dodatkowe argumenty czasu wykonywania.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Identyfikator URI dokumentu wejściowego. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty kwalifikowane przestrzenią nazw używane jako wejście do transformacji. Ta wartość może być **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) do którego chcesz zapisać wynik. Jeśli arkusz stylów zawiera element **xsl:output**, należy utworzyć [XmlWriter](../../../system.xml/xmlwriter/) przy użyciu obiektu [XmlWriterSettings](../../../system.xml/xmlwritersettings/) zwróconego z wartości [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Zapewnia to, że [XmlWriter](../../../system.xml/xmlwriter/) ma prawidłowe ustawienia wyjścia. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) metoda

Wykonuje transformację przy użyciu dokumentu wejściowego określonego przez identyfikator URI i zapisuje wyniki do TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Identyfikator URI dokumentu wejściowego. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty kwalifikowane przestrzenią nazw używane jako wejście do transformacji. Ta wartość może być **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter do którego chcesz zapisać wynik. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) metoda

Wykonuje transformację przy użyciu dokumentu wejściowego określonego przez identyfikator URI i zapisuje wyniki do strumienia. [XsltArgumentList](../../xsltargumentlist/) zapewnia dodatkowe argumenty czasu wykonywania.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Identyfikator URI dokumentu wejściowego. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty kwalifikowane przestrzenią nazw używane jako wejście do transformacji. Ta wartość może być **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień do którego chcesz zapisać wynik. |

## XslCompiledTransform::Transform(const String\&, const String\&) metoda

Wykonuje transformację przy użyciu dokumentu wejściowego określonego przez identyfikator URI i zapisuje wyniki do pliku.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Identyfikator URI dokumentu wejściowego. |
| resultsFile | const [String](../../../system/string/)\& | Identyfikator URI pliku wyjściowego. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) metoda

Wykonuje transformację przy użyciu dokumentu wejściowego określonego przez obiekt [XmlReader](../../../system.xml/xmlreader/) i zapisuje wyniki do [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) zapewnia dodatkowe argumenty czasu wykonywania, a [XmlResolver](../../../system.xml/xmlresolver/) rozwiązuje funkcję XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) zawierający dokument wejściowy. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty kwalifikowane przestrzenią nazw używane jako wejście do transformacji. Ta wartość może być **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) do którego chcesz zapisać wynik. Jeśli arkusz stylów zawiera element **xsl:output**, należy utworzyć [XmlWriter](../../../system.xml/xmlwriter/) przy użyciu obiektu [XmlWriterSettings](../../../system.xml/xmlwritersettings/) zwróconego z wartości [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Zapewnia to, że [XmlWriter](../../../system.xml/xmlwriter/) ma prawidłowe ustawienia wyjścia. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania funkcji XSLT **document()**. Jeśli jest **nullptr**, funkcja **document()** nie jest rozwiązywana. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) metoda

Wykonuje transformację przy użyciu dokumentu wejściowego określonego przez obiekt IXPathNavigable i zapisuje wyniki do [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) zapewnia dodatkowe argumenty czasu wykonywania, a [XmlResolver](../../../system.xml/xmlresolver/) rozwiązuje funkcję XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Dokument do przekształcenia określony przez obiekt IXPathNavigable. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Lista argumentów jako [XsltArgumentList](../../xsltargumentlist/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) do którego chcesz zapisać wynik. Jeśli arkusz stylów zawiera element **xsl:output**, należy utworzyć [XmlWriter](../../../system.xml/xmlwriter/) przy użyciu obiektu [XmlWriterSettings](../../../system.xml/xmlwritersettings/) zwróconego z wartości [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Zapewnia to, że [XmlWriter](../../../system.xml/xmlwriter/) ma prawidłowe ustawienia wyjścia. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania funkcji XSLT **document()**. Jeśli jest **nullptr**, funkcja **document()** nie jest rozwiązywana. |

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Klasa [XmlWriter](../../../system.xml/xmlwriter/)
* Klasa [XslCompiledTransform](../)
* Klasa [XsltArgumentList](../../xsltargumentlist/)
* Klasa [TextWriter](../../../system.io/textwriter/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [XmlReader](../../../system.xml/xmlreader/)
* Klasa [String](../../../system/string/)
* Klasa [XmlResolver](../../../system.xml/xmlresolver/)
* Przestrzeń nazw [System::Xml::Xsl](../../)
* Biblioteka [Aspose.Slides](../../../)