---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 将由给定 URL 定位的模式添加到模式集合中。
type: docs
weight: 40
url: /zh/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) method

将由给定 URL 定位的模式添加到模式集合中。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | 与模式关联的命名空间 URI。对于 XML 模式，通常是 **targetNamespace**。 |
| uri | const [String](../../../system/string/)\& | 指定要加载的模式的 URL。 |

### 返回值

添加到模式集合中的 [XmlSchema](../../xmlschema/)；如果添加的模式是 XDR 模式或模式中存在编译错误，则为 **nullptr**。

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) method

将 [XmlReader](../../../system.xml/xmlreader/) 中包含的模式添加到模式集合中。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | 与模式关联的命名空间 URI。对于 XML 模式，通常是 **targetNamespace**。 |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含要添加的模式的 [XmlReader](../../../system.xml/xmlreader/)。 |

### 返回值

添加到模式集合中的 [XmlSchema](../../xmlschema/)；如果添加的模式是 XDR 模式或模式中存在编译错误，则为 **nullptr**。

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

将 [XmlReader](../../../system.xml/xmlreader/) 中包含的模式添加到模式集合中。指定的 [XmlResolver](../../../system.xml/xmlresolver/) 用于解析任何外部资源。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | 与模式关联的命名空间 URI。对于 XML 模式，通常是 **targetNamespace**。 |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含要添加的模式的 [XmlReader](../../../system.xml/xmlreader/)。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于解析 **include**、**import** 元素或 **x-schema** 属性（XDR 模式）中引用的命名空间的 [XmlResolver](../../../system.xml/xmlresolver/)。如果为 **nullptr**，则不解析外部引用。 |

### 返回值

添加到模式集合中的 [XmlSchema](../../xmlschema/)；如果添加的模式是 XDR 模式或模式中存在编译错误，则为 **nullptr**。

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) method

将 [XmlSchema](../../xmlschema/) 添加到集合中。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | 要添加到集合中的 [XmlSchema](../../xmlschema/)。 |

### 返回值

[XmlSchema](../../xmlschema/) 对象。

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

将 [XmlSchema](../../xmlschema/) 添加到集合中。指定的 [XmlResolver](../../../system.xml/xmlresolver/) 用于解析任何外部引用。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | 要添加到集合中的 [XmlSchema](../../xmlschema/)。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用于解析 **include** 和 **import** 元素中引用的命名空间的 [XmlResolver](../../../system.xml/xmlresolver/)。如果为 **nullptr**，则不解析外部引用。 |

### 返回值

添加到模式集合中的 [XmlSchema](../../xmlschema/)。

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) method

将给定集合中定义的所有命名空间（包括其关联的模式）添加到此集合中。

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | 您想要添加到此集合的 [XmlSchemaCollection](../)。 |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)