---
title: Load()
second_title: Aspose.Slides C++ API 参考
description: 编译包含在 XmlReader 中的样式表。
type: docs
weight: 27
url: /zh/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) 方法

编译包含在 [XmlReader](../../../system.xml/xmlreader/) 中的样式表。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含样式表的 [XmlReader](../../../system.xml/xmlreader/)。 |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) 方法

编译包含在 [XmlReader](../../../system.xml/xmlreader/) 中的 XSLT 样式表。[XmlResolver](../../../system.xml/xmlresolver/) 解析任何 XSLT **import** 或 **include** 元素，XSLT 设置决定样式表的权限。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含样式表的 [XmlReader](../../../system.xml/xmlreader/)。 |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | 要应用于样式表的 [XsltSettings](../../xsltsettings/)。如果为 **nullptr**，则使用 [XsltSettings::get_Default](../../xsltsettings/get_default/) 设置。 |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于解析 XSLT **import** 和 **include** 元素中引用的任何样式表的 [XmlResolver](../../../system.xml/xmlresolver/)。如果为 **nullptr**，则不会解析外部资源。 |

## XslCompiledTransform::Load(const String\&) 方法

加载并编译位于指定 URI 的样式表。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | 样式表的 URI。 |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) 方法

加载并编译由 URI 指定的 XSLT 样式表。[XmlResolver](../../../system.xml/xmlresolver/) 解析任何 XSLT **import** 或 **include** 元素，XSLT 设置决定样式表的权限。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | 样式表的 URI。 |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | 要应用于样式表的 [XsltSettings](../../xsltsettings/)。如果为 **nullptr**，则使用 [XsltSettings::get_Default](../../xsltsettings/get_default/) 设置。 |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于解析样式表 URI 以及 XSLT **import** 和 **include** 元素中引用的任何样式表的 [XmlResolver](../../../system.xml/xmlresolver/)。 |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) 方法

编译包含在 IXPathNavigable 对象中的样式表。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 实现 IXPathNavigable 接口的对象。它可以是 [XmlNode](../../../system.xml/xmlnode/)（通常是 [XmlDocument](../../../system.xml/xmldocument/)），也可以是包含样式表的 XPathDocument。 |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) 方法

编译包含在 IXPathNavigable 中的 XSLT 样式表。[XmlResolver](../../../system.xml/xmlresolver/) 解析任何 XSLT **import** 或 **include** 元素，XSLT 设置决定样式表的权限。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 实现 IXPathNavigable 接口的对象。它可以是 [XmlNode](../../../system.xml/xmlnode/)（通常是 [XmlDocument](../../../system.xml/xmldocument/)），也可以是包含样式表的 XPathDocument。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | 要应用于样式表的 [XsltSettings](../../xsltsettings/)。如果为 **nullptr**，则使用 [XsltSettings::get_Default](../../xsltsettings/get_default/) 设置。 |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | 用于解析 XSLT **import** 和 **include** 元素中引用的任何样式表的 [XmlResolver](../../../system.xml/xmlresolver/)。如果为 **nullptr**，则不会解析外部资源。 |

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlReader](../../../system.xml/xmlreader/)
* 类 [XslCompiledTransform](../)
* 类 [XsltSettings](../../xsltsettings/)
* 类 [XmlResolver](../../../system.xml/xmlresolver/)
* 类 [String](../../../system/string/)
* 类 [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* 命名空间 [System::Xml::Xsl](../../)
* 库 [Aspose.Slides](../../../)