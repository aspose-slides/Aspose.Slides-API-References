---
title: CanDeserialize()
second_title: Aspose.Slides for C++ API 参考
description: 检查特定读取器是否处于可反序列化状态。
type: docs
weight: 1
url: /zh/system.xml.serialization/xmlserializer/candeserialize/
---
## XmlSerializer::CanDeserialize(System::SharedPtr\<XmlReader\>) 方法

检查特定读取器是否处于可反序列化状态。

```cpp
virtual bool System::Xml::Serialization::XmlSerializer::CanDeserialize(System::SharedPtr<XmlReader> xmlReader)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 用于检查的读取器。 |

### 返回值

如果 xmlReader 可以反序列化则返回 true，否则返回 false。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlReader](../../../system.xml/xmlreader/)
* 类 [XmlSerializer](../)
* 命名空间 [System::Xml::Serialization](../../)
* 库 [Aspose.Slides](../../../)