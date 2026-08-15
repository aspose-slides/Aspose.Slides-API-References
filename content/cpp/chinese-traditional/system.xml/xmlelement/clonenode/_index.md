---
title: CloneNode()
second_title: Aspose.Slides C++ API 參考
description: 建立此節點的副本。
type: docs
weight: 196
url: /zh-hant/system.xml/xmlelement/clonenode/
---
## XmlElement::CloneNode(bool) 方法


建立此節點的副本。

```cpp
SharedPtr<XmlNode> System::Xml::XmlElement::CloneNode(bool deep) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** 以遞迴方式複製指定節點下的子樹；**false** 僅複製節點本身（如果該節點是 [XmlElement](../)，則同時複製其屬性）。 |

### 回傳值

已克隆的節點。

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlElement](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)