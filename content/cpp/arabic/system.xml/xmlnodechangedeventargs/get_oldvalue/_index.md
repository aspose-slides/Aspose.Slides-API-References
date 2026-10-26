---
title: get_OldValue()
second_title: Aspose.Slides لـ C++ مرجع API
description: يعيد القيمة الأصلية للعنقودة.
type: docs
weight: 53
url: /ar/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() طريقة

يرجع القيمة الأصلية للعنقودة.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```

### قيمة الإرجاع

القيمة الأصلية للعنقودة. تُعيد هذه الطريقة **nullptr** إذا لم تكن العنقودة سمة ولا عقدة نصية، أو إذا كانت العنقودة قيد الإدراج. إذا تم استدعاؤها في حدث **XmlDocument::NodeChanging**، فإن **get_OldValue** تُعيد القيمة الحالية للعنقودة التي ستستبدل إذا نجحت العملية. إذا تم استدعاؤها في حدث **XmlDocument::NodeChanged**، فإن **get_OldValue** تُعيد قيمة العنقودة قبل التغيير.

## انظر أيضاً

* الفئة [String](../../../system/string/)
* الفئة [XmlNodeChangedEventArgs](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)