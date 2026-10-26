---
title: Contains()
second_title: Aspose.Slides for C++ API 参考
description: 指示指定的 XmlSchemaObject 是否在 XmlSchemaObjectCollection 中。
type: docs
weight: 92
url: /zh/system.xml.schema/xmlschemaobjectcollection/contains/
---
## XmlSchemaObjectCollection::Contains(const SharedPtr\<XmlSchemaObject\>\&) 方法

指示指定的 [XmlSchemaObject](../../xmlschemaobject/) 是否在 [XmlSchemaObjectCollection](../) 中。

```cpp
bool System::Xml::Schema::XmlSchemaObjectCollection::Contains(const SharedPtr<XmlSchemaObject> &item)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | 该 [XmlSchemaObject](../../xmlschemaobject/)。 |

### 返回值

**true** 如果指定的限定名称在集合中；否则返回 **false**。如果提供了 **nullptr**，则返回 **false**，因为没有具有空名称的限定名称。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaObject](../../xmlschemaobject/)
* Class [XmlSchemaObjectCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)