---
title: get_LocalName()
second_title: Aspose.Slides لواجهة برمجة التطبيقات C++
description: يرجع الاسم المحلي للعقدة الحالية.
type: docs
weight: 27
url: /ar/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName() طريقة

يرجع الاسم المحلي للعقدة الحالية.

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```

### قيمة الإرجاع

اسم العقدة الحالية مع إزالة البادئة. على سبيل المثال، **LocalName** هو **book** للعنصر **<bk:book>**. لأنواع العقد التي لا تمتلك اسماً (مثل **[Text](../../../system.text/)**، **Comment**، وهكذا)، تُعيد هذه الطريقة [String::Empty](../../../system/string/empty/).

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlNodeReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)