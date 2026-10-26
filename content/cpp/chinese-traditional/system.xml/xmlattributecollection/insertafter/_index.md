---
title: InsertAfter()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的屬性緊接在指定的參考屬性之後插入。
type: docs
weight: 66
url: /zh-hant/system.xml/xmlattributecollection/insertafter/
---
## XmlAttributeCollection::InsertAfter(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) 方法

將指定的屬性緊接在指定的參考屬性之後插入。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertAfter(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | 要插入的屬性。 |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | 參考屬性。**newNode** 於 **refNode** 之後放置。 |

### 傳回值

要插入到集合中的 [XmlAttribute](../../xmlattribute/)。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlAttribute](../../xmlattribute/)
* 類別 [XmlAttributeCollection](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)