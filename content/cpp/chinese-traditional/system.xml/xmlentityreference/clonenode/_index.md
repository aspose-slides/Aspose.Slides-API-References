---
title: CloneNode()
second_title: Aspose.Slides for C++ API 參考
description: 建立此節點的副本。
type: docs
weight: 92
url: /zh-hant/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) 方法


建立此節點的副本。

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| deep | **bool** | **true** 以遞迴方式複製指定節點下的子樹； **false** 僅複製節點本身。對於 [XmlEntityReference](../) 節點，此方法總是返回一個沒有子項的實體參照節點。當節點插入父節點時，會設定取代文字。 |

### 返回值

已複製的節點。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlEntityReference](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)