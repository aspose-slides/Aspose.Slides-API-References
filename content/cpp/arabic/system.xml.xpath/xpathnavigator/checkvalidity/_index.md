---
title: CheckValidity()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يتحقق من أن بيانات XML في XPathNavigator تتوافق مع مخطط لغة تعريف XML Schema (XSD) المقدم.
type: docs
weight: 755
url: /ar/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) طريقة

يتحقق من أن بيانات XML في [XPathNavigator](../) تتوافق مع مخطط لغة تعريف XML [Schema](../../../system.xml.schema/) (XSD) المقدم.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | مجموعة XmlSchemaSet التي تحتوي على المخططات المستخدمة للتحقق من صحة بيانات XML الموجودة في [XPathNavigator](../). |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | معالج ValidationEventHandler الذي يتلقى معلومات حول تحذيرات وأخطاء التحقق من صحة المخطط. |

### قيمة الإرجاع

**true** إذا لم تحدث أي أخطاء في التحقق من صحة المخطط؛ وإلا، **false**.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* فئة [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* فئة [XPathNavigator](../)
* نطاق [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)