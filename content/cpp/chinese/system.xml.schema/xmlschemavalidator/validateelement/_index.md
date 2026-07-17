---
title: ValidateElement()
second_title: Aspose.Slides C++ API 参考
description: 在当前上下文中验证元素。
type: docs
weight: 131
url: /zh/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) 方法

在当前上下文中验证元素。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 要验证的元素的本地名称。 |
| namespaceUri | const [String](../../../system/string/)\& | 要验证的元素的命名空间 URI。 |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 一个 [XmlSchemaInfo](../../xmlschemainfo/) 对象，其属性在成功验证元素名称后被设置。此参数可以为 **nullptr**。 |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) 方法

在当前上下文中验证元素，并使用指定的 **xsi:Type**、**xsi:Nil**、**xsi:SchemaLocation** 和 **xsi:NoNamespaceSchemaLocation** 属性值。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 要验证的元素的本地名称。 |
| namespaceUri | const [String](../../../system/string/)\& | 要验证的元素的命名空间 URI。 |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 一个 [XmlSchemaInfo](../../xmlschemainfo/) 对象，其属性在成功验证元素名称后被设置。此参数可以为 **nullptr**。 |
| xsiType | const [String](../../../system/string/)\& | **xsi:Type** 属性值。此参数可以为 **nullptr**。 |
| xsiNil | const [String](../../../system/string/)\& | **xsi:Nil** 属性值。此参数可以为 **nullptr**。 |
| xsiSchemaLocation | const [String](../../../system/string/)\& | **xsi:SchemaLocation** 属性值。此参数可以为 **nullptr**。 |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | **xsi:NoNamespaceSchemaLocation** 属性值。此参数可以为 **nullptr**。 |

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [XmlSchemaInfo](../../xmlschemainfo/)
* 类 [XmlSchemaValidator](../)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)