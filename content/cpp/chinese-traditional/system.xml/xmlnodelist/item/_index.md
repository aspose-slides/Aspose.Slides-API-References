---
title: Item()
second_title: Aspose.Slides for C++ API 參考
description: 取得給定索引處的節點。
type: docs
weight: 14
url: /zh-hant/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item(int32_t) 方法

取得給定索引處的節點。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 節點列表中的零基索引。 |

### 返回值

指定集合中具有指定索引的 [XmlNode](../../xmlnode/)。如果 **index** 大於或等於列表中節點的數量，則返回 **nullptr**。

## 另見

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlNodeList](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)