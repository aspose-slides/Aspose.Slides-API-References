---
title: ReadSubtree()
second_title: مرجع API Aspose.Slides للغة C++
description: يعيد كائنًا جديدًا من نوع XmlReader يمكن استخدامه لقراءة العقدة الحالية وجميع العناصر التابعة لها.
type: docs
weight: 963
url: /ar/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() طريقة

تُرجع كائنًا جديدًا من نوع [XmlReader](../) يمكن استخدامه لقراءة العقدة الحالية وجميع العناصر التابعة لها.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```

### قيمة الإرجاع

كائن قارئ XML جديد يتم ضبطه على [ReadState::Initial](../../readstate/). استدعاء طريقة [XmlReader::Read](../read/) يضع القارئ الجديد على العقدة التي كانت الحالية قبل استدعاء طريقة [XmlReader::ReadSubtree](./).

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlReader](../)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)