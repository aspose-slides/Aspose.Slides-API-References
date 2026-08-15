---
title: CloneNode()
second_title: Aspose.Slides for C++ API 參考
description: 建立此節點的副本。
type: docs
weight: 118
url: /zh-hant/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) 方法

建立此節點的副本。

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** 以遞迴方式複製指定節點下的子樹；**false** 僅複製節點本身。對於文件類型節點，無論參數設定為何，複製的節點總是包含子樹。 |

### 返回值

複製的節點。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlDocumentType](../)
* 命名空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)