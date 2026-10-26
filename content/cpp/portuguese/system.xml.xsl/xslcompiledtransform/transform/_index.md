---
title: Transform()
second_title: Aspose.Slides para C++ Referência da API
description: Executa a transformação usando o documento de entrada especificado pelo objeto IXPathNavigable e envia os resultados para um XmlWriter.
type: docs
weight: 40
url: /pt/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) method


Executa a transformação usando o documento de entrada especificado pelo objeto IXPathNavigable e envia os resultados para um [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Um objeto que implementa a interface IXPathNavigable. Pode ser um [XmlNode](../../../system.xml/xmlnode/) (tipicamente um [XmlDocument](../../../system.xml/xmldocument/)) ou um XPathDocument contendo os dados a serem transformados. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | O [XmlWriter](../../../system.xml/xmlwriter/) para o qual você deseja enviar a saída. Se a folha de estilos contiver um elemento **xsl:output**, você deve criar o [XmlWriter](../../../system.xml/xmlwriter/) usando o objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) retornado do valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Isso garante que o [XmlWriter](../../../system.xml/xmlwriter/) tenha as configurações de saída corretas. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Executa a transformação usando o documento de entrada especificado pelo objeto IXPathNavigable e envia os resultados para um [XmlWriter](../../../system.xml/xmlwriter/). O [XsltArgumentList](../../xsltargumentlist/) fornece argumentos adicionais em tempo de execução.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Um objeto que implementa a interface IXPathNavigable. Pode ser um [XmlNode](../../../system.xml/xmlnode/) (tipicamente um [XmlDocument](../../../system.xml/xmldocument/)) ou um XPathDocument contendo os dados a serem transformados. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. Este valor pode ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | O [XmlWriter](../../../system.xml/xmlwriter/) para o qual você deseja enviar a saída. Se a folha de estilos contiver um elemento **xsl:output**, você deve criar o [XmlWriter](../../../system.xml/xmlwriter/) usando o objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) retornado do valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Isso garante que o [XmlWriter](../../../system.xml/xmlwriter/) tenha as configurações de saída corretas. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Executa a transformação usando o documento de entrada especificado pelo objeto IXPathNavigable e envia os resultados para um TextWriter. O [XsltArgumentList](../../xsltargumentlist/) fornece argumentos adicionais em tempo de execução.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Um objeto que implementa a interface IXPathNavigable. Pode ser um [XmlNode](../../../system.xml/xmlnode/) (tipicamente um [XmlDocument](../../../system.xml/xmldocument/)) ou um XPathDocument contendo os dados a serem transformados. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. Este valor pode ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | O TextWriter para o qual você deseja enviar a saída. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Executa a transformação usando o documento de entrada especificado pelo objeto IXPathNavigable e envia os resultados para um fluxo. O [XsltArgumentList](../../xsltargumentlist/) fornece argumentos adicionais em tempo de execução.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Um objeto que implementa a interface IXPathNavigable. Pode ser um [XmlNode](../../../system.xml/xmlnode/) (tipicamente um [XmlDocument](../../../system.xml/xmldocument/)) ou um XPathDocument contendo os dados a serem transformados. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. Este valor pode ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O fluxo para o qual você deseja enviar a saída. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) method


Executa a transformação usando o documento de entrada especificado pelo objeto [XmlReader](../../../system.xml/xmlreader/) e envia os resultados para um [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | O [XmlReader](../../../system.xml/xmlreader/) contendo o documento de entrada. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | O [XmlWriter](../../../system.xml/xmlwriter/) para o qual você deseja enviar a saída. Se a folha de estilos contiver um elemento **xsl:output**, você deve criar o [XmlWriter](../../../system.xml/xmlwriter/) usando o objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) retornado do valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Isso garante que o [XmlWriter](../../../system.xml/xmlwriter/) tenha as configurações de saída corretas. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Executa a transformação usando o documento de entrada especificado pelo objeto [XmlReader](../../../system.xml/xmlreader/) e envia os resultados para um [XmlWriter](../../../system.xml/xmlwriter/). O [XsltArgumentList](../../xsltargumentlist/) fornece argumentos adicionais em tempo de execução.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Um [XmlReader](../../../system.xml/xmlreader/) contendo o documento de entrada. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. Este valor pode ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | O [XmlWriter](../../../system.xml/xmlwriter/) para o qual você deseja enviar a saída. Se a folha de estilos contiver um elemento **xsl:output**, você deve criar o [XmlWriter](../../../system.xml/xmlwriter/) usando o objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) retornado do valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Isso garante que o [XmlWriter](../../../system.xml/xmlwriter/) tenha as configurações de saída corretas. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Executa a transformação usando o documento de entrada especificado pelo objeto [XmlReader](../../../system.xml/xmlreader/) e envia os resultados para um TextWriter. O [XsltArgumentList](../../xsltargumentlist/) fornece argumentos adicionais em tempo de execução.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Um [XmlReader](../../../system.xml/xmlreader/) contendo o documento de entrada. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. Este valor pode ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | O TextWriter para o qual você deseja enviar a saída. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Executa a transformação usando o documento de entrada especificado pelo objeto [XmlReader](../../../system.xml/xmlreader/) e envia os resultados para um fluxo. O [XsltArgumentList](../../xsltargumentlist/) fornece argumentos adicionais em tempo de execução.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Um [XmlReader](../../../system.xml/xmlreader/) contendo o documento de entrada. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. Este valor pode ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O fluxo para o qual você deseja enviar a saída. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) method


