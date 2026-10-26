---
title: get_OldValue()
second_title: Aspose.Slides C++ API 参考
description: 返回节点的原始值。
type: docs
weight: 53
url: /zh/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() method


返回节点的原始值。

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### 返回值

节点的原始值。如果节点既不是属性也不是文本节点，或正在插入节点，则此方法返回 **nullptr**。如果在 **XmlDocument::NodeChanging** 事件中调用，**get_OldValue** 返回将在更改成功时被替换的节点的当前值。如果在 **XmlDocument::NodeChanged** 事件中调用，**get_OldValue** 返回更改前节点的值。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlNodeChangedEventArgs](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)