---
title: SetContext()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عند تجاوزها في فئة مشتقة، تُحدد كائن XmlNamespaceManager لاستخدامه في حل أسماء النطاقات.
type: docs
weight: 53
url: /ar/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) طريقة

عند تجاوزها في فئة مُشتقة، تُحدد كائن [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) لاستخدامه في حل الأسماء.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | كائن [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) لاستخدامه في حل الأسماء. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) طريقة

عند تجاوزها في فئة مُشتقة، تُحدد كائن [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) لاستخدامه في حل الأسماء.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | كائن يُنفّذ واجهة [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) لاستخدامه في حل الأسماء. |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* فئة [XPathExpression](../)
* فئة [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* نطاق [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)