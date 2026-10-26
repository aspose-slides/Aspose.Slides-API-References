---
title: Load()
second_title: Aspose.Slides için C++ API Referansı
description: XmlReader içinde bulunan XSLT stil sayfasını yükler.
type: docs
weight: 27
url: /tr/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) yöntemi

[XmlReader](../../../system.xml/xmlreader/) içinde bulunan XSLT stil sayfasını yükler.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | XSLT stil sayfasını içeren bir [XmlReader](../../../system.xml/xmlreader/) nesnesi. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) yöntemi

[XmlReader](../../../system.xml/xmlreader/) içinde bulunan XSLT stil sayfasını yükler.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | XSLT stil sayfasını içeren bir [XmlReader](../../../system.xml/xmlreader/) nesnesi. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) herhangi bir stil sayfasını **xsl:import** ve **xsl:include** öğelerinde referans verilen stil sayfalarını yüklemek için kullanılır. Bu **nullptr** ise dış kaynaklar çözülmez. [XmlResolver](../../../system.xml/xmlresolver/) bu yöntemin tamamlanmasından sonra önbelleğe alınmaz. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) yöntemi

IXPathNavigable içinde bulunan XSLT stil sayfasını yükler.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. Bu, bir [XmlNode](../../../system.xml/xmlnode/) (genellikle bir [XmlDocument](../../../system.xml/xmldocument/)) ya da XSLT stil sayfasını içeren bir XPathDocument olabilir. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) yöntemi

IXPathNavigable içinde bulunan XSLT stil sayfasını yükler.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. Bu, bir [XmlNode](../../../system.xml/xmlnode/) (genellikle bir [XmlDocument](../../../system.xml/xmldocument/)) ya da XSLT stil sayfasını içeren bir XPathDocument olabilir. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) herhangi bir stil sayfasını **xsl:import** ve **xsl:include** öğelerinde referans verilen stil sayfalarını yüklemek için kullanılır. Bu **nullptr** ise dış kaynaklar çözülmez. [XmlResolver](../../../system.xml/xmlresolver/) bu yöntemin tamamlanmasından sonra önbelleğe alınmaz. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) yöntemi

XPathNavigator içinde bulunan XSLT stil sayfasını yükler.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XSLT stil sayfasını içeren bir XPathNavigator nesnesi. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) yöntemi

XPathNavigator içinde bulunan XSLT stil sayfasını yükler.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XSLT stil sayfasını içeren bir XPathNavigator nesnesi. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) herhangi bir stil sayfasını **xsl:import** ve **xsl:include** öğelerinde referans verilen stil sayfalarını yüklemek için kullanılır. Bu **nullptr** ise dış kaynaklar çözülmez. [XmlResolver](../../../system.xml/xmlresolver/) bu yöntemin tamamlanmasından sonra önbelleğe alınmaz. |

## XslTransform::Load(const String\&) yöntemi

Bir URL ile belirtilen XSLT stil sayfasını yükler.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Yüklemek için XSLT stil sayfasını belirten URL. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) yöntemi

Bir URL ile belirtilen XSLT stil sayfasını yükler.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Yüklemek için XSLT stil sayfasını belirten URL. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) stil sayfasını ve **xsl:import** ve **xsl:include** öğelerinde referans verilen stil sayfalarını yüklemek için kullanılır. Bu **nullptr** ise varsayılan bir [XmlUrlResolver](../../../system.xml/xmlurlresolver/) kullanıcı kimlik bilgileri olmadan stil sayfasını açmak için kullanılır. Varsayılan [XmlUrlResolver](../../../system.xml/xmlurlresolver/) stil sayfasındaki dış kaynakları çözmek için kullanılmaz, bu yüzden **xsl:import** ve **xsl:include** öğeleri çözülmez. [XmlResolver](../../../system.xml/xmlresolver/) bu yöntemin tamamlanmasından sonra önbelleğe alınmaz. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslTransform](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)