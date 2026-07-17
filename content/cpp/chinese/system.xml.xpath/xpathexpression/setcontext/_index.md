---
title: SetContext()
second_title: Aspose.Slides for C++ API 参考
description: 在派生类中重写时，指定用于命名空间解析的 XmlNamespaceManager 对象。
type: docs
weight: 53
url: /zh/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) 方法


When overridden in a derived class, specifies the [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) object to use for namespace resolution.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | An [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) object to use for namespace resolution. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) 方法


When overridden in a derived class, specifies the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object to use for namespace resolution.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | An object that implements the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) interface to use for namespace resolution. |

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* 类 [XPathExpression](../)
* 类 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)