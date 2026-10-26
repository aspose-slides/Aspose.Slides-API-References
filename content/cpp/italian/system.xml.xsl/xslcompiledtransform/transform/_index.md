---
title: Transform()
second_title: Riferimento API di Aspose.Slides per C++
description: Esegue la trasformazione utilizzando il documento di input specificato dall'oggetto IXPathNavigable e restituisce i risultati in un XmlWriter.
type: docs
weight: 40
url: /it/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) method

Esegue la trasformazione utilizzando il documento di input specificato dall'oggetto IXPathNavigable e restituisce i risultati in un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un oggetto che implementa l'interfaccia IXPathNavigable. Può essere un [XmlNode](../../../system.xml/xmlnode/) (tipicamente un [XmlDocument](../../../system.xml/xmldocument/)) o un XPathDocument contenente i dati da trasformare. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Il [XmlWriter](../../../system.xml/xmlwriter/) su cui si desidera scrivere l'output. Se il foglio di stile contiene un elemento **xsl:output**, è necessario creare il [XmlWriter](../../../system.xml/xmlwriter/) usando l'oggetto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) restituito dal valore [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Questo garantisce che il [XmlWriter](../../../system.xml/xmlwriter/) abbia le impostazioni di output corrette. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Esegue la trasformazione utilizzando il documento di input specificato dall'oggetto IXPathNavigable e restituisce i risultati in un [XmlWriter](../../../system.xml/xmlwriter/). Il [XsltArgumentList](../../xsltargumentlist/) fornisce argomenti di esecuzione aggiuntivi.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un oggetto che implementa l'interfaccia IXPathNavigable. Può essere un [XmlNode](../../../system.xml/xmlnode/) (tipicamente un [XmlDocument](../../../system.xml/xmldocument/)) o un XPathDocument contenente i dati da trasformare. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. Questo valore può essere **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Il [XmlWriter](../../../system.xml/xmlwriter/) su cui si desidera scrivere l'output. Se il foglio di stile contiene un elemento **xsl:output**, è necessario creare il [XmlWriter](../../../system.xml/xmlwriter/) usando l'oggetto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) restituito dal valore [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Questo garantisce che il [XmlWriter](../../../system.xml/xmlwriter/) abbia le impostazioni di output corrette. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Esegue la trasformazione utilizzando il documento di input specificato dall'oggetto IXPathNavigable e restituisce i risultati in un TextWriter. Il [XsltArgumentList](../../xsltargumentlist/) fornisce argomenti di esecuzione aggiuntivi.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un oggetto che implementa l'interfaccia IXPathNavigable. Può essere un [XmlNode](../../../system.xml/xmlnode/) (tipicamente un [XmlDocument](../../../system.xml/xmldocument/)) o un XPathDocument contenente i dati da trasformare. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. Questo valore può essere **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Il TextWriter su cui si desidera scrivere l'output. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Esegue la trasformazione utilizzando il documento di input specificato dall'oggetto IXPathNavigable e restituisce i risultati in uno stream. Il [XsltArgumentList](../../xsltargumentlist/) fornisce argomenti di esecuzione aggiuntivi.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un oggetto che implementa l'interfaccia IXPathNavigable. Può essere un [XmlNode](../../../system.xml/xmlnode/) (tipicamente un [XmlDocument](../../../system.xml/xmldocument/)) o un XPathDocument contenente i dati da trasformare. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. Questo valore può essere **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream su cui si desidera scrivere l'output. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) method

Esegue la trasformazione utilizzando il documento di input specificato dall'oggetto [XmlReader](../../../system.xml/xmlreader/) e restituisce i risultati in un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Il [XmlReader](../../../system.xml/xmlreader/) contenente il documento di input. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Il [XmlWriter](../../../system.xml/xmlwriter/) su cui si desidera scrivere l'output. Se il foglio di stile contiene un elemento **xsl:output**, è necessario creare il [XmlWriter](../../../system.xml/xmlwriter/) usando l'oggetto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) restituito dal valore [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Questo garantisce che il [XmlWriter](../../../system.xml/xmlwriter/) abbia le impostazioni di output corrette. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Esegue la trasformazione utilizzando il documento di input specificato dall'oggetto [XmlReader](../../../system.xml/xmlreader/) e restituisce i risultati in un [XmlWriter](../../../system.xml/xmlwriter/). Il [XsltArgumentList](../../xsltargumentlist/) fornisce argomenti di esecuzione aggiuntivi.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un [XmlReader](../../../system.xml/xmlreader/) contenente il documento di input. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. Questo valore può essere **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Il [XmlWriter](../../../system.xml/xmlwriter/) su cui si desidera scrivere l'output. Se il foglio di stile contiene un elemento **xsl:output**, è necessario creare il [XmlWriter](../../../system.xml/xmlwriter/) usando l'oggetto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) restituito dal valore [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Questo garantisce che il [XmlWriter](../../../system.xml/xmlwriter/) abbia le impostazioni di output corrette. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Esegue la trasformazione utilizzando il documento di input specificato dall'oggetto [XmlReader](../../../system.xml/xmlreader/) e restituisce i risultati in un TextWriter. Il [XsltArgumentList](../../xsltargumentlist/) fornisce argomenti di esecuzione aggiuntivi.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un [XmlReader](../../../system.xml/xmlreader/) contenente il documento di input. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. Questo valore può essere **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Il TextWriter su cui si desidera scrivere l'output. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Esegue la trasformazione utilizzando il documento di input specificato dall'oggetto [XmlReader](../../../system.xml/xmlreader/) e restituisce i risultati in uno stream. Il [XsltArgumentList](../../xsltargumentlist/) fornisce argomenti di esecuzione aggiuntivi.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un [XmlReader](../../../system.xml/xmlreader/) contenente il documento di input. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. Questo valore può essere **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream su cui si desidera scrivere l'output. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) method

