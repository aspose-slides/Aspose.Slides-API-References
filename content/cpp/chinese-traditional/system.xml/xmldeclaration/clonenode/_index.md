---
title: CloneNode()
second_title: Aspose.Slides for C++ API 參考
description: 建立此節點的複本。
type: docs
weight: 157
url: /zh-hant/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) 方法

建立此節點的複本。

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| deep | **bool** | **true** 用於遞迴複製指定節點下的子樹；**false** 用於僅複製節點本身。因為 [XmlDeclaration](../) 節點沒有子項，無論參數設定為何，複製的節點始終會包含資料值。 |

### 傳回值

複製的節點。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlDeclaration](../)
* 命名空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)