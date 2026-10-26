---
title: get_LocalName()
second_title: مرجع API Aspose.Slides لـ C++
description: يعيد الاسم المحلي للعقدة الحالية.
type: docs
weight: 27
url: /ar/system.xml/xmltextreader/get_localname/
---
## XmlTextReader::get_LocalName() method

يعيد الاسم المحلي للعقدة الحالية.

```cpp
String System::Xml::XmlTextReader::get_LocalName() override
```

### قيمة الإرجاع

اسم العقدة الحالية بعد إزالة البادئة. على سبيل المثال، **LocalName** هو **book** للعنصر **<bk:book>**. بالنسبة لأنواع العقد التي ليس لها اسم (مثل **[Text](../../../system.text/)**، **Comment**، وما إلى ذلك)، هذه الطريقة تُعيد [String::Empty](../../../system/string/empty/).

## انظر أيضاً

* الفئة [String](../../../system/string/)
* الفئة [XmlTextReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)