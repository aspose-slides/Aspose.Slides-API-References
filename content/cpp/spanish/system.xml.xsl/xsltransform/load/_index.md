---
title: Load()
second_title: Referencia de API de Aspose.Slides para C++
description: Carga la hoja de estilo XSLT contenida en el XmlReader.
type: docs
weight: 27
url: /es/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) método


Carga la hoja de estilo XSLT contenida en el [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un objeto [XmlReader](../../../system.xml/xmlreader/) que contiene la hoja de estilo XSLT. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método


Carga la hoja de estilo XSLT contenida en el [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un objeto [XmlReader](../../../system.xml/xmlreader/) que contiene la hoja de estilo XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) utilizado para cargar cualquier hoja de estilo referenciada en los elementos **xsl:import** y **xsl:include**. Si es **nullptr**, los recursos externos no se resuelven. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método se completa. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) método


Carga la hoja de estilo XSLT contenida en el IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)) o un XPathDocument que contiene la hoja de estilo XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método


Carga la hoja de estilo XSLT contenida en el IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)) o un XPathDocument que contiene la hoja de estilo XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) utilizado para cargar cualquier hoja de estilo referenciada en los elementos **xsl:import** y **xsl:include**. Si es **nullptr**, los recursos externos no se resuelven. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método se completa. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) método


Carga la hoja de estilo XSLT contenida en el XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un objeto XPathNavigator que contiene la hoja de estilo XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método


Carga la hoja de estilo XSLT contenida en el XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un objeto XPathNavigator que contiene la hoja de estilo XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) utilizado para cargar cualquier hoja de estilo referenciada en los elementos **xsl:import** y **xsl:include**. Si es **nullptr**, los recursos externos no se resuelven. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método se completa. |

## XslTransform::Load(const String\&) método


Carga la hoja de estilo XSLT especificada por una URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | La URL que especifica la hoja de estilo XSLT a cargar. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) método


Carga la hoja de estilo XSLT especificada por una URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | La URL que especifica la hoja de estilo XSLT a cargar. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) que se usa para cargar la hoja de estilo y cualquier hoja(s) de estilo referenciada(s) en los elementos **xsl:import** y **xsl:include**. Si es **nullptr**, se usa un [XmlUrlResolver](../../../system.xml/xmlurlresolver/) predeterminado sin credenciales de usuario para abrir la hoja de estilo. El [XmlUrlResolver](../../../system.xml/xmlurlresolver/) predeterminado no se utiliza para resolver recursos externos en la hoja de estilo, por lo que los elementos **xsl:import** y **xsl:include** no se resuelven. El [XmlResolver](../../../system.xml/xmlresolver/) no se almacena en caché después de que este método se completa. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslTransform](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)