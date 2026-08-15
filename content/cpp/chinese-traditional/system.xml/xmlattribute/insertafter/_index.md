---
title: InsertAfter()
second_title: Aspose.Slides for C++ API 參考
description: 將指定節點緊接在指定的參考節點之後插入。
type: docs
weight: 222
url: /zh-hant/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) 方法

將指定節點緊接在指定的參考節點之後插入。

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 要插入的 [XmlNode](../../xmlnode/)。 |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 作為參考節點的 [XmlNode](../../xmlnode/)。**newChild** 置於 **refChild** 之後。 |

### 返回值

已插入的 [XmlNode](../../xmlnode/)。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlAttribute](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)