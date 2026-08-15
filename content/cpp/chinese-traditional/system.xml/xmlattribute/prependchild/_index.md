---
title: PrependChild()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的節點添加到此節點的子節點列表的開頭。
type: docs
weight: 261
url: /zh-hant/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) 方法


將指定的節點添加到此節點的子節點列表的開頭。

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 要添加的[XmlNode](../../xmlnode/)。如果它是[XmlDocumentFragment](../../xmldocumentfragment/)，則文檔片段的全部內容將移動到此節點的子列表中。 |

### 返回值

已添加的[XmlNode](../../xmlnode/)。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlAttribute](../)
* 命名空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)