---
title: Transform()
second_title: Riferimento API di Aspose.Slides per C++
description: Trasforma i dati XML nell'XPathNavigator usando gli args specificati e restituisce il risultato in un XmlReader.
type: docs
weight: 40
url: /it/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metodo


Trasforma i dati XML nell'XPathNavigator usando gli **args** specificati e restituisce il risultato in un [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator contenente i dati da trasformare. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) utilizzato per risolvere la funzione **document()** di XSLT. Se questo è **nullptr**, la funzione **document()** non viene risolta. Il [XmlResolver](../../../system.xml/xmlresolver/) non viene memorizzato nella cache dopo il completamento di questo metodo. |

### Valore restituito

Un [XmlReader](../../../system.xml/xmlreader/) contenente i risultati della trasformazione.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) metodo


Trasforma i dati XML nell'XPathNavigator usando gli **args** specificati e restituisce il risultato in un [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator contenente i dati da trasformare. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. |

### Valore restituito

Un [XmlReader](../../../system.xml/xmlreader/) contenente i risultati della trasformazione.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metodo


Trasforma i dati XML nell'XPathNavigator usando gli **args** specificati e restituisce il risultato in un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator contenente i dati da trasformare. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Il [XmlWriter](../../../system.xml/xmlwriter/) in cui si desidera scrivere l'output. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) utilizzato per risolvere la funzione **document()** di XSLT. Se questo è **nullptr**, la funzione **document()** non viene risolta. Il [XmlResolver](../../../system.xml/xmlresolver/) non viene memorizzato nella cache dopo il completamento di questo metodo. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) metodo


Trasforma i dati XML nell'XPathNavigator usando gli **args** specificati e restituisce il risultato in un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator contenente i dati da trasformare. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Il [XmlWriter](../../../system.xml/xmlwriter/) in cui si desidera scrivere l'output. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metodo


Trasforma i dati XML nell'XPathNavigator usando gli **args** specificati e restituisce il risultato in uno Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator contenente i dati da trasformare. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream in cui si desidera scrivere l'output. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) utilizzato per risolvere la funzione **document()** di XSLT. Se questo è **nullptr**, la funzione **document()** non viene risolta. Il [XmlResolver](../../../system.xml/xmlresolver/) non viene memorizzato nella cache dopo il completamento di questo metodo. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) metodo


Trasforma i dati XML nell'XPathNavigator usando gli **args** specificati e restituisce il risultato in uno Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator contenente i dati da trasformare. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream in cui si desidera scrivere l'output. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metodo


Trasforma i dati XML nell'XPathNavigator usando gli **args** specificati e restituisce il risultato in un TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator contenente i dati da trasformare. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Il TextWriter in cui si desidera scrivere l'output. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) utilizzato per risolvere la funzione **document()** di XSLT. Se questo è **nullptr**, la funzione **document()** non viene risolta. Il [XmlResolver](../../../system.xml/xmlresolver/) non viene memorizzato nella cache dopo il completamento di questo metodo. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) metodo


Trasforma i dati XML nell'XPathNavigator usando gli **args** specificati e restituisce il risultato in un TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator contenente i dati da trasformare. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Il TextWriter in cui si desidera scrivere l'output. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metodo


Trasforma i dati XML nell'IXPathNavigable usando gli **args** specificati e restituisce il risultato in un [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un oggetto che implementa l'interfaccia IXPathNavigable. Può essere un [XmlNode](../../../system.xml/xmlnode/) (tipicamente un [XmlDocument](../../../system.xml/xmldocument/)) oppure un XPathDocument contenente i dati da trasformare. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) utilizzato per risolvere la funzione **document()** di XSLT. Se questo è **nullptr**, la funzione **document()** non viene risolta. Il [XmlResolver](../../../system.xml/xmlresolver/) non viene memorizzato nella cache dopo il completamento di questo metodo. |

### Valore restituito

Un [XmlReader](../../../system.xml/xmlreader/) contenente i risultati della trasformazione.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) metodo


Trasforma i dati XML nell'IXPathNavigable usando gli **args** specificati e restituisce il risultato in un [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un oggetto che implementa l'interfaccia IXPathNavigable. Può essere un [XmlNode](../../../system.xml/xmlnode/) (tipicamente un [XmlDocument](../../../system.xml/xmldocument/)) oppure un XPathDocument contenente i dati da trasformare. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. |

### Valore restituito

Un [XmlReader](../../../system.xml/xmlreader/) contenente i risultati della trasformazione.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metodo


