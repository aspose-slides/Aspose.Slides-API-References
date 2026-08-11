---
title: XmlNodeChangedEventArgs()
second_title: مرجع API Aspose.Slides للـ C++
description: تهيئة نسخة جديدة من الفئة XmlNodeChangedEventArgs.
type: docs
weight: 79
url: /ar/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) المنشئ

تهيئة نسخة جديدة من [XmlNodeChangedEventArgs](../) الصنف.

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | الـ [XmlNode](../../xmlnode/) الذي تولد الحدث. |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | الوالد القديم [XmlNode](../../xmlnode/) للـ [XmlNode](../../xmlnode/) الذي تولد الحدث. |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | الوالد الجديد [XmlNode](../../xmlnode/) للـ [XmlNode](../../xmlnode/) الذي تولد الحدث. |
| oldValue | const [String](../../../system/string/)\& | القيمة القديمة للـ [XmlNode](../../xmlnode/) الذي تولد الحدث. |
| newValue | const [String](../../../system/string/)\& | القيمة الجديدة للـ [XmlNode](../../xmlnode/) الذي تولد الحدث. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | الإجراء XmlNodeChangedAction. |

## انظر أيضًا

* تعداد [XmlNodeChangedAction](../../xmlnodechangedaction/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [XmlNode](../../xmlnode/)
* الفئة [String](../../../system/string/)
* الفئة [XmlNodeChangedEventArgs](../)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)