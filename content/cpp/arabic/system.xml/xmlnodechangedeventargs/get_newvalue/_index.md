---
title: get_NewValue()
second_title: Aspose.Slides لـ C++ مرجع API
description: يعيد القيمة الجديدة للعقدة.
type: docs
weight: 66
url: /ar/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() طريقة

Returns the new value of the node.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```

### قيمة الإرجاع

ترجع هذه الطريقة **nullptr** إذا لم تكن العقدة سمة ولا عقدة نصية، أو إذا كانت العقدة تُزال. إذا تم الاستدعاء في حدث **XmlDocument::NodeChanging**، فإن **get_NewValue** تُرجع قيمة العقدة إذا نجح التغيير. إذا تم الاستدعاء في حدث **XmlDocument::NodeChanged**، فإن **get_NewValue** تُرجع القيمة الحالية للعقدة.

## أنظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlNodeChangedEventArgs](../)
* مساحة الأسماء [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)