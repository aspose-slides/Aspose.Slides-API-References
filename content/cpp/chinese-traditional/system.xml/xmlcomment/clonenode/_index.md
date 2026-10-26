---
title: CloneNode()
second_title: Aspose.Slides for C++ API 參考文件
description: 為此節點建立副本。
type: docs
weight: 40
url: /zh-hant/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) 方法


建立此節點的副本。

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| deep | **bool** | **true** 以遞迴方式複製指定節點下的子樹；**false** 僅複製節點本身。因為註解節點沒有子項，無論參數設定如何，複製的節點都會包含文字內容。 |

### 回傳值

已複製的節點。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlComment](../)
* 命名空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)