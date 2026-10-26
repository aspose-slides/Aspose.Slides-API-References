---
title: Transform()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的 args 对 XPathNavigator 中的 XML 数据进行转换，并将结果输出到 XmlReader。
type: docs
weight: 40
url: /zh/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

使用指定的 **args** 对 XPathNavigator 中的 XML 数据进行转换，并将结果输出到一个[XmlReader](../../../system.xml/xmlreader/)。

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 包含要转换的数据的 XPathNavigator。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 一个包含用于转换输入的带命名空间限定的参数的[XsltArgumentList](../../xsltargumentlist/)。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于解析 XSLT **document()** 函数的[XmlResolver](../../../system.xml/xmlresolver/)。如果该对象为 **nullptr**，则不会解析 **document()** 函数。该[XmlResolver](../../../system.xml/xmlresolver/)在此方法完成后不会被缓存。 |

### 返回值

一个包含转换结果的[XmlReader](../../../system.xml/xmlreader/)。

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) 方法

使用指定的 **args** 对 XPathNavigator 中的 XML 数据进行转换，并将结果输出到一个[XmlReader](../../../system.xml/xmlreader/)。

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 包含要转换的数据的 XPathNavigator。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 一个包含用于转换输入的带命名空间限定的参数的[XsltArgumentList](../../xsltargumentlist/)。 |

### 返回值

一个包含转换结果的[XmlReader](../../../system.xml/xmlreader/)。

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

使用指定的 **args** 对 XPathNavigator 中的 XML 数据进行转换，并将结果输出到一个[XmlWriter](../../../system.xml/xmlwriter/)。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 包含要转换的数据的 XPathNavigator。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 一个包含用于转换输入的带命名空间限定的参数的[XsltArgumentList](../../xsltargumentlist/)。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 要输出的[XmlWriter](../../../system.xml/xmlwriter/)。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于解析 XSLT **document()** 函数的[XmlResolver](../../../system.xml/xmlresolver/)。如果该对象为 **nullptr**，则不会解析 **document()** 函数。该[XmlResolver](../../../system.xml/xmlresolver/)在此方法完成后不会被缓存。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) 方法

使用指定的 **args** 对 XPathNavigator 中的 XML 数据进行转换，并将结果输出到一个[XmlWriter](../../../system.xml/xmlwriter/)。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 包含要转换的数据的 XPathNavigator。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 一个包含用于转换输入的带命名空间限定的参数的[XsltArgumentList](../../xsltargumentlist/)。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 要输出的[XmlWriter](../../../system.xml/xmlwriter/)。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

使用指定的 **args** 对 XPathNavigator 中的 XML 数据进行转换，并将结果输出到一个流。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 包含要转换的数据的 XPathNavigator。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 一个包含用于转换输入的带命名空间限定的参数的[XsltArgumentList](../../xsltargumentlist/)。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 要输出的流。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于解析 XSLT **document()** 函数的[XmlResolver](../../../system.xml/xmlresolver/)。如果该对象为 **nullptr**，则不会解析 **document()** 函数。该[XmlResolver](../../../system.xml/xmlresolver/)在此方法完成后不会被缓存。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) 方法

使用指定的 **args** 对 XPathNavigator 中的 XML 数据进行转换，并将结果输出到一个流。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 包含要转换的数据的 XPathNavigator。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 一个包含用于转换输入的带命名空间限定的参数的[XsltArgumentList](../../xsltargumentlist/)。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 要输出的流。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

使用指定的 **args** 对 XPathNavigator 中的 XML 数据进行转换，并将结果输出到一个 TextWriter。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 包含要转换的数据的 XPathNavigator。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 一个包含用于转换输入的带命名空间限定的参数的[XsltArgumentList](../../xsltargumentlist/)。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 要输出的 TextWriter。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于解析 XSLT **document()** 函数的[XmlResolver](../../../system.xml/xmlresolver/)。如果该对象为 **nullptr**，则不会解析 **document()** 函数。该[XmlResolver](../../../system.xml/xmlresolver/)在此方法完成后不会被缓存。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) 方法

使用指定的 **args** 对 XPathNavigator 中的 XML 数据进行转换，并将结果输出到一个 TextWriter。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | 包含要转换的数据的 XPathNavigator。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 一个包含用于转换输入的带命名空间限定的参数的[XsltArgumentList](../../xsltargumentlist/)。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 要输出的 TextWriter。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

使用指定的 **args** 对 IXPathNavigable 中的 XML 数据进行转换，并将结果输出到一个[XmlReader](../../../system.xml/xmlreader/)。

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 实现 IXPathNavigable 接口的对象。它可以是一个[XmlNode](../../../system.xml/xmlnode/)（通常是[XmlDocument](../../../system.xml/xmldocument/)），也可以是包含要转换数据的 XPathDocument。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 一个包含用于转换输入的带命名空间限定的参数的[XsltArgumentList](../../xsltargumentlist/)。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于解析 XSLT **document()** 函数的[XmlResolver](../../../system.xml/xmlresolver/)。如果该对象为 **nullptr**，则不会解析 **document()** 函数。该[XmlResolver](../../../system.xml/xmlresolver/)在此方法完成后不会被缓存。 |

### 返回值

一个包含转换结果的[XmlReader](../../../system.xml/xmlreader/)。

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) 方法

