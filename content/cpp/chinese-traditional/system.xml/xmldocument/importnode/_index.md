---
title: ImportNode()
second_title: Aspose.Slides for C++ API 參考
description: 將節點從另一個文件匯入至當前文件。
type: docs
weight: 469
url: /zh-hant/system.xml/xmldocument/importnode/
---
## XmlDocument::ImportNode(SharedPtr\<XmlNode\>, bool) 方法


將節點從另一個文件匯入到目前的文件。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ImportNode(SharedPtr<XmlNode> node, bool deep)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 要匯入的節點。 |
| deep | **bool** | **true** 以執行深層 clone；否則為 **false**。 |

### 返回值

已匯入的 [XmlNode](../../xmlnode/)。

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlDocument](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)