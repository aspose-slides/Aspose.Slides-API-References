---
title: Item()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢索位於 XmlNamedNodeMap 中指定索引的節點。
type: docs
weight: 53
url: /zh-hant/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) 方法


取得 [XmlNamedNodeMap](../) 中於指定索引處的節點。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```


### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要從 [XmlNamedNodeMap](../) 取得的節點之索引位置。索引採零基礎；因此，第一個節點的索引為 0，最後一個節點的索引為 [XmlNamedNodeMap::get_Count](../get_count/) - 1。 |

### 傳回值

[XmlNode](../../xmlnode/) 在指定的索引處。如果 **index** 小於 0 或大於等於 [XmlNamedNodeMap::get_Count](../get_count/) 值，則回傳 **nullptr**。

## 另見

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlNamedNodeMap](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)