使用指定的 **args** 对 IXPathNavigable 中的 XML 数据进行转换，并将结果输出到一个[XmlReader](../../../system.xml/xmlreader/)。

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 实现 IXPathNavigable 接口的对象。它可以是一个[XmlNode](../../../system.xml/xmlnode/)（通常是[XmlDocument](../../../system.xml/xmldocument/)），也可以是包含要转换数据的 XPathDocument。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 一个包含用于转换输入的带命名空间限定的参数的[XsltArgumentList](../../xsltargumentlist/)。 |

### 返回值

一个包含转换结果的[XmlReader](../../../system.xml/xmlreader/)。

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

使用指定的 **args** 对 IXPathNavigable 中的 XML 数据进行转换，并将结果输出到一个 TextWriter。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 实现 IXPathNavigable 接口的对象。它可以是一个[XmlNode](../../../system.xml/xmlnode/)（通常是[XmlDocument](../../../system.xml/xmldocument/)），也可以是包含要转换数据的 XPathDocument。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 一个包含用于转换输入的带命名空间限定的参数的[XsltArgumentList](../../xsltargumentlist/)。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 要输出的 TextWriter。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于解析 XSLT **document()** 函数的[XmlResolver](../../../system.xml/xmlresolver/)。如果该对象为 **nullptr**，则不会解析 **document()** 函数。该[XmlResolver](../../../system.xml/xmlresolver/)在此方法完成后不会被缓存。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) 方法

使用指定的 **args** 对 IXPathNavigable 中的 XML 数据进行转换，并将结果输出到一个 TextWriter。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 实现 IXPathNavigable 接口的对象。它可以是一个[XmlNode](../../../system.xml/xmlnode/)（通常是[XmlDocument](../../../system.xml/xmldocument/)），也可以是包含要转换数据的 XPathDocument。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 一个包含用于转换输入的带命名空间限定的参数的[XsltArgumentList](../../xsltargumentlist/)。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 要输出的 TextWriter。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

使用指定的 **args** 对 IXPathNavigable 中的 XML 数据进行转换，并将结果输出到一个流。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 实现 IXPathNavigable 接口的对象。它可以是一个[XmlNode](../../../system.xml/xmlnode/)（通常是[XmlDocument](../../../system.xml/xmldocument/)），也可以是包含要转换数据的 XPathDocument。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 一个包含用于转换输入的带命名空间限定的参数的[XsltArgumentList](../../xsltargumentlist/)。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 要输出的流。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于解析 XSLT **document()** 函数的[XmlResolver](../../../system.xml/xmlresolver/)。如果该对象为 **nullptr**，则不会解析 **document()** 函数。该[XmlResolver](../../../system.xml/xmlresolver/)在此[XslTransform::Transform](./)方法完成后不会被缓存。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) 方法

使用指定的 **args** 对 IXPathNavigable 中的 XML 数据进行转换，并将结果输出到一个流。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 实现 IXPathNavigable 接口的对象。它可以是一个[XmlNode](../../../system.xml/xmlnode/)（通常是[XmlDocument](../../../system.xml/xmldocument/)），也可以是包含要转换数据的 XPathDocument。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 一个包含用于转换输入的带命名空间限定的参数的[XsltArgumentList](../../xsltargumentlist/)。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 要输出的流。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

使用指定的 **args** 对 IXPathNavigable 中的 XML 数据进行转换，并将结果输出到一个[XmlWriter](../../../system.xml/xmlwriter/)。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 实现 IXPathNavigable 接口的对象。它可以是一个[XmlNode](../../../system.xml/xmlnode/)（通常是[XmlDocument](../../../system.xml/xmldocument/)），也可以是包含要转换数据的 XPathDocument。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 一个包含用于转换输入的带命名空间限定的参数的[XsltArgumentList](../../xsltargumentlist/)。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 要输出的[XmlWriter](../../../system.xml/xmlwriter/)。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于解析 XSLT **document()** 函数的[XmlResolver](../../../system.xml/xmlresolver/)。如果该对象为 **nullptr**，则不会解析 **document()** 函数。该[XmlResolver](../../../system.xml/xmlresolver/)在此方法完成后不会被缓存。 |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) 方法

使用指定的 **args** 对 IXPathNavigable 中的 XML 数据进行转换，并将结果输出到一个[XmlWriter](../../../system.xml/xmlwriter/)。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | 实现 IXPathNavigable 接口的对象。它可以是一个[XmlNode](../../../system.xml/xmlnode/)（通常是[XmlDocument](../../../system.xml/xmldocument/)），也可以是包含要转换数据的 XPathDocument。 |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 一个包含用于转换输入的带命名空间限定的参数的[XsltArgumentList](../../xsltargumentlist/)。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 要输出的[XmlWriter](../../../system.xml/xmlwriter/)。 |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

对输入文件中的 XML 数据进行转换，并将结果输出到输出文件。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | 要转换的源文档的 URL。 |
| outputfile | const [String](../../../system/string/)\& | 输出文件的 URL。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于解析 XSLT **document()** 函数的[XmlResolver](../../../system.xml/xmlresolver/)。如果该对象为 **nullptr**，则不会解析 **document()** 函数。该[XmlResolver](../../../system.xml/xmlresolver/)在此[XslTransform::Transform](./)方法完成后不会被缓存。 |

## XslTransform::Transform(const String\&, const String\&) 方法

对输入文件中的 XML 数据进行转换，并将结果输出到输出文件。

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | 要转换的源文档的 URL。 |
| outputfile | const [String](../../../system/string/)\& | 输出文件的 URL。 |

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)