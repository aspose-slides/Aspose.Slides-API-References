---
title: idx_get()
second_title: Aspose.Slides C++ API 參考
description: 返回在給定索引處的節點。
type: docs
weight: 40
url: /zh-hant/system.xml/xmlnodelist/idx_get/
---
## XmlNodeList::idx_get(int32_t) 方法


返回在給定索引處的節點。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::idx_get(int32_t i)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | 零基索引，指向節點清單中的位置。 |

### 回傳值

集合中具有指定索引的 [XmlNode](../../xmlnode/)。如果索引大於或等於列表中節點的數量，則返回 **nullptr**。

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlNodeList](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)