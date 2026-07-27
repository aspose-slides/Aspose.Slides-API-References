---
title: Transform()
second_title: Referência da API Aspose.Slides para C++
description: Transforma os dados XML no XPathNavigator usando os args especificados e grava o resultado em um XmlReader.
type: docs
weight: 40
url: /pt/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método


Transforma os dados XML no XPathNavigator usando os **args** especificados e grava o resultado em um [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Um XPathNavigator contendo os dados a serem transformados. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver a função **document()** do XSLT. Se for **nullptr**, a função **document()** não será resolvida. O [XmlResolver](../../../system.xml/xmlresolver/) não é armazenado em cache após a conclusão deste método. |

### Valor de Retorno

Um [XmlReader](../../../system.xml/xmlreader/) contendo os resultados da transformação.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) método


Transforma os dados XML no XPathNavigator usando os **args** especificados e grava o resultado em um [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Um XPathNavigator contendo os dados a serem transformados. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. |

### Valor de Retorno

Um [XmlReader](../../../system.xml/xmlreader/) contendo os resultados da transformação.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método


Transforma os dados XML no XPathNavigator usando os **args** especificados e grava o resultado em um [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Um XPathNavigator contendo os dados a serem transformados. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | O [XmlWriter](../../../system.xml/xmlwriter/) para o qual você deseja gravar a saída. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver a função **document()** do XSLT. Se for **nullptr**, a função **document()** não será resolvida. O [XmlResolver](../../../system.xml/xmlresolver/) não é armazenado em cache após a conclusão deste método. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) método


Transforma os dados XML no XPathNavigator usando os **args** especificados e grava o resultado em um [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Um XPathNavigator contendo os dados a serem transformados. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | O [XmlWriter](../../../system.xml/xmlwriter/) para o qual você deseja gravar a saída. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método


Transforma os dados XML no XPathNavigator usando os **args** especificados e grava o resultado em um Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Um XPathNavigator contendo os dados a serem transformados. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O stream para o qual você deseja gravar a saída. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver a função **document()** do XSLT. Se for **nullptr**, a função **document()** não será resolvida. O [XmlResolver](../../../system.xml/xmlresolver/) não é armazenado em cache após a conclusão deste método. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) método


Transforma os dados XML no XPathNavigator usando os **args** especificados e grava o resultado em um Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Um XPathNavigator contendo os dados a serem transformados. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O stream para o qual você deseja gravar a saída. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método


Transforma os dados XML no XPathNavigator usando os **args** especificados e grava o resultado em um TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Um XPathNavigator contendo os dados a serem transformados. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | O TextWriter para o qual você deseja gravar a saída. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver a função **document()** do XSLT. Se for **nullptr**, a função **document()** não será resolvida. O [XmlResolver](../../../system.xml/xmlresolver/) não é armazenado em cache após a conclusão deste método. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) método


Transforma os dados XML no XPathNavigator usando os **args** especificados e grava o resultado em um TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Um XPathNavigator contendo os dados a serem transformados. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | O TextWriter para o qual você deseja gravar a saída. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método


Transforma os dados XML no IXPathNavigable usando os **args** especificados e grava o resultado em um [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Um objeto que implementa a interface IXPathNavigable. Pode ser um [XmlNode](../../../system.xml/xmlnode/) (tipicamente um [XmlDocument](../../../system.xml/xmldocument/)) ou um XPathDocument contendo os dados a serem transformados. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver a função **document()** do XSLT. Se for **nullptr**, a função **document()** não será resolvida. O [XmlResolver](../../../system.xml/xmlresolver/) não é armazenado em cache após a conclusão deste método. |

### Valor de Retorno

Um [XmlReader](../../../system.xml/xmlreader/) contendo os resultados da transformação.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) método


