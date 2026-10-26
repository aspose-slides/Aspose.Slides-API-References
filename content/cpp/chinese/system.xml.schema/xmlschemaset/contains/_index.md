---
title: Contains()
second_title: Aspose.Slides for C++ API 参考
description: 指示具有指定目标命名空间 URI 的 XML Schema 定义语言 (XSD) 架构是否在 XmlSchemaSet 中。
type: docs
weight: 196
url: /zh/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) 方法


指示是否具有指定目标命名空间 URI 的 XML [Schema](../../) 定义语言 (XSD) 架构位于 [XmlSchemaSet](../) 中。

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | 模式的 **targetNamespace** 属性。 |

### 返回值

**true** 如果具有指定目标命名空间 URI 的架构位于 [XmlSchemaSet](../) 中；否则，**false**。

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) 方法


指示指定的 XML [Schema](../../) 定义语言 (XSD) [XmlSchema](../../xmlschema/) 对象是否位于 [XmlSchemaSet](../) 中。

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | 该 [XmlSchema](../../xmlschema/) 对象。 |

### 返回值

**true** 如果 [XmlSchema](../../xmlschema/) 对象位于 [XmlSchemaSet](../) 中；否则，**false**。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [XmlSchemaSet](../)
* 类 [XmlSchema](../../xmlschema/)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)