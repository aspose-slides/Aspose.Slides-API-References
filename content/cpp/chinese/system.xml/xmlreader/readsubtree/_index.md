---
title: ReadSubtree()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个新的 XmlReader 实例，可用于读取当前节点及其所有后代。
type: docs
weight: 963
url: /zh/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() 方法

返回一个新的 [XmlReader](../) 实例，可用于读取当前节点及其所有后代。

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```

### 返回值

一个新的 XML 阅读器实例，设置为 [ReadState::Initial](../../readstate/)。调用 [XmlReader::Read](../read/) 方法会将新阅读器定位在调用 [XmlReader::ReadSubtree](./) 方法之前的当前节点上。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)