Transforma os dados XML no IXPathNavigable usando os **args** especificados e grava o resultado em um [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Um objeto que implementa a interface IXPathNavigable. Pode ser um [XmlNode](../../../system.xml/xmlnode/) (tipicamente um [XmlDocument](../../../system.xml/xmldocument/)) ou um XPathDocument contendo os dados a serem transformados. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. |

### Valor de Retorno

Um [XmlReader](../../../system.xml/xmlreader/) contendo os resultados da transformação.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método


Transforma os dados XML no IXPathNavigable usando os **args** especificados e grava o resultado em um TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Um objeto que implementa a interface IXPathNavigable. Pode ser um [XmlNode](../../../system.xml/xmlnode/) (tipicamente um [XmlDocument](../../../system.xml/xmldocument/)) ou um XPathDocument contendo os dados a serem transformados. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | O TextWriter para o qual você deseja gravar a saída. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver a função **document()** do XSLT. Se for **nullptr**, a função **document()** não será resolvida. O [XmlResolver](../../../system.xml/xmlresolver/) não é armazenado em cache após a conclusão deste método. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) método


Transforma os dados XML no IXPathNavigable usando os **args** especificados e grava o resultado em um TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Um objeto que implementa a interface IXPathNavigable. Pode ser um [XmlNode](../../../system.xml/xmlnode/) (tipicamente um [XmlDocument](../../../system.xml/xmldocument/)) ou um XPathDocument contendo os dados a serem transformados. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | O TextWriter para o qual você deseja gravar a saída. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método


Transforma os dados XML no IXPathNavigable usando os **args** especificados e grava o resultado em um Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Um objeto que implementa a interface IXPathNavigable. Pode ser um [XmlNode](../../../system.xml/xmlnode/) (tipicamente um [XmlDocument](../../../system.xml/xmldocument/)) ou um XPathDocument contendo os dados a serem transformados. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O stream para o qual você deseja gravar a saída. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver a função **document()** do XSLT. Se for **nullptr**, a função **document()** não será resolvida. O [XmlResolver](../../../system.xml/xmlresolver/) não é armazenado em cache após a conclusão do método [XslTransform::Transform](./). |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) método


Transforma os dados XML no IXPathNavigable usando os **args** especificados e grava o resultado em um Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Um objeto que implementa a interface IXPathNavigable. Pode ser um [XmlNode](../../../system.xml/xmlnode/) (tipicamente um [XmlDocument](../../../system.xml/xmldocument/)) ou um XPathDocument contendo os dados a serem transformados. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O stream para o qual você deseja gravar a saída. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método


Transforma os dados XML no IXPathNavigable usando os **args** especificados e grava o resultado em um [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Um objeto que implementa a interface IXPathNavigable. Pode ser um [XmlNode](../../../system.xml/xmlnode/) (tipicamente um [XmlDocument](../../../system.xml/xmldocument/)) ou um XPathDocument contendo os dados a serem transformados. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | O [XmlWriter](../../../system.xml/xmlwriter/) para o qual você deseja gravar a saída. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver a função **document()** do XSLT. Se for **nullptr**, a função **document()** não será resolvida. O [XmlResolver](../../../system.xml/xmlresolver/) não é armazenado em cache após a conclusão deste método. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) método


Transforma os dados XML no IXPathNavigable usando os **args** especificados e grava o resultado em um [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Um objeto que implementa a interface IXPathNavigable. Pode ser um [XmlNode](../../../system.xml/xmlnode/) (tipicamente um [XmlDocument](../../../system.xml/xmldocument/)) ou um XPathDocument contendo os dados a serem transformados. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | O [XmlWriter](../../../system.xml/xmlwriter/) para o qual você deseja gravar a saída. |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método


Transforma os dados XML no arquivo de entrada e grava o resultado em um arquivo de saída.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | A URL do documento de origem a ser transformado. |
| outputfile | const [String](../../../system/string/)\& | A URL do arquivo de saída. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver a função **document()** do XSLT. Se for **nullptr**, a função **document()** não será resolvida. O [XmlResolver](../../../system.xml/xmlresolver/) não é armazenado em cache após a conclusão do método [XslTransform::Transform](./). |

## XslTransform::Transform(const String\&, const String\&) método


Transforma os dados XML no arquivo de entrada e grava o resultado em um arquivo de saída.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | A URL do documento de origem a ser transformado. |
| outputfile | const [String](../../../system/string/)\& | A URL do arquivo de saída. |

## Veja Também

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
* Espaço de nomes [System::Xml::Xsl](../../)
* Biblioteca [Aspose.Slides](../../../)