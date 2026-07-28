---
title: Transform()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Przekształca dane XML w obiekcie XPathNavigator przy użyciu określonych args i zapisuje wynik do XmlReadera.
type: docs
weight: 40
url: /pl/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metoda


Przekształca dane XML w obiekcie XPathNavigator przy użyciu określonych **args** i zapisuje wynik do [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Obiekt XPathNavigator zawierający dane do przekształcenia. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Obiekt [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty z kwalifikacją przestrzeni nazw używane jako dane wejściowe do przekształcenia. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania funkcji XSLT **document()**. Jeśli jest **nullptr**, funkcja **document()** nie jest rozwiązywana. [XmlResolver](../../../system.xml/xmlresolver/) nie jest buforowany po zakończeniu tej metody. |

### Wartość zwracana

Obiekt [XmlReader](../../../system.xml/xmlreader/) zawierający wyniki przekształcenia.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) metoda


Przekształca dane XML w obiekcie XPathNavigator przy użyciu określonych **args** i zapisuje wynik do [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Obiekt XPathNavigator zawierający dane do przekształcenia. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Obiekt [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty z kwalifikacją przestrzeni nazw używane jako dane wejściowe do przekształcenia. |

### Wartość zwracana

Obiekt [XmlReader](../../../system.xml/xmlreader/) zawierający wyniki przekształcenia.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metoda


Przekształca dane XML w obiekcie XPathNavigator przy użyciu określonych args i zapisuje wynik do [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Obiekt XPathNavigator zawierający dane do przekształcenia. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Obiekt [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty z kwalifikacją przestrzeni nazw używane jako dane wejściowe do przekształcenia. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) do którego chcesz zapisać wynik. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania funkcji XSLT **document()**. Jeśli jest **nullptr**, funkcja **document()** nie jest rozwiązywana. [XmlResolver](../../../system.xml/xmlresolver/) nie jest buforowany po zakończeniu tej metody. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) metoda


Przekształca dane XML w obiekcie XPathNavigator przy użyciu określonych args i zapisuje wynik do [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Obiekt XPathNavigator zawierający dane do przekształcenia. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Obiekt [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty z kwalifikacją przestrzeni nazw używane jako dane wejściowe do przekształcenia. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) do którego chcesz zapisać wynik. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metoda


Przekształca dane XML w obiekcie XPathNavigator przy użyciu określonych **args** i zapisuje wynik do strumienia.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Obiekt XPathNavigator zawierający dane do przekształcenia. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Obiekt [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty z kwalifikacją przestrzeni nazw używane jako dane wejściowe do przekształcenia. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień, do którego chcesz zapisać wynik. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania funkcji XSLT **document()**. Jeśli jest **nullptr**, funkcja **document()** nie jest rozwiązywana. [XmlResolver](../../../system.xml/xmlresolver/) nie jest buforowany po zakończeniu tej metody. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) metoda


Przekształca dane XML w obiekcie XPathNavigator przy użyciu określonych **args** i zapisuje wynik do strumienia.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Obiekt XPathNavigator zawierający dane do przekształcenia. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Obiekt [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty z kwalifikacją przestrzeni nazw używane jako dane wejściowe do przekształcenia. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień, do którego chcesz zapisać wynik. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metoda


Przekształca dane XML w obiekcie XPathNavigator przy użyciu określonych **args** i zapisuje wynik do TextWritera.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Obiekt XPathNavigator zawierający dane do przekształcenia. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Obiekt [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty z kwalifikacją przestrzeni nazw używane jako dane wejściowe do przekształcenia. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do którego chcesz zapisać wynik. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania funkcji XSLT **document()**. Jeśli jest **nullptr**, funkcja **document()** nie jest rozwiązywana. [XmlResolver](../../../system.xml/xmlresolver/) nie jest buforowany po zakończeniu tej metody. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) metoda


Przekształca dane XML w obiekcie XPathNavigator przy użyciu określonych **args** i zapisuje wynik do TextWritera.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Obiekt XPathNavigator zawierający dane do przekształcenia. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Obiekt [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty z kwalifikacją przestrzeni nazw używane jako dane wejściowe do przekształcenia. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do którego chcesz zapisać wynik. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metoda


Przekształca dane XML w obiekcie IXPathNavigable przy użyciu określonych **args** i zapisuje wynik do [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Obiekt implementujący interfejs IXPathNavigable. Może to być [XmlNode](../../../system.xml/xmlnode/) (zwykle [XmlDocument](../../../system.xml/xmldocument/)) lub XPathDocument zawierający dane do przekształcenia. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Obiekt [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty z kwalifikacją przestrzeni nazw używane jako dane wejściowe do przekształcenia. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania funkcji XSLT **document()**. Jeśli jest **nullptr**, funkcja **document()** nie jest rozwiązywana. [XmlResolver](../../../system.xml/xmlresolver/) nie jest buforowany po zakończeniu tej metody. |

### Wartość zwracana

Obiekt [XmlReader](../../../system.xml/xmlreader/) zawierający wyniki przekształcenia.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) metoda


Przekształca dane XML w obiekcie IXPathNavigable przy użyciu określonych **args** i zapisuje wynik do [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Obiekt implementujący interfejs IXPathNavigable. Może to być [XmlNode](../../../system.xml/xmlnode/) (zwykle [XmlDocument](../../../system.xml/xmldocument/)) lub XPathDocument zawierający dane do przekształcenia. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Obiekt [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty z kwalifikacją przestrzeni nazw używane jako dane wejściowe do przekształcenia. |

### Wartość zwracana

Obiekt [XmlReader](../../../system.xml/xmlreader/) zawierający wyniki przekształcenia.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metoda


Przekształca dane XML w obiekcie IXPathNavigable przy użyciu określonych **args** i zapisuje wynik do TextWritera.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Obiekt implementujący interfejs IXPathNavigable. Może to być [XmlNode](../../../system.xml/xmlnode/) (zwykle [XmlDocument](../../../system.xml/xmldocument/)) lub XPathDocument zawierający dane do przekształcenia. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Obiekt [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty z kwalifikacją przestrzeni nazw używane jako dane wejściowe do przekształcenia. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do którego chcesz zapisać wynik. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania funkcji XSLT **document()**. Jeśli jest **nullptr**, funkcja **document()** nie jest rozwiązywana. [XmlResolver](../../../system.xml/xmlresolver/) nie jest buforowany po zakończeniu tej metody. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) metoda


Przekształca dane XML w obiekcie IXPathNavigable przy użyciu określonych **args** i zapisuje wynik do TextWritera.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Obiekt implementujący interfejs IXPathNavigable. Może to być [XmlNode](../../../system.xml/xmlnode/) (zwykle [XmlDocument](../../../system.xml/xmldocument/)) lub XPathDocument zawierający dane do przekształcenia. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Obiekt [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty z kwalifikacją przestrzeni nazw używane jako dane wejściowe do przekształcenia. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do którego chcesz zapisać wynik. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metoda


Przekształca dane XML w obiekcie IXPathNavigable przy użyciu określonych **args** i zapisuje wynik do strumienia.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Obiekt implementujący interfejs IXPathNavigable. Może to być [XmlNode](../../../system.xml/xmlnode/) (zwykle [XmlDocument](../../../system.xml/xmldocument/)) lub XPathDocument zawierający dane do przekształcenia. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Obiekt [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty z kwalifikacją przestrzeni nazw używane jako dane wejściowe do przekształcenia. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień, do którego chcesz zapisać wynik. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania funkcji XSLT **document()**. Jeśli jest **nullptr**, funkcja **document()** nie jest rozwiązywana. [XmlResolver](../../../system.xml/xmlresolver/) nie jest buforowany po zakończeniu [XslTransform::Transform](./) metody. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) metoda


Przekształca dane XML w obiekcie IXPathNavigable przy użyciu określonych **args** i zapisuje wynik do strumienia.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Obiekt implementujący interfejs IXPathNavigable. Może to być [XmlNode](../../../system.xml/xmlnode/) (zwykle [XmlDocument](../../../system.xml/xmldocument/)) lub XPathDocument zawierający dane do przekształcenia. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Obiekt [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty z kwalifikacją przestrzeni nazw używane jako dane wejściowe do przekształcenia. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień, do którego chcesz zapisać wynik. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metoda


Przekształca dane XML w obiekcie IXPathNavigable przy użyciu określonych **args** i zapisuje wynik do [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Obiekt implementujący interfejs IXPathNavigable. Może to być [XmlNode](../../../system.xml/xmlnode/) (zwykle [XmlDocument](../../../system.xml/xmldocument/)) lub XPathDocument zawierający dane do przekształcenia. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Obiekt [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty z kwalifikacją przestrzeni nazw używane jako dane wejściowe do przekształcenia. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) do którego chcesz zapisać wynik. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania funkcji XSLT **document()**. Jeśli jest **nullptr**, funkcja **document()** nie jest rozwiązywana. [XmlResolver](../../../system.xml/xmlresolver/) nie jest buforowany po zakończeniu tej metody. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) metoda


Przekształca dane XML w obiekcie IXPathNavigable przy użyciu określonych **args** i zapisuje wynik do [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Obiekt implementujący interfejs IXPathNavigable. Może to być [XmlNode](../../../system.xml/xmlnode/) (zwykle [XmlDocument](../../../system.xml/xmldocument/)) lub XPathDocument zawierający dane do przekształcenia. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Obiekt [XsltArgumentList](../../xsltargumentlist/) zawierający argumenty z kwalifikacją przestrzeni nazw używane jako dane wejściowe do przekształcenia. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) do którego chcesz zapisać wynik. |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metoda


Przekształca dane XML w pliku wejściowym i zapisuje wynik do pliku wyjściowego.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | URL dokumentu źródłowego, który ma zostać przekształcony. |
| outputfile | const [String](../../../system/string/)\& | URL pliku wyjściowego. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) używany do rozwiązywania funkcji XSLT **document()**. Jeśli jest **nullptr**, funkcja **document()** nie jest rozwiązywana. [XmlResolver](../../../system.xml/xmlresolver/) nie jest buforowany po zakończeniu [XslTransform::Transform](./) metody. |

## XslTransform::Transform(const String\&, const String\&) metoda


Przekształca dane XML w pliku wejściowym i zapisuje wynik do pliku wyjściowego.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | URL dokumentu źródłowego, który ma zostać przekształcony. |
| outputfile | const [String](../../../system/string/)\& | URL pliku wyjściowego. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlReader](../../../system.xml/xmlreader/)
* Klasa [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Klasa [XsltArgumentList](../../xsltargumentlist/)
* Klasa [XmlResolver](../../../system.xml/xmlresolver/)
* Klasa [XslTransform](../)
* Klasa [XmlWriter](../../../system.xml/xmlwriter/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [TextWriter](../../../system.io/textwriter/)
* Klasa [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml::Xsl](../../)
* Biblioteka [Aspose.Slides](../../../)