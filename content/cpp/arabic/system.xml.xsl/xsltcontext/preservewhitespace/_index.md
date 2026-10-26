---
title: PreserveWhitespace()
second_title: مرجع API Aspose.Slides للغة C++
description: عند تجاوزها في فئة مشتقة، تُقَيِّم ما إذا كان ينبغي الحفاظ على عقد المسافات البيضاء أو إزالتها في السياق المحدد.
type: docs
weight: 40
url: /ar/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) طريقة

عند تجاوزها في فئة مشتقة، تُقَيِّم ما إذا كان ينبغي الحفاظ على عقد المسافات البيضاء أو إزالتها للسياق المحدد.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | عقدة المسافة البيضاء التي يجب الحفاظ عليها أو إزالتها في السياق الحالي. |

### قيمة الإرجاع

**true** إذا كان يجب الحفاظ على المسافة البيضاء؛ **false** إذا كان يجب إزالتها.

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* فئة [XsltContext](../)
* نطاق [System::Xml::Xsl](../../)
* مكتبة [Aspose.Slides](../../../)