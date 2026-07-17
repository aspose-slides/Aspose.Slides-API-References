---
title: ValueAs()
second_title: Aspose.Slides for C++ API 参考
description: 返回使用指定的 IXmlNamespaceResolver 对象解析命名空间前缀后，以指定类型返回的已验证 XML 元素或属性的值。
type: docs
weight: 144
url: /zh/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) 方法

返回使用 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 对象解析命名空间前缀后，指定类型的已验证 XML 元素或属性的值。

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 用于返回已验证的 XML 元素或属性的值的类型。 |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 用于解析命名空间前缀的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 对象。 |

### 返回值

已验证的 XML 元素或属性的值，类型为请求的类型。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 类 [XmlAtomicValue](../)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)