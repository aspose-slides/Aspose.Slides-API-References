---
title: CloneNode()
second_title: Aspose.Slides C++ API 參考文件
description: 建立此節點的複本。
type: docs
weight: 79
url: /zh-hant/system.xml/xmlsignificantwhitespace/clonenode/
---
## XmlSignificantWhitespace::CloneNode(bool) 方法

建立此節點的複本。

```cpp
SharedPtr<XmlNode> System::Xml::XmlSignificantWhitespace::CloneNode(bool deep) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| deep | **bool** | **true** 以遞迴方式複製指定節點下的子樹；**false** 僅複製節點本身。對於顯著空白節點，無論參數設定為何，複製的節點皆會包含資料值。 |

### 傳回值

複製的節點。

## 相關參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlSignificantWhitespace](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)