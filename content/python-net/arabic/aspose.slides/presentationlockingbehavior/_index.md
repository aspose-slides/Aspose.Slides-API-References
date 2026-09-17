---
title: PresentationLockingBehavior enumeration
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior التعداد

يمثل السلوك المتعلق بمعالجة مصدر [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation) (ملف أو **io.RawIOBase**) أثناء التحميل والعمل مع نسخة من [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation).

يعرض نوع PresentationLockingBehavior الأعضاء التالية:

## الحقول

| الحقل | الوصف |
| :- | :- |
| LOAD_AND_RELEASE | سيتم قفل المصدر فقط لمدة تنفيذ مُنشئ [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation).<br/>            إذا تم تعيين [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/ar/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) إلى false، سيتم تحميل جميع كائنات BLOB في الذاكرة. وإلا، قد تُستخدم وسائل أخرى مثل الملفات المؤقتة. هذا السلوك أبطأ من [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/ar/aspose.slides/presentationlockingbehavior/KEEP_LOCKED)، وإذا كان من الممكن تمرير ملكية المصدر إلى [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation)، يُنصح باستخدام [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/ar/aspose.slides/presentationlockingbehavior/KEEP_LOCKED). |
| KEEP_LOCKED | سيتم قفل المصدر طوال عمر نسخة [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation)، حتى يتم التخلص منها.<br/>            يجب تعيين [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/ar/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) إلى true لاستخدام <br/>            هذا السلوك، وإلا سيتم رمي استثناء. يُنصح بهذا السلوك، فهو أسرع ويستهلك ذاكرة أقل من [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/ar/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |

### ملاحظات

المصدر هو المعامل الممرّر إلى مُنشئ [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). في المثال أدناه، المصدر هو ملف "pres.pptx":

في هذا المثال، سيتم قفل المصدر (ملف "pres.pptx") لمدة عمر نسخة [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation)، أي لا يمكن تغييره أو حذفه بواسطة العملية الأخرى.

### أنظر أيضًا
* الفئة [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)