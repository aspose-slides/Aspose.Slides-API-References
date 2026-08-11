---
title: get_LocalName()
second_title: Aspose.Slides لـ C++ مرجع API
description: عند تجاوزها في فئة مشتقة، تحصل على الاسم المحلي للعقدة الحالية.
type: docs
weight: 40
url: /ar/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() طريقة

عند تجاوزها في فئة مشتقة، تحصل على الاسم المحلي للعقدة الحالية.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```

### قيمة الإرجاع

اسم العقدة الحالية مع إلغاء البادئة. على سبيل المثال، **LocalName** هو **book** للعنصر **<bk:book>**. لأنواع العقد التي لا تمتلك اسماً (مثل **[Text](../../../system.text/)**، **Comment**، وما إلى ذلك)، تُعيد هذه الطريقة [String::Empty](../../../system/string/empty/).

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [XmlReader](../)
* مساحة أسماء [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)