Trasforma i dati XML nell'IXPathNavigable usando gli **args** specificati e restituisce il risultato in un TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un oggetto che implementa l'interfaccia IXPathNavigable. Può essere un [XmlNode](../../../system.xml/xmlnode/) (tipicamente un [XmlDocument](../../../system.xml/xmldocument/)) oppure un XPathDocument contenente i dati da trasformare. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Il TextWriter in cui si desidera scrivere l'output. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) utilizzato per risolvere la funzione **document()** di XSLT. Se questo è **nullptr**, la funzione **document()** non viene risolta. Il [XmlResolver](../../../system.xml/xmlresolver/) non viene memorizzato nella cache dopo il completamento di questo metodo. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) metodo


Trasforma i dati XML nell'IXPathNavigable usando gli **args** specificati e restituisce il risultato in un TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un oggetto che implementa l'interfaccia IXPathNavigable. Può essere un [XmlNode](../../../system.xml/xmlnode/) (tipicamente un [XmlDocument](../../../system.xml/xmldocument/)) oppure un XPathDocument contenente i dati da trasformare. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Il TextWriter in cui si desidera scrivere l'output. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metodo


Trasforma i dati XML nell'IXPathNavigable usando gli **args** specificati e restituisce il risultato in uno Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un oggetto che implementa l'interfaccia IXPathNavigable. Può essere un [XmlNode](../../../system.xml/xmlnode/) (tipicamente un [XmlDocument](../../../system.xml/xmldocument/)) oppure un XPathDocument contenente i dati da trasformare. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream in cui si desidera scrivere l'output. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) utilizzato per risolvere la funzione **document()** di XSLT. Se questo è **nullptr**, la funzione **document()** non viene risolta. Il [XmlResolver](../../../system.xml/xmlresolver/) non viene memorizzato nella cache dopo il completamento del metodo [XslTransform::Transform](./). |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) metodo


Trasforma i dati XML nell'IXPathNavigable usando gli **args** specificati e restituisce il risultato in uno Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un oggetto che implementa l'interfaccia IXPathNavigable. Può essere un [XmlNode](../../../system.xml/xmlnode/) (tipicamente un [XmlDocument](../../../system.xml/xmldocument/)) oppure un XPathDocument contenente i dati da trasformare. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream in cui si desidera scrivere l'output. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metodo


Trasforma i dati XML nell'IXPathNavigable usando gli **args** specificati e restituisce il risultato in un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un oggetto che implementa l'interfaccia IXPathNavigable. Può essere un [XmlNode](../../../system.xml/xmlnode/) (tipicamente un [XmlDocument](../../../system.xml/xmldocument/)) oppure un XPathDocument contenente i dati da trasformare. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Il [XmlWriter](../../../system.xml/xmlwriter/) in cui si desidera scrivere l'output. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) utilizzato per risolvere la funzione **document()** di XSLT. Se questo è **nullptr**, la funzione **document()** non viene risolta. Il [XmlResolver](../../../system.xml/xmlresolver/) non viene memorizzato nella cache dopo il completamento di questo metodo. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) metodo


Trasforma i dati XML nell'IXPathNavigable usando gli **args** specificati e restituisce il risultato in un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un oggetto che implementa l'interfaccia IXPathNavigable. Può essere un [XmlNode](../../../system.xml/xmlnode/) (tipicamente un [XmlDocument](../../../system.xml/xmldocument/)) oppure un XPathDocument contenente i dati da trasformare. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Il [XmlWriter](../../../system.xml/xmlwriter/) in cui si desidera scrivere l'output. |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metodo


Trasforma i dati XML nel file di input e restituisce il risultato in un file di output.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | L'URL del documento sorgente da trasformare. |
| outputfile | const [String](../../../system/string/)\& | L'URL del file di output. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) utilizzato per risolvere la funzione **document()** di XSLT. Se questo è **nullptr**, la funzione **document()** non viene risolta. Il [XmlResolver](../../../system.xml/xmlresolver/) non viene memorizzato nella cache dopo il completamento del metodo [XslTransform::Transform](./). |

## XslTransform::Transform(const String\&, const String\&) metodo


Trasforma i dati XML nel file di input e restituisce il risultato in un file di output.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | L'URL del documento sorgente da trasformare. |
| outputfile | const [String](../../../system/string/)\& | L'URL del file di output. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Classe [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Classe [XsltArgumentList](../../xsltargumentlist/)
* Classe [XmlResolver](../../../system.xml/xmlresolver/)
* Classe [XslTransform](../)
* Classe [XmlWriter](../../../system.xml/xmlwriter/)
* Classe [Stream](../../../system.io/stream/)
* Classe [TextWriter](../../../system.io/textwriter/)
* Classe [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)