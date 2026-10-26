---
title: InsertBefore()
second_title: Aspose.Slides for C++ API 參考手冊
description: 在指定的參考節點之前立即插入指定的節點。
type: docs
weight: 378
url: /zh-hant/system.xml/xmlnode/insertbefore/
---
## XmlNode::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) 方法


在指定的參考節點之前立即插入指定的節點。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | 要插入的節點。 |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | 參考節點。**newChild** 會放在此節點之前。 |

### 回傳值

被插入的節點。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)