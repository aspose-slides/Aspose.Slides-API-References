---
title: get_NewValue()
second_title: Aspose.Slides C++ API 参考
description: 返回节点的新值。
type: docs
weight: 66
url: /zh/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() 方法


返回节点的新值。

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```


### 返回值

节点的新值。若节点既不是属性也不是文本节点，或者节点正在被删除，则此方法返回 **nullptr**。如果在 **XmlDocument::NodeChanging** 事件中调用，**get_NewValue** 在更改成功时返回节点的值。如果在 **XmlDocument::NodeChanged** 事件中调用，**get_NewValue** 返回节点的当前值。

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlNodeChangedEventArgs](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)