---
title: ParseValue()
second_title: Aspose.Slides C++ API 参考
description: 当在派生类中被覆写时，验证指定的字符串是否符合内置或用户定义的简单类型。
type: docs
weight: 53
url: /zh/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) 方法

当在派生类中被覆写时，验证指定的 **string** 是否符合内置或用户定义的简单类型。

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| s | [String](../../../system/string/) | 用于验证 **string** 是否符合简单类型。 |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | 在解析 **string** 时，如果此 [XmlSchemaDatatype](../) 对象表示 **xs:NCName** 类型，则用于原子化的 [XmlNameTable](../../../system.xml/xmlnametable/)。 |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 在解析 **string** 时，如果此 [XmlSchemaDatatype](../) 对象表示 **xs:QName** 类型，则使用的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 对象。 |

### 返回值

一个 [Object](../../../system/object/)，可以安全地转换为 [XmlSchemaDatatype::get_ValueType](../get_valuetype/) 调用返回的类型。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [String](../../../system/string/)
* 类 [XmlNameTable](../../../system.xml/xmlnametable/)
* 类 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 类 [XmlSchemaDatatype](../)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)