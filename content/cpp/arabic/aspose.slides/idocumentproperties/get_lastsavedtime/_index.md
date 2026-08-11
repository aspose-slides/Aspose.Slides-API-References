---
title: get_LastSavedTime()
second_title: مرجع API Aspose.Slides للغة C++
description: "يعيد تاريخ آخر تعديل للعرض التقديمي. القيم في UTC.P للقراءة فقط في حالة Presentation.DocumentProperties (لأنها سيتم تحديثها داخليًا أثناء عملية حفظ كائن IPresentation). يمكن تغييره عبر مثيل DocumentProperties الذي تُعيده الطريقة IPresentationInfo::ReadDocumentProperties. يرجى الاطلاع على المثال في ملخص طريقة IPresentationInfo::UpdateDocumentProperties."
type: docs
weight: 378
url: /ar/aspose.slides/idocumentproperties/get_lastsavedtime/
---
## IDocumentProperties::get_LastSavedTime() طريقة

Returns the date a presentation was last modified. Values are in UTC.P للقراءة فقط في حالة Presentation.DocumentProperties (because it will be updated internally while [IPresentation](../../ipresentation/) object saving process). Can be changed via [DocumentProperties](../../documentproperties/) instance returning by طريقة [IPresentationInfo::ReadDocumentProperties](../../ipresentationinfo/readdocumentproperties/) Please see the example in [IPresentationInfo::UpdateDocumentProperties](../../ipresentationinfo/updatedocumentproperties/) ملخص الطريقة.

```cpp
virtual System::DateTime Aspose::Slides::IDocumentProperties::get_LastSavedTime()=0
```

## انظر أيضًا

* فئة [DateTime](../../../system/datetime/)
* فئة [IDocumentProperties](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)