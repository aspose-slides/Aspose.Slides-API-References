---
title: Load()
second_title: Referência da API Aspose.Slides para C++
description: Carrega a folha de estilo XSLT contida no XmlReader.
type: docs
weight: 27
url: /pt/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) método

Carrega a folha de estilo XSLT contida no [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Um objeto [XmlReader](../../../system.xml/xmlreader/) que contém a folha de estilo XSLT. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método

Carrega a folha de estilo XSLT contida no [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Um objeto [XmlReader](../../../system.xml/xmlreader/) que contém a folha de estilo XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para carregar quaisquer folhas de estilo referenciadas nos elementos **xsl:import** e **xsl:include**. Se for **nullptr**, recursos externos não são resolvidos. O [XmlResolver](../../../system.xml/xmlresolver/) não é armazenado em cache após a conclusão deste método. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) método

Carrega a folha de estilo XSLT contida no IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Um objeto que implementa a interface IXPathNavigable. Pode ser um [XmlNode](../../../system.xml/xmlnode/) (tipicamente um [XmlDocument](../../../system.xml/xmldocument/)) ou um XPathDocument contendo a folha de estilo XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método

Carrega a folha de estilo XSLT contida no IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Um objeto que implementa a interface IXPathNavigable. Pode ser um [XmlNode](../../../system.xml/xmlnode/) (tipicamente um [XmlDocument](../../../system.xml/xmldocument/)) ou um XPathDocument contendo a folha de estilo XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para carregar quaisquer folhas de estilo referenciadas nos elementos **xsl:import** e **xsl:include**. Se for **nullptr**, recursos externos não são resolvidos. O [XmlResolver](../../../system.xml/xmlresolver/) não é armazenado em cache após a conclusão deste método. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) método

Carrega a folha de estilo XSLT contida no XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Um objeto XPathNavigator que contém a folha de estilo XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método

Carrega a folha de estilo XSLT contida no XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Um objeto XPathNavigator que contém a folha de estilo XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para carregar quaisquer folhas de estilo referenciadas nos elementos **xsl:import** e **xsl:include**. Se for **nullptr**, recursos externos não são resolvidos. O [XmlResolver](../../../system.xml/xmlresolver/) não é armazenado em cache após a conclusão deste método. |

## XslTransform::Load(const String\&) método

Carrega a folha de estilo XSLT especificada por uma URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | A URL que especifica a folha de estilo XSLT a ser carregada. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método

Carrega a folha de estilo XSLT especificada por uma URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | A URL que especifica a folha de estilo XSLT a ser carregada. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) a ser usado para carregar a folha de estilo e quaisquer folha(s) de estilo referenciadas nos elementos **xsl:import** e **xsl:include**. Se for **nullptr**, um [XmlUrlResolver](../../../system.xml/xmlurlresolver/) padrão sem credenciais de usuário é usado para abrir a folha de estilo. O [XmlUrlResolver](../../../system.xml/xmlurlresolver/) padrão não é usado para resolver quaisquer recursos externos na folha de estilo, portanto os elementos **xsl:import** e **xsl:include** não são resolvidos. O [XmlResolver](../../../system.xml/xmlresolver/) não é armazenado em cache após a conclusão deste método. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Classe [XslTransform](../)
* Classe [XmlResolver](../../../system.xml/xmlresolver/)
* Classe [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Classe [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Classe [String](../../../system/string/)
* Namespace [System::Xml::Xsl](../../)
* Biblioteca [Aspose.Slides](../../../)