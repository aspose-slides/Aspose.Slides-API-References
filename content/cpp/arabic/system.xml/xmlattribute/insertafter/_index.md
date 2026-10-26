---
title: InsertAfter()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يدرج العقدة المحددة مباشرةً بعد عقدة الإشارة المحددة.
type: docs
weight: 222
url: /ar/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) طريقة


يدرج العقدة المحددة مباشرةً بعد عقدة الإشارة المحددة.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | الـ [XmlNode](../../xmlnode/) للإدراج. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | الـ [XmlNode](../../xmlnode/) التي هي عقدة الإشارة. الـ **newChild** يتم وضعه بعد الـ **refChild**. |

### قيمة الإرجاع

الـ [XmlNode](../../xmlnode/) تم إدراجه.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNode](../../xmlnode/)
* فئة [XmlAttribute](../)
* نطاق [System::Xml](../../)
* Library [Aspose.Slides](../../../)