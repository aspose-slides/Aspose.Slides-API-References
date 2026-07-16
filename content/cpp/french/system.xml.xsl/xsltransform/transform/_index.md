---
title: Transform()
second_title: Référence de l'API Aspose.Slides pour C++
description: Transforme les données XML du XPathNavigator en utilisant les args spécifiés et écrit le résultat dans un XmlReader.
type: docs
weight: 40
url: /fr/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforme les données XML du XPathNavigator en utilisant les **args** spécifiés et écrit le résultat dans un [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator contenant les données à transformer. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l'espace de noms utilisés comme entrée pour la transformation. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre la fonction XSLT **document()**. Si c'est **nullptr**, la fonction **document()** n'est pas résolue. Le [XmlResolver](../../../system.xml/xmlresolver/) n'est pas mis en cache après l'exécution de cette méthode. |

### Valeur de retour

Un [XmlReader](../../../system.xml/xmlreader/) contenant les résultats de la transformation.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) method

Transforme les données XML du XPathNavigator en utilisant les **args** spécifiés et écrit le résultat dans un [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator contenant les données à transformer. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l'espace de noms utilisés comme entrée pour la transformation. |

### Valeur de retour

Un [XmlReader](../../../system.xml/xmlreader/) contenant les résultats de la transformation.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforme les données XML du XPathNavigator en utilisant les **args** spécifiés et écrit le résultat dans un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator contenant les données à transformer. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l'espace de noms utilisés comme entrée pour la transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Le [XmlWriter](../../../system.xml/xmlwriter/) vers lequel vous souhaitez écrire. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre la fonction XSLT **document()**. Si c'est **nullptr**, la fonction **document()** n'est pas résolue. Le [XmlResolver](../../../system.xml/xmlresolver/) n'est pas mis en cache après l'exécution de cette méthode. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Transforme les données XML du XPathNavigator en utilisant les **args** spécifiés et écrit le résultat dans un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator contenant les données à transformer. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l'espace de noms utilisés comme entrée pour la transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Le [XmlWriter](../../../system.xml/xmlwriter/) vers lequel vous souhaitez écrire. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforme les données XML du XPathNavigator en utilisant les **args** spécifiés et écrit le résultat dans un flux.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator contenant les données à transformer. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l'espace de noms utilisés comme entrée pour la transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux vers lequel vous souhaitez écrire. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre la fonction XSLT **document()**. Si c'est **nullptr**, la fonction **document()** n'est pas résolue. Le [XmlResolver](../../../system.xml/xmlresolver/) n'est pas mis en cache après l'exécution de cette méthode. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Transforme les données XML du XPathNavigator en utilisant les **args** spécifiés et écrit le résultat dans un flux.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator contenant les données à transformer. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l'espace de noms utilisés comme entrée pour la transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux vers lequel vous souhaitez écrire. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforme les données XML du XPathNavigator en utilisant les **args** spécifiés et écrit le résultat dans un TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator contenant les données à transformer. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l'espace de noms utilisés comme entrée pour la transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Le TextWriter vers lequel vous souhaitez écrire. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre la fonction XSLT **document()**. Si c'est **nullptr**, la fonction **document()** n'est pas résolue. Le [XmlResolver](../../../system.xml/xmlresolver/) n'est pas mis en cache après l'exécution de cette méthode. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Transforme les données XML du XPathNavigator en utilisant les **args** spécifiés et écrit le résultat dans un TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un XPathNavigator contenant les données à transformer. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l'espace de noms utilisés comme entrée pour la transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Le TextWriter vers lequel vous souhaitez écrire. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforme les données XML de l'IXPathNavigable en utilisant les **args** spécifiés et écrit le résultat dans un [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objet implémentant l'interface IXPathNavigable. Il peut s'agir soit d'un [XmlNode](../../../system.xml/xmlnode/) (généralement un [XmlDocument](../../../system.xml/xmldocument/)), soit d'un XPathDocument contenant les données à transformer. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l'espace de noms utilisés comme entrée pour la transformation. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre la fonction XSLT **document()**. Si c'est **nullptr**, la fonction **document()** n'est pas résolue. Le [XmlResolver](../../../system.xml/xmlresolver/) n'est pas mis en cache après l'exécution de cette méthode. |

### Valeur de retour

Un [XmlReader](../../../system.xml/xmlreader/) contenant les résultats de la transformation.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) method

Transforme les données XML de l'IXPathNavigable en utilisant les **args** spécifiés et écrit le résultat dans un [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objet implémentant l'interface IXPathNavigable. Il peut s'agir soit d'un [XmlNode](../../../system.xml/xmlnode/) (généralement un [XmlDocument](../../../system.xml/xmldocument/)), soit d'un XPathDocument contenant les données à transformer. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l'espace de noms utilisés comme entrée pour la transformation. |

### Valeur de retour

