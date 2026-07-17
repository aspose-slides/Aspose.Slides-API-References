---
title: Schemas()
second_title: Aspose.Slides for C++ API 参考
description: 返回 XmlSchemaSet 中所有 XML 架构定义语言 (XSD) 模式的集合。
type: docs
weight: 248
url: /zh/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() method


返回 [XmlSchemaSet](../) 中所有 XML [Schema](../../) 定义语言（XSD）模式的集合。

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```


### 返回值

返回一个 IList 对象，包含已添加到 [XmlSchemaSet](../) 的所有模式。如果没有模式被添加到 [XmlSchemaSet](../)，则返回空集合。

## XmlSchemaSet::Schemas(String) method


返回属于给定命名空间的 [XmlSchemaSet](../) 中所有 XML [Schema](../../) 定义语言（XSD）模式的集合。

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | 模式的 **targetNamespace** 属性。 |

### 返回值

返回一个 IList 对象，包含已添加到 [XmlSchemaSet](../) 且属于给定命名空间的所有模式。如果没有模式被添加到 [XmlSchemaSet](../)，则返回空集合。

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IList](../../../system.collections.generic/ilist/)
* 类 [XmlSchema](../../xmlschema/)
* 类 [XmlSchemaSet](../)
* 类 [List](../../../system.collections.generic/list/)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)