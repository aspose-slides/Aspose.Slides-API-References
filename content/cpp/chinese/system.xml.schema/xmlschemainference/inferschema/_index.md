---
title: InferSchema()
second_title: Aspose.Slides C++ API 参考
description: 从指定的 XmlReader 对象中包含的 XML 文档推断 XML 模式定义语言 (XSD) 架构。
type: docs
weight: 66
url: /zh/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) method

从指定的 [XmlReader](../../../system.xml/xmlreader/) 对象中包含的 XML 文档推断 XML [Schema](../../) 定义语言 (XSD) 架构。

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含用于推断架构的 XML 文档的 [XmlReader](../../../system.xml/xmlreader/) 对象。 |

### 返回值

包含推断后架构的 [XmlSchemaSet](../../xmlschemaset/) 对象。

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) method

从指定的 [XmlReader](../../../system.xml/xmlreader/) 对象中包含的 XML 文档推断 XML [Schema](../../) 定义语言 (XSD) 架构，并使用在 [XmlSchemaSet](../../xmlschemaset/) 对象中具有相同目标命名空间的现有架构对推断的架构进行细化。

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含用于推断架构的 XML 文档的 [XmlReader](../../../system.xml/xmlreader/) 对象。 |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | 包含用于细化推断架构的现有架构的 [XmlSchemaSet](../../xmlschemaset/) 对象。 |

### 返回值

包含推断后架构的 [XmlSchemaSet](../../xmlschemaset/) 对象。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)