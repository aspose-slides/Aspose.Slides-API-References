---
title: RemoveAttributeAt()
second_title: Aspose.Slides for C++ API 參考
description: 從元素中移除具有指定索引的屬性節點。（如果被移除的屬性具有預設值，則會立即被替換）。
type: docs
weight: 339
url: /zh-hant/system.xml/xmlelement/removeattributeat/
---
## XmlElement::RemoveAttributeAt(int32_t) 方法

從元素中移除具有指定索引的屬性節點。（如果被移除的屬性具有預設值，則會立即被替換）。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlElement::RemoveAttributeAt(int32_t i)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | 要移除的節點索引。第一個節點的索引為 0。 |

### 回傳值

已移除的屬性節點，若在給定索引處沒有節點則返回 **nullptr**。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlElement](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)