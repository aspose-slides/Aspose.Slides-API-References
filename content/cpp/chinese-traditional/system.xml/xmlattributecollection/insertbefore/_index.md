---
title: InsertBefore()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的屬性直接插入於指定的參考屬性之前。
type: docs
weight: 53
url: /zh-hant/system.xml/xmlattributecollection/insertbefore/
---
## XmlAttributeCollection::InsertBefore(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) 方法

將指定的屬性直接插入於指定的參考屬性之前。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertBefore(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | 要插入的屬性。 |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | 參考屬性。**newNode** 會放在 **refNode** 之前。 |

### 返回值

要插入至集合的 [XmlAttribute](../../xmlattribute/)。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlAttribute](../../xmlattribute/)
* 類別 [XmlAttributeCollection](../)
* 命名空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)