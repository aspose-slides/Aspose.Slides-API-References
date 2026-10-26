---
title: WriteNode()
second_title: Aspose.Slides for C++ API 参考
description: 当在派生类中重写时，复制读取器中的所有内容到写入器，并将读取器移动到下一个兄弟节点的开始位置。
type: docs
weight: 430
url: /zh/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) 方法

在派生类中重写时，复制读取器中的所有内容到写入器，并将读取器移动到下一个兄弟节点的开始位置。

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | 要读取的[XmlReader](../../xmlreader/)。 |
| defattr | **bool** | **true** 表示从[XmlReader](../../xmlreader/)复制默认属性；否则为 **false**。 |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) 方法

复制 XPathNavigator 对象中的所有内容到写入器。XPathNavigator 的位置保持不变。

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | 要复制的XPathNavigator。 |
| defattr | **bool** | **true** 表示复制默认属性；否则为 **false**。 |

## 另见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlReader](../../xmlreader/)
* 类 [XmlWriter](../)
* 类 [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)