---
title: PrependChild()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يضيف العقدة المحددة إلى بداية قائمة العقد الفرعية لهذا العنصر.
type: docs
weight: 261
url: /ar/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) طريقة


يضيف العقدة المحددة إلى بداية قائمة العقد الفرعية لهذا العنصر.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```


### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | الـ [XmlNode](../../xmlnode/) للإضافة. إذا كان [XmlDocumentFragment](../../xmldocumentfragment/)، يتم نقل كامل محتويات قطعة المستند إلى قائمة الأطفال لهذا العنصر. |

### قيمة الإرجاع

الـ [XmlNode](../../xmlnode/) المضافة.

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [XmlAttribute](../)
* مساحة أسماء [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)