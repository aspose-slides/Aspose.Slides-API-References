---
title: Contains()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个值，指示指定的 XmlSchema 的 targetNamespace 是否在集合中。
type: docs
weight: 66
url: /zh/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) method


返回一个值，指示指定的 [XmlSchema](../../xmlschema/) 的 **targetNamespace** 是否在集合中。

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) 对象。 |

### 返回值

**true** if there is a schema in the collection with the same **targetNamespace**; otherwise, **false**.

## XmlSchemaCollection::Contains(const String\&) method


返回一个值，指示集合中是否存在具有指定命名空间的模式。

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | 与模式关联的命名空间 URI。对于 XML Schemas，通常是目标命名空间。 |

### 返回值

**true** if a schema with the specified namespace is in the collection; otherwise, **false**.

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaCollection](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)