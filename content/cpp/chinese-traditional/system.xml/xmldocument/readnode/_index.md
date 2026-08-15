---
title: ReadNode()
second_title: Aspose.Slides for C++ API 參考
description: 根據 XmlReader 中的資訊建立一個 XmlNode 物件。讀取器必須定位在節點或屬性上。
type: docs
weight: 495
url: /zh-hant/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) 方法


根據 [XmlReader](../../xmlreader/) 中的資訊建立一個 [XmlNode](../../xmlnode/) 物件。讀取器必須定位在節點或屬性上。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | XML 來源。 |

### 返回值

新的 [XmlNode](../../xmlnode/)，如果沒有更多節點則返回 **nullptr**。

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlReader](../../xmlreader/)
* 類別 [XmlDocument](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)