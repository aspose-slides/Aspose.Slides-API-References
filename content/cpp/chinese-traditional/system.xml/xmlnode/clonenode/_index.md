---
title: CloneNode()
second_title: Aspose.Slides for C++ API 參考
description: 在派生類別中覆寫時，建立節點的副本。
type: docs
weight: 456
url: /zh-hant/system.xml/xmlnode/clonenode/
---
## XmlNode::CloneNode(bool) 方法

在派生類別中覆寫時，建立節點的副本。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::CloneNode(bool deep)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| deep | **bool** | 如果為 **true**，則遞迴複製指定節點下的子樹；如果為 **false**，則僅複製該節點本身。 |

### 回傳值

已複製的節點。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)