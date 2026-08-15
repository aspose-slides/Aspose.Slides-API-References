---
title: CloneNode()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立此節點的副本。實體節點無法被克隆。在 XmlEntity 物件上呼叫此方法會拋出例外。
type: docs
weight: 170
url: /zh-hant/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) 方法

建立此節點的副本。實體節點無法被克隆。在 [XmlEntity](../) 物件上呼叫此方法會拋出例外。

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| deep | **bool** | **true**：遞迴複製指定節點下的子樹；**false**：僅複製節點本身。 |

### 回傳值

從呼叫此方法的 [XmlNode](../../xmlnode/) 複製而來的副本。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlEntity](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)