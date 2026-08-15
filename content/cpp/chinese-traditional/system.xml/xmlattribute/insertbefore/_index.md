---
title: InsertBefore()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的節點立即插入在指定的參考節點之前。
type: docs
weight: 209
url: /zh-hant/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) 方法


將指定的節點立即插入在指定的參考節點之前。

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 要插入的 [XmlNode](../../xmlnode/)。 |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/)是參考節點。**newChild**會放在此節點之前。 |

### 回傳值

插入的[XmlNode](../../xmlnode/)。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlAttribute](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)