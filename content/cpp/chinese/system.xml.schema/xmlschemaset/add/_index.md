---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 将位于指定 URL 的 XML 架构定义语言 (XSD) 架构添加到 XmlSchemaSet。
type: docs
weight: 157
url: /zh/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) 方法

将位于指定 URL 的 XML [Schema](../../) 定义语言 (XSD) 架构添加到 [XmlSchemaSet](../)。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | 架构的 **targetNamespace** 值，或 **nullptr** 以使用架构中指定的 **targetNamespace**。 |
| schemaUri | const [String](../../../system/string/)\& | 指定要加载的架构的 URL。 |

### 返回值

如果架构有效，则返回 [XmlSchema](../../xmlschema/) 对象。如果架构无效且已指定 ValidationEventHandler，则返回 **nullptr** 并触发相应的验证事件。否则，将抛出 XmlSchemaException。

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) 方法

将包含在 [XmlReader](../../../system.xml/xmlreader/) 中的 XML [Schema](../../) 定义语言 (XSD) 架构添加到 [XmlSchemaSet](../)。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | 架构的 **targetNamespace** 值，或 **nullptr** 以使用架构中指定的 **targetNamespace**。 |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) 对象。 |

### 返回值

如果架构有效，则返回 [XmlSchema](../../xmlschema/) 对象。如果架构无效且已指定 ValidationEventHandler，则返回 **nullptr** 并触发相应的验证事件。否则，将抛出 XmlSchemaException。

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) 方法

将给定 [XmlSchemaSet](../) 中的所有 XML [Schema](../../) 定义语言 (XSD) 架构添加到 [XmlSchemaSet](../)。

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | [XmlSchemaSet](../) 对象。 |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) 方法

将给定的 [XmlSchema](../../xmlschema/) 添加到 [XmlSchemaSet](../)。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | 要添加到 [XmlSchemaSet](../) 的 [XmlSchema](../../xmlschema/) 对象。 |

### 返回值

如果架构有效，则返回 [XmlSchema](../../xmlschema/) 对象。如果架构无效且已指定 ValidationEventHandler，则返回 **nullptr** 并触发相应的验证事件。否则，将抛出 XmlSchemaException。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)