Executa a transformação usando o documento de entrada especificado pelo URI e envia os resultados para um [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | O URI do documento de entrada. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | O [XmlWriter](../../../system.xml/xmlwriter/) para o qual você deseja enviar a saída. Se a folha de estilos contiver um elemento **xsl:output**, você deve criar o [XmlWriter](../../../system.xml/xmlwriter/) usando o objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) retornado do valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Isso garante que o [XmlWriter](../../../system.xml/xmlwriter/) tenha as configurações de saída corretas. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Executa a transformação usando o documento de entrada especificado pelo URI e envia os resultados para um [XmlWriter](../../../system.xml/xmlwriter/). O [XsltArgumentList](../../xsltargumentlist/) fornece argumentos adicionais em tempo de execução.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | O URI do documento de entrada. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. Este valor pode ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | O [XmlWriter](../../../system.xml/xmlwriter/) para o qual você deseja enviar a saída. Se a folha de estilos contiver um elemento **xsl:output**, você deve criar o [XmlWriter](../../../system.xml/xmlwriter/) usando o objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) retornado do valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Isso garante que o [XmlWriter](../../../system.xml/xmlwriter/) tenha as configurações de saída corretas. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Executa a transformação usando o documento de entrada especificado pelo URI e envia os resultados para um TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | O URI do documento de entrada. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. Este valor pode ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | O TextWriter para o qual você deseja enviar a saída. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Executa a transformação usando o documento de entrada especificado pelo URI e envia os resultados para um fluxo. O [XsltArgumentList](../../xsltargumentlist/) fornece argumentos adicionais em tempo de execução.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | O URI do documento de entrada. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. Este valor pode ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O fluxo para o qual você deseja enviar a saída. |

## XslCompiledTransform::Transform(const String\&, const String\&) method


Executa a transformação usando o documento de entrada especificado pelo URI e envia os resultados para um arquivo.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | O URI do documento de entrada. |
| resultsFile | const [String](../../../system/string/)\& | O URI do arquivo de saída. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method


Executa a transformação usando o documento de entrada especificado pelo objeto [XmlReader](../../../system.xml/xmlreader/) e envia os resultados para um [XmlWriter](../../../system.xml/xmlwriter/). O [XsltArgumentList](../../xsltargumentlist/) fornece argumentos adicionais em tempo de execução e o [XmlResolver](../../../system.xml/xmlresolver/) resolve a função XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Um [XmlReader](../../../system.xml/xmlreader/) contendo o documento de entrada. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Um [XsltArgumentList](../../xsltargumentlist/) contendo os argumentos qualificados por namespace usados como entrada para a transformação. Este valor pode ser **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | O [XmlWriter](../../../system.xml/xmlwriter/) para o qual você deseja enviar a saída. Se a folha de estilos contiver um elemento **xsl:output**, você deve criar o [XmlWriter](../../../system.xml/xmlwriter/) usando o objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) retornado do valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Isso garante que o [XmlWriter](../../../system.xml/xmlwriter/) tenha as configurações de saída corretas. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver a função XSLT **document()**. Se for **nullptr**, a função **document()** não será resolvida. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method


Executa a transformação usando o documento de entrada especificado pelo objeto IXPathNavigable e envia os resultados para um [XmlWriter](../../../system.xml/xmlwriter/). O [XsltArgumentList](../../xsltargumentlist/) fornece argumentos adicionais em tempo de execução e o [XmlResolver](../../../system.xml/xmlresolver/) resolve a função XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | O documento a ser transformado que é especificado pelo objeto IXPathNavigable. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Lista de argumentos como [XsltArgumentList](../../xsltargumentlist/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | O [XmlWriter](../../../system.xml/xmlwriter/) para o qual você deseja enviar a saída. Se a folha de estilos contiver um elemento **xsl:output**, você deve criar o [XmlWriter](../../../system.xml/xmlwriter/) usando o objeto [XmlWriterSettings](../../../system.xml/xmlwritersettings/) que é retornado do valor [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Isso garante que o [XmlWriter](../../../system.xml/xmlwriter/) tenha as configurações de saída corretas. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver a função XSLT **document()**. Se for **nullptr**, a função **document()** não será resolvida. |

## Veja Também

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
* Namespace [System::Xml::Xsl](../../)
* Biblioteca [Aspose.Slides](../../../)