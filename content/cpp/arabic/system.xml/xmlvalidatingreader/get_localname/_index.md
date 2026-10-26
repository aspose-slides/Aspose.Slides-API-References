---
title: get_LocalName()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يعيد الاسم المحلي للعقدة الحالية.
type: docs
weight: 27
url: /ar/system.xml/xmlvalidatingreader/get_localname/
---
## XmlValidatingReader::get_LocalName() طريقة

يعيد الاسم المحلي للعقدة الحالية.

```cpp
String System::Xml::XmlValidatingReader::get_LocalName() override
```

### قيمة الإرجاع

اسم العقدة الحالية مع إزالة البادئة. على سبيل المثال، **LocalName** هو **book** للعنصر **<bk:book>**. لأنواع العقد التي لا تملك اسمًا (مثل **[Text](../../../system.text/)**، **Comment**، وما إلى ذلك)، تعيد هذه الطريقة [String::Empty](../../../system/string/empty/).

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlValidatingReader](../)
* النطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)