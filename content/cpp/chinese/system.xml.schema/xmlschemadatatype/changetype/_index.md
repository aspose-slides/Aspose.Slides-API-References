---
title: ChangeType()
second_title: Aspose.Slides C++ API 参考
description: 将指定的值转换为运行时指定的类型，该值的类型是由 XmlSchemaDatatype 表示的 XML 架构类型的有效表示之一。
type: docs
weight: 66
url: /zh/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) 方法

将指定的值转换为运行时指定的类型，该值的类型是由 [XmlSchemaDatatype](../) 表示的 XML 架构类型的有效表示之一。

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 要转换为指定类型的输入值。 |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | 要将输入值转换成的目标类型。 |

### 返回值

转换后的输入值。

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) 方法

如果 [XmlSchemaDatatype](../) 表示 **xs:QName** 类型或其派生类型，则使用 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 将由 [XmlSchemaDatatype](../) 表示的 XML 架构类型的有效表示之一的指定值转换为运行时指定的类型。

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 要转换为指定类型的输入值。 |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | 要将输入值转换成的目标类型。 |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 用于解析命名空间前缀的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)。仅当 [XmlSchemaDatatype](../) 表示 **xs:QName** 类型或其派生类型时才有用。 |

### 返回值

转换后的输入值。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [XmlSchemaDatatype](../)
* 类 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 命名空间 [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)