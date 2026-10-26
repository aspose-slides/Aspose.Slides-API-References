---
title: SetNamedItem()
second_title: Aspose.Slides for C++ API 參考文件
description: "使用其 XmlNode::get_Name 值新增 XmlNode。"
type: docs
weight: 27
url: /zh-hant/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) 方法

使用其 [XmlNode::get_Name](../../xmlnode/get_name/) 值新增 [XmlNode](../../xmlnode/)。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 用於存放於 [XmlNamedNodeMap](../) 的 [XmlNode](../../xmlnode/)。如果映射中已存在具有相同名稱的節點，則會被新節點取代。 |

### 回傳值

如果 **node** 替換了具有相同名稱的現有節點，則返回舊的節點；否則，返回 **nullptr**。

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlNamedNodeMap](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)