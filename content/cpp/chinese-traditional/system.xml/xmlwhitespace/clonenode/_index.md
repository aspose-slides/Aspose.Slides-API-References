---
title: CloneNode()
second_title: Aspose.Slides for C++ API 參考
description: 建立此節點的副本。
type: docs
weight: 79
url: /zh-hant/system.xml/xmlwhitespace/clonenode/
---
## XmlWhitespace::CloneNode(bool) 方法

建立此節點的副本。

```cpp
SharedPtr<XmlNode> System::Xml::XmlWhitespace::CloneNode(bool deep) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** 以遞迴方式複製指定節點下的子樹；**false** 僅複製節點本身。對於空白節點，無論參數設定為何，複製的節點皆會包含資料值。 |

### 回傳值

已克隆的節點。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlWhitespace](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)