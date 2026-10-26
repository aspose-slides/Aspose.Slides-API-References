---
title: Transform()
second_title: Référence de l'API Aspose.Slides pour C++
description: Exécute la transformation en utilisant le document d'entrée spécifié par l'objet IXPathNavigable et écrit les résultats dans un XmlWriter.
type: docs
weight: 40
url: /fr/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) method

Exécute la transformation en utilisant le document d’entrée spécifié par l’objet IXPathNavigable et écrit les résultats dans un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objet implémentant l’interface IXPathNavigable. Il peut s’agir d’un [XmlNode](../../../system.xml/xmlnode/) (généralement un [XmlDocument](../../../system.xml/xmldocument/)), ou d’un XPathDocument contenant les données à transformer. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Le [XmlWriter](../../../system.xml/xmlwriter/) vers lequel vous souhaitez écrire. Si la feuille de style contient un élément **xsl:output**, vous devez créer le [XmlWriter](../../../system.xml/xmlwriter/) à l’aide de l’objet [XmlWriterSettings](../../../system.xml/xmlwritersettings/) retourné par la valeur [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Cela garantit que le [XmlWriter](../../../system.xml/xmlwriter/) possède les paramètres de sortie corrects. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Exécute la transformation en utilisant le document d’entrée spécifié par l’objet IXPathNavigable et écrit les résultats dans un [XmlWriter](../../../system.xml/xmlwriter/). Le [XsltArgumentList](../../xsltargumentlist/) fournit des arguments d’exécution supplémentaires.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objet implémentant l’interface IXPathNavigable. Il peut s’agir d’un [XmlNode](../../../system.xml/xmlnode/) (généralement un [XmlDocument](../../../system.xml/xmldocument/)), ou d’un XPathDocument contenant les données à transformer. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l’espace de noms utilisés comme entrée pour la transformation. Cette valeur peut être **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Le [XmlWriter](../../../system.xml/xmlwriter/) vers lequel vous souhaitez écrire. Si la feuille de style contient un élément **xsl:output**, vous devez créer le [XmlWriter](../../../system.xml/xmlwriter/) à l’aide de l’objet [XmlWriterSettings](../../../system.xml/xmlwritersettings/) retourné par la valeur [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Cela garantit que le [XmlWriter](../../../system.xml/xmlwriter/) possède les paramètres de sortie corrects. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Exécute la transformation en utilisant le document d’entrée spécifié par l’objet IXPathNavigable et écrit les résultats dans un TextWriter. Le [XsltArgumentList](../../xsltargumentlist/) fournit des arguments d’exécution supplémentaires.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objet implémentant l’interface IXPathNavigable. Il peut s’agir d’un [XmlNode](../../../system.xml/xmlnode/) (généralement un [XmlDocument](../../../system.xml/xmldocument/)), ou d’un XPathDocument contenant les données à transformer. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l’espace de noms utilisés comme entrée pour la transformation. Cette valeur peut être **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Le TextWriter vers lequel vous souhaitez écrire. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Exécute la transformation en utilisant le document d’entrée spécifié par l’objet IXPathNavigable et écrit les résultats dans un flux. Le [XsltArgumentList](../../xsltargumentlist/) fournit des arguments d’exécution supplémentaires.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objet implémentant l’interface IXPathNavigable. Il peut s’agir d’un [XmlNode](../../../system.xml/xmlnode/) (généralement un [XmlDocument](../../../system.xml/xmldocument/)), ou d’un XPathDocument contenant les données à transformer. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l’espace de noms utilisés comme entrée pour la transformation. Cette valeur peut être **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux vers lequel vous souhaitez écrire. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) method

Exécute la transformation en utilisant le document d’entrée spécifié par l’objet [XmlReader](../../../system.xml/xmlreader/) et écrit les résultats dans un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Le [XmlReader](../../../system.xml/xmlreader/) contenant le document d’entrée. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Le [XmlWriter](../../../system.xml/xmlwriter/) vers lequel vous souhaitez écrire. Si la feuille de style contient un élément **xsl:output**, vous devez créer le [XmlWriter](../../../system.xml/xmlwriter/) à l’aide de l’objet [XmlWriterSettings](../../../system.xml/xmlwritersettings/) retourné par la valeur [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Cela garantit que le [XmlWriter](../../../system.xml/xmlwriter/) possède les paramètres de sortie corrects. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Exécute la transformation en utilisant le document d’entrée spécifié par l’objet [XmlReader](../../../system.xml/xmlreader/) et écrit les résultats dans un [XmlWriter](../../../system.xml/xmlwriter/). Le [XsltArgumentList](../../xsltargumentlist/) fournit des arguments d’exécution supplémentaires.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un [XmlReader](../../../system.xml/xmlreader/) contenant le document d’entrée. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l’espace de noms utilisés comme entrée pour la transformation. Cette valeur peut être **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Le [XmlWriter](../../../system.xml/xmlwriter/) vers lequel vous souhaitez écrire. Si la feuille de style contient un élément **xsl:output**, vous devez créer le [XmlWriter](../../../system.xml/xmlwriter/) à l’aide de l’objet [XmlWriterSettings](../../../system.xml/xmlwritersettings/) retourné par la valeur [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Cela garantit que le [XmlWriter](../../../system.xml/xmlwriter/) possède les paramètres de sortie corrects. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Exécute la transformation en utilisant le document d’entrée spécifié par l’objet [XmlReader](../../../system.xml/xmlreader/) et écrit les résultats dans un TextWriter. Le [XsltArgumentList](../../xsltargumentlist/) fournit des arguments d’exécution supplémentaires.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un [XmlReader](../../../system.xml/xmlreader/) contenant le document d’entrée. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l’espace de noms utilisés comme entrée pour la transformation. Cette valeur peut être **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Le TextWriter vers lequel vous souhaitez écrire. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Exécute la transformation en utilisant le document d’entrée spécifié par l’objet [XmlReader](../../../system.xml/xmlreader/) et écrit les résultats dans un flux. Le [XsltArgumentList](../../xsltargumentlist/) fournit des arguments d’exécution supplémentaires.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un [XmlReader](../../../system.xml/xmlreader/) contenant le document d’entrée. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l’espace de noms utilisés comme entrée pour la transformation. Cette valeur peut être **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux vers lequel vous souhaitez écrire. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) method

Exécute la transformation en utilisant le document d’entrée spécifié par l’URI et écrit les résultats dans un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | L’URI du document d’entrée. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Le [XmlWriter](../../../system.xml/xmlwriter/) vers lequel vous souhaitez écrire. Si la feuille de style contient un élément **xsl:output**, vous devez créer le [XmlWriter](../../../system.xml/xmlwriter/) à l’aide de l’objet [XmlWriterSettings](../../../system.xml/xmlwritersettings/) retourné par la valeur [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Cela garantit que le [XmlWriter](../../../system.xml/xmlwriter/) possède les paramètres de sortie corrects. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Exécute la transformation en utilisant le document d’entrée spécifié par l’URI et écrit les résultats dans un [XmlWriter](../../../system.xml/xmlwriter/). Le [XsltArgumentList](../../xsltargumentlist/) fournit des arguments d’exécution supplémentaires.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | L’URI du document d’entrée. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l’espace de noms utilisés comme entrée pour la transformation. Cette valeur peut être **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Le [XmlWriter](../../../system.xml/xmlwriter/) vers lequel vous souhaitez écrire. Si la feuille de style contient un élément **xsl:output**, vous devez créer le [XmlWriter](../../../system.xml/xmlwriter/) à l’aide de l’objet [XmlWriterSettings](../../../system.xml/xmlwritersettings/) retourné par la valeur [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Cela garantit que le [XmlWriter](../../../system.xml/xmlwriter/) possède les paramètres de sortie corrects. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Exécute la transformation en utilisant le document d’entrée spécifié par l’URI et écrit les résultats dans un TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | L’URI du document d’entrée. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l’espace de noms utilisés comme entrée pour la transformation. Cette valeur peut être **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Le TextWriter vers lequel vous souhaitez écrire. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Exécute la transformation en utilisant le document d’entrée spécifié par l’URI et écrit les résultats dans un flux. Le [XsltArgumentList](../../xsltargumentlist/) fournit des arguments d’exécution supplémentaires.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | L’URI du document d’entrée. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l’espace de noms utilisés comme entrée pour la transformation. Cette valeur peut être **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux vers lequel vous souhaitez écrire. |

## XslCompiledTransform::Transform(const String\&, const String\&) method

Exécute la transformation en utilisant le document d’entrée spécifié par l’URI et écrit les résultats dans un fichier.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | L’URI du document d’entrée. |
| resultsFile | const [String](../../../system/string/)\& | L’URI du fichier de sortie. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method

Exécute la transformation en utilisant le document d’entrée spécifié par l’objet [XmlReader](../../../system.xml/xmlreader/) et écrit les résultats dans un [XmlWriter](../../../system.xml/xmlwriter/). Le [XsltArgumentList](../../xsltargumentlist/) fournit des arguments d’exécution supplémentaires et le [XmlResolver](../../../system.xml/xmlresolver/) résout la fonction XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un [XmlReader](../../../system.xml/xmlreader/) contenant le document d’entrée. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l’espace de noms utilisés comme entrée pour la transformation. Cette valeur peut être **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Le [XmlWriter](../../../system.xml/xmlwriter/) vers lequel vous souhaitez écrire. Si la feuille de style contient un élément **xsl:output**, vous devez créer le [XmlWriter](../../../system.xml/xmlwriter/) à l’aide de l’objet [XmlWriterSettings](../../../system.xml/xmlwritersettings/) retourné par la valeur [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Cela garantit que le [XmlWriter](../../../system.xml/xmlwriter/) possède les paramètres de sortie corrects. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre la fonction XSLT **document()**. Si cette valeur est **nullptr**, la fonction **document()** n’est pas résolue. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method

Exécute la transformation en utilisant le document d’entrée spécifié par l’objet IXPathNavigable et écrit les résultats dans un [XmlWriter](../../../system.xml/xmlwriter/). Le [XsltArgumentList](../../xsltargumentlist/) fournit des arguments d’exécution supplémentaires et le [XmlResolver](../../../system.xml/xmlresolver/) résout la fonction XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Le document à transformer spécifié par l’objet IXPathNavigable. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Liste d’arguments en tant que [XsltArgumentList](../../xsltargumentlist/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Le [XmlWriter](../../../system.xml/xmlwriter/) vers lequel vous souhaitez écrire. Si la feuille de style contient un élément **xsl:output**, vous devez créer le [XmlWriter](../../../system.xml/xmlwriter/) en utilisant l’objet [XmlWriterSettings](../../../system.xml/xmlwritersettings/) retourné par la valeur [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Cela garantit que le [XmlWriter](../../../system.xml/xmlwriter/) possède les paramètres de sortie corrects. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre la fonction XSLT **document()**. Si cette valeur est **nullptr**, la fonction **document()** n’est pas résolue. |

## See Also

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
* Espace de noms [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)