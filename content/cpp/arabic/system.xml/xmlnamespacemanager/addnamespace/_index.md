---
title: AddNamespace()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف مساحة الاسم المحددة إلى المجموعة.
type: docs
weight: 66
url: /ar/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) طريقة

يضيف مساحة الاسم المحددة إلى المجموعة.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | البادئة لربطها بمساحة الاسم التي يتم إضافتها. استخدم [String::Empty](../../../system/string/empty/) لإضافة مساحة اسم افتراضية. إذا كان سيتم استخدام [XmlNamespaceManager](../) لحل مساحات الأسماء في تعبير لغة مسار XML ([XPath](../../../system.xml.xpath/))، يجب تحديد بادئة. إذا لم يتضمن تعبير [XPath](../../../system.xml.xpath/) بادئة، يُفترض أن معرف المورد الموحد (URI) لمساحة الاسم هو مساحة الاسم الفارغة. لمزيد من المعلومات حول تعبيرات [XPath](../../../system.xml.xpath/) و[XmlNamespaceManager](../)، راجع طرق XmlNode::SelectNodes(String) وXPathExpression::SetContext(SharedPtr<XmlNamespaceManager>). |
| uri | [String](../../../system/string/) | مساحة الاسم التي سيتم إضافتها. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlNamespaceManager](../)
* مساحة الأسماء [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)