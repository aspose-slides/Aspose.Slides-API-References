---
title: ValueAs()
second_title: Aspose.Slides for C++ API 参考
description: 返回项目的值，类型为指定的类型。
type: docs
weight: 131
url: /zh/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) 方法

返回项目的值，类型为指定的类型。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 返回项目值的类型。 |

### 返回值

项目的值，类型为请求的类型。

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) 方法

在派生类中重写时，返回项目的值，类型是使用 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 对象指定以解析命名空间前缀的类型。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 返回项目值的类型。 |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 对象用于解析命名空间前缀。 |

### 返回值

项目的值，类型为请求的类型。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [XPathItem](../)
* 类 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)