Un [XmlReader](../../../system.xml/xmlreader/) contenant les résultats de la transformation.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforme les données XML de l'IXPathNavigable en utilisant les **args** spécifiés et écrit le résultat dans un TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objet implémentant l'interface IXPathNavigable. Il peut s'agir soit d'un [XmlNode](../../../system.xml/xmlnode/) (généralement un [XmlDocument](../../../system.xml/xmldocument/)), soit d'un XPathDocument contenant les données à transformer. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l'espace de noms utilisés comme entrée pour la transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Le TextWriter vers lequel vous souhaitez écrire. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre la fonction XSLT **document()**. Si c'est **nullptr**, la fonction **document()** n'est pas résolue. Le [XmlResolver](../../../system.xml/xmlresolver/) n'est pas mis en cache après l'exécution de cette méthode. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Transforme les données XML de l'IXPathNavigable en utilisant les **args** spécifiés et écrit le résultat dans un TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objet implémentant l'interface IXPathNavigable. Il peut s'agir soit d'un [XmlNode](../../../system.xml/xmlnode/) (généralement un [XmlDocument](../../../system.xml/xmldocument/)), soit d'un XPathDocument contenant les données à transformer. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l'espace de noms utilisés comme entrée pour la transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Le TextWriter vers lequel vous souhaitez écrire. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforme les données XML de l'IXPathNavigable en utilisant les **args** spécifiés et écrit le résultat dans un flux.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objet implémentant l'interface IXPathNavigable. Il peut s'agir soit d'un [XmlNode](../../../system.xml/xmlnode/) (généralement un [XmlDocument](../../../system.xml/xmldocument/)), soit d'un XPathDocument contenant les données à transformer. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l'espace de noms utilisés comme entrée pour la transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux vers lequel vous souhaitez écrire. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre la fonction XSLT **document()**. Si c'est **nullptr**, la fonction **document()** n'est pas résolue. Le [XmlResolver](../../../system.xml/xmlresolver/) n'est pas mis en cache après l'exécution de la méthode [XslTransform::Transform](./). |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Transforme les données XML de l'IXPathNavigable en utilisant les **args** spécifiés et écrit le résultat dans un flux.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objet implémentant l'interface IXPathNavigable. Il peut s'agir soit d'un [XmlNode](../../../system.xml/xmlnode/) (généralement un [XmlDocument](../../../system.xml/xmldocument/)), soit d'un XPathDocument contenant les données à transformer. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l'espace de noms utilisés comme entrée pour la transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux vers lequel vous souhaitez écrire. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforme les données XML de l'IXPathNavigable en utilisant les **args** spécifiés et écrit le résultat dans un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objet implémentant l'interface IXPathNavigable. Il peut s'agir soit d'un [XmlNode](../../../system.xml/xmlnode/) (généralement un [XmlDocument](../../../system.xml/xmldocument/)), soit d'un XPathDocument contenant les données à transformer. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l'espace de noms utilisés comme entrée pour la transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Le [XmlWriter](../../../system.xml/xmlwriter/) vers lequel vous souhaitez écrire. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre la fonction XSLT **document()**. Si c'est **nullptr**, la fonction **document()** n'est pas résolue. Le [XmlResolver](../../../system.xml/xmlresolver/) n'est pas mis en cache après l'exécution de cette méthode. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Transforme les données XML de l'IXPathNavigable en utilisant les **args** spécifiés et écrit le résultat dans un [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objet implémentant l'interface IXPathNavigable. Il peut s'agir soit d'un [XmlNode](../../../system.xml/xmlnode/) (généralement un [XmlDocument](../../../system.xml/xmldocument/)), soit d'un XPathDocument contenant les données à transformer. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Un [XsltArgumentList](../../xsltargumentlist/) contenant les arguments qualifiés par l'espace de noms utilisés comme entrée pour la transformation. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Le [XmlWriter](../../../system.xml/xmlwriter/) vers lequel vous souhaitez écrire. |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

Transforme les données XML du fichier d'entrée et écrit le résultat dans un fichier de sortie.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | L'URL du document source à transformer. |
| outputfile | const [String](../../../system/string/)\& | L'URL du fichier de sortie. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre la fonction XSLT **document()**. Si c'est **nullptr**, la fonction **document()** n'est pas résolue. Le [XmlResolver](../../../system.xml/xmlresolver/) n'est pas mis en cache après l'exécution de la méthode [XslTransform::Transform](./). |

## XslTransform::Transform(const String\&, const String\&) method

Transforme les données XML du fichier d'entrée et écrit le résultat dans un fichier de sortie.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | L'URL du document à transformer. |
| outputfile | const [String](../../../system/string/)\& | L'URL du fichier de sortie. |

## Voir aussi

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
* Espace de noms [System::Xml::Xsl](../../)
* Bibliothèque [Aspose.Slides](../../../)