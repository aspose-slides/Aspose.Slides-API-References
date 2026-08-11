---
title: LookupPrefix()
second_title: مرجع API Aspose.Slides للغة C++
description: عند تجاوزها في فئة مشتقة، تُعيد أقرب بادئة معرفة في نطاق مساحة الأسماء الحالي لعنوان URI الخاص بمساحة الأسماء.
type: docs
weight: 352
url: /ar/system.xml/xmlwriter/lookupprefix/
---
## XmlWriter::LookupPrefix(String) طريقة


عند تجاوزها في فئة مشتقة، تُعيد أقرب بادئة معرفة في نطاق مساحة الأسماء الحالي للـ URI الخاص بمساحة الأسماء.

```cpp
virtual String System::Xml::XmlWriter::LookupPrefix(String ns)=0
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ns | [String](../../../system/string/) | عنوان URI لمساحة الأسماء التي تريد العثور على بادئتها. |

### قيمة الإرجاع

البادئة المطابقة أو **nullptr** إذا لم يتم العثور على عنوان URI لمساحة أسماء متطابق في النطاق الحالي.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlWriter](../)
* الفضاء الاسمي [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)