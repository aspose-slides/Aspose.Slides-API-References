---
title: InsertAfter()
second_title: Aspose.Slides for C++ API 參考
description: 在指定的參考節點之後立即插入指定的節點。
type: docs
weight: 391
url: /zh-hant/system.xml/xmlnode/insertafter/
---
## XmlNode::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) 方法

在指定的參考節點之後立即插入指定的節點。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | 要插入的節點。 |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | 參考節點。**newChild** 會放在 **refChild** 之後。 |

### 返回值

被插入的節點。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)