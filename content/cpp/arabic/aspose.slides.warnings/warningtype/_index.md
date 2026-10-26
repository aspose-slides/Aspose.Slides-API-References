---
title: WarningType
second_title: مرجع API Aspose.Slides للغة C++
description: يمثل نوعًا من التحذير.
type: docs
weight: 92
url: /ar/aspose.slides.warnings/warningtype/
---
## WarningType enum

يمثل نوعًا من التحذير.

```cpp
enum class WarningType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| SourceFileCorruption | 0 | تم اكتشاف مشكلة في المستند الأصلي تجعل من المحتمل جدًا ألا يتمكن المستند من الفتح إذا تم حفظه بصيغته الأصلية. |
| DataLoss | 1 | سيُفقد النص/الرسم البياني/الصورة أو أي بيانات أخرى تمامًا إما من شجرة المستند بعد التحميل، أو من المستند الذي تم إنشاؤه بعد الحفظ. |
| MajorFormattingLoss | 2 | فقدان كبير في التنسيق. |
| MinorFormattingLoss | 3 | فقدان بسيط في التنسيق. |
| CompatibilityIssue | 4 | هذه مشكلة معروفة ستمنع فتح المستند بواسطة بعض وكلاء المستخدم، أو إصدارات سابقة من وكلاء المستخدم. |
| UnexpectedContent | 99 | بعض المحتوى في المستند الأصلي لم يتم التعرف عليه (أي غير مدعوم)، قد يتسبب ذلك في مشاكل أو قد لا يتسبب في فقدان البيانات/التنسيق. |

## أنظر أيضًا

* النطاق [Aspose::Slides::Warnings](../)
* المكتبة [Aspose.Slides](../../)