Esegue la trasformazione utilizzando il documento di input specificato dall'URI e restituisce i risultati in un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | L'URI del documento di input. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Il [XmlWriter](../../../system.xml/xmlwriter/) su cui si desidera scrivere l'output. Se il foglio di stile contiene un elemento **xsl:output**, è necessario creare il [XmlWriter](../../../system.xml/xmlwriter/) usando l'oggetto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) restituito dal valore [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Questo garantisce che il [XmlWriter](../../../system.xml/xmlwriter/) abbia le impostazioni di output corrette. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Esegue la trasformazione utilizzando il documento di input specificato dall'URI e restituisce i risultati in un [XmlWriter](../../../system.xml/xmlwriter/). Il [XsltArgumentList](../../xsltargumentlist/) fornisce argomenti di esecuzione aggiuntivi.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | L'URI del documento di input. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. Questo valore può essere **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Il [XmlWriter](../../../system.xml/xmlwriter/) su cui si desidera scrivere l'output. Se il foglio di stile contiene un elemento **xsl:output**, è necessario creare il [XmlWriter](../../../system.xml/xmlwriter/) usando l'oggetto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) restituito dal valore [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Questo garantisce che il [XmlWriter](../../../system.xml/xmlwriter/) abbia le impostazioni di output corrette. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Esegue la trasformazione utilizzando il documento di input specificato dall'URI e restituisce i risultati in un TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | L'URI del documento di input. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. Questo valore può essere **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Il TextWriter su cui si desidera scrivere l'output. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Esegue la trasformazione utilizzando il documento di input specificato dall'URI e restituisce i risultati in uno stream. Il [XsltArgumentList](../../xsltargumentlist/) fornisce argomenti di esecuzione aggiuntivi.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | L'URI del documento di input. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. Questo valore può essere **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Lo stream su cui si desidera scrivere l'output. |

## XslCompiledTransform::Transform(const String\&, const String\&) method

Esegue la trasformazione utilizzando il documento di input specificato dall'URI e restituisce i risultati in un file.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | L'URI del documento di input. |
| resultsFile | const [String](../../../system/string/)\& | L'URI del file di output. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method

Esegue la trasformazione utilizzando il documento di input specificato dall'oggetto [XmlReader](../../../system.xml/xmlreader/) e restituisce i risultati in un [XmlWriter](../../../system.xml/xmlwriter/). Il [XsltArgumentList](../../xsltargumentlist/) fornisce argomenti di esecuzione aggiuntivi e il [XmlResolver](../../../system.xml/xmlresolver/) risolve la funzione XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un [XmlReader](../../../system.xml/xmlreader/) contenente il documento di input. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenente gli argomenti qualificati per namespace usati come input per la trasformazione. Questo valore può essere **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Il [XmlWriter](../../../system.xml/xmlwriter/) su cui si desidera scrivere l'output. Se il foglio di stile contiene un elemento **xsl:output**, è necessario creare il [XmlWriter](../../../system.xml/xmlwriter/) usando l'oggetto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) restituito dal valore [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Questo garantisce che il [XmlWriter](../../../system.xml/xmlwriter/) abbia le impostazioni di output corrette. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) usato per risolvere la funzione XSLT **document()**. Se questo è **nullptr**, la funzione **document()** non viene risolta. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method

Esegue la trasformazione usando il documento di input specificato dall'oggetto IXPathNavigable e restituisce i risultati in un [XmlWriter](../../../system.xml/xmlwriter/). Il [XsltArgumentList](../../xsltargumentlist/) fornisce argomenti di esecuzione aggiuntivi e il [XmlResolver](../../../system.xml/xmlresolver/) risolve la funzione XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Il documento da trasformare specificato dall'oggetto IXPathNavigable. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Elenco di argomenti come [XsltArgumentList](../../xsltargumentlist/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Il [XmlWriter](../../../system.xml/xmlwriter/) su cui si desidera scrivere l'output. Se il foglio di stile contiene un elemento **xsl:output**, è necessario creare il [XmlWriter](../../../system.xml/xmlwriter/) usando l'oggetto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) restituito dal valore [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Questo garantisce che il [XmlWriter](../../../system.xml/xmlwriter/) abbia le impostazioni di output corrette. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) usato per risolvere la funzione XSLT **document()**. Se questo è **nullptr**, la funzione **document()** non viene risolta. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Classe [XmlWriter](../../../system.xml/xmlwriter/)
* Classe [XslCompiledTransform](../)
* Classe [XsltArgumentList](../../xsltargumentlist/)
* Classe [TextWriter](../../../system.io/textwriter/)
* Classe [Stream](../../../system.io/stream/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Classe [String](../../../system/string/)
* Classe [XmlResolver](../../../system.xml/xmlresolver/)
* Spazio dei nomi [System::Xml::Xsl](../../)
* Libreria [Aspose.Slides](../../../)