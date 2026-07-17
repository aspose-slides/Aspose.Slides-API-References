---
title: Load()
second_title: Aspose.Slides C++ API 参考
description: 加载 XmlReader 中包含的 XSLT 样式表。
type: docs
weight: 27
url: /zh/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) 方法

加载包含在 [XmlReader](../../../system.xml/xmlreader/) 中的 XSLT 样式表。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 一个包含 XSLT 样式表的 [XmlReader](../../../system.xml/xmlreader/) 对象。 |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

加载包含在 [XmlReader](../../../system.xml/xmlreader/) 中的 XSLT 样式表。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 一个包含 XSLT 样式表的 [XmlReader](../../../system.xml/xmlreader/) 对象。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于加载 **xsl:import** 和 **xsl:include** 元素中引用的任何样式表的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值为 **nullptr**，则不会解析外部资源。此方法完成后，[XmlResolver](../../../system.xml/xmlresolver/) 不会被缓存。 |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) 方法

加载包含在 IXPathNavigable 中的 XSLT 样式表。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 实现 IXPathNavigable 接口的对象。它可以是 [XmlNode](../../../system.xml/xmlnode/)（通常是 [XmlDocument](../../../system.xml/xmldocument/)），也可以是包含 XSLT 样式表的 XPathDocument。 |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

加载包含在 IXPathNavigable 中的 XSLT 样式表。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 实现 IXPathNavigable 接口的对象。它可以是 [XmlNode](../../../system.xml/xmlnode/)（通常是 [XmlDocument](../../../system.xml/xmldocument/)），也可以是包含 XSLT 样式表的 XPathDocument。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于加载 **xsl:import** 和 **xsl:include** 元素中引用的任何样式表的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值为 **nullptr**，则不会解析外部资源。此方法完成后，[XmlResolver](../../../system.xml/xmlresolver/) 不会被缓存。 |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) 方法

加载包含在 XPathNavigator 中的 XSLT 样式表。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 一个包含 XSLT 样式表的 XPathNavigator 对象。 |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

加载包含在 XPathNavigator 中的 XSLT 样式表。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 一个包含 XSLT 样式表的 XPathNavigator 对象。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于加载 **xsl:import** 和 **xsl:include** 元素中引用的任何样式表的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值为 **nullptr**，则不会解析外部资源。此方法完成后，[XmlResolver](../../../system.xml/xmlresolver/) 不会被缓存。 |

## XslTransform::Load(const String\&) 方法

加载由 URL 指定的 XSLT 样式表。

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 指定要加载的 XSLT 样式表的 URL。 |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

加载由 URL 指定的 XSLT 样式表。

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 指定要加载的 XSLT 样式表的 URL。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于加载样式表以及 **xsl:import** 和 **xsl:include** 元素中引用的任何样式表的 [XmlResolver](../../../system.xml/xmlresolver/)。如果此值为 **nullptr**，则使用默认的 [XmlUrlResolver](../../../system.xml/xmlurlresolver/)（无用户凭据）打开样式表。默认的 [XmlUrlResolver](../../../system.xml/xmlurlresolver/) 不用于解析样式表中的任何外部资源，因此 **xsl:import** 和 **xsl:include** 元素不会被解析。此方法完成后，[XmlResolver](../../../system.xml/xmlresolver/) 不会被缓存。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlReader](../../../system.xml/xmlreader/)
* 类 [XslTransform](../)
* 类 [XmlResolver](../../../system.xml/xmlresolver/)
* 类 [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* 类 [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml::Xsl](../../)
* 库 [Aspose.Slides](../../../)