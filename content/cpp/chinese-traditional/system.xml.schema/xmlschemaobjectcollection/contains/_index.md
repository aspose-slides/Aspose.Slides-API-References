---
title: Contains()
second_title: Aspose.Slides for C++ API 參考
description: 指示指定的 XmlSchemaObject 是否位於 XmlSchemaObjectCollection 中。
type: docs
weight: 92
url: /zh-hant/system.xml.schema/xmlschemaobjectcollection/contains/
---
## XmlSchemaObjectCollection::Contains(const SharedPtr\<XmlSchemaObject\>\&) method

指示指定的 [XmlSchemaObject](../../xmlschemaobject/) 是否在 [XmlSchemaObjectCollection](../) 中。

```cpp
bool System::Xml::Schema::XmlSchemaObjectCollection::Contains(const SharedPtr<XmlSchemaObject> &item)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| item | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | 此 [XmlSchemaObject](../../xmlschemaobject/)。 |

### 傳回值

**true** 如果指定的合格名稱在集合中；否則返回 **false**。如果提供 **nullptr**，則返回 **false**，因為沒有名稱為 null 的合格名稱。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaObject](../../xmlschemaobject/)
* Class [XmlSchemaObjectCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)