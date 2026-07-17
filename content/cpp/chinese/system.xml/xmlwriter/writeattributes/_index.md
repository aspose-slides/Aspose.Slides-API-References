---
title: WriteAttributes()
second_title: Aspose.Slides C++ API 参考
description: 当在派生类中被重写时，写出在 XmlReader 当前定位处找到的所有属性。
type: docs
weight: 417
url: /zh/system.xml/xmlwriter/writeattributes/
---
## XmlWriter::WriteAttributes(SharedPtr\<XmlReader\>, bool) 方法


当在派生类中被重写时，将写出在 [XmlReader](../../xmlreader/) 当前定位处找到的所有属性。

```cpp
virtual void System::Xml::XmlWriter::WriteAttributes(SharedPtr<XmlReader> reader, bool defattr)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | 从中复制属性的 [XmlReader](../../xmlreader/)。 |
| defattr | **bool** | **true** 表示从 [XmlReader](../../xmlreader/) 复制默认属性；否则为 **false**。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlReader](../../xmlreader/)
* 类 [XmlWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)