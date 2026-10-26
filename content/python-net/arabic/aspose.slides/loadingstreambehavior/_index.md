---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/loadingstreambehavior/
---
## تعداد LoadingStreamBehavior

يُعتبر **io.RawIOBase** الممرَّر إلى طريقة ما ككائن كبير ثنائي (BLOB) (انظر وصف [`IBlobManagementOptions`](/slides/python-net/ar/aspose.slides/iblobmanagementoptions)). قيم هذا التعداد تحدد كيفية معالجة **io.RawIOBase** عندما يُمرَّر إلى الطريقة. اعتمادًا على المتطلبات، يمكن اتخاذ قرارات مختلفة لتوفير السلوك الأكثر كفاءة.

يعرض النوع LoadingStreamBehavior الأعضاء التالية:

## الحقول

| العضو | الوصف |
| :- | :- |
| READ_STREAM_AND_RELEASE | سيتم قراءة التدفق حتى النهاية ثم إصداره - أي أنه سيُضمن ألا يتم استخدام هذا التدفق <br/>            من قبل كائن [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation) في المستقبل. يمكن إغلاقه بواسطة شفرة العميل <br/>            أو استخدامه بأي طريقة أخرى. |
| KEEP_LOCKED | سيتم قفل التدفق داخل كائن [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation)، أي سيتم نقل ملكية <br/>            التدفق. سيكون كائن [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation) مسؤولاً عن <br/>            التخلص الصحيح من التدفق عندما يُتَخلَّص من هذا الكائن نفسه. <br/>            هذا السلوك مفيد للغاية عندما تحتاج إلى تسلسل ملف BLOB كبير (مثل فيديو أو صوت كبير -انظر وصف [`IBlobManagementOptions`](/slides/python-net/ar/aspose.slides/iblobmanagementoptions)) وتريد منع تحميل <br/>            هذا الملف إلى الذاكرة أو مشكلات أداء أخرى. يمكنك فقط فتح **System.IO.FileStream** <br/>            لهذا الملف وتمريره إلى طريقة، مع اختيار [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/ar/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior. |

### راجع أيضًا
* فئة [`IBlobManagementOptions`](/slides/python-net/ar/aspose.slides/iblobmanagementoptions)
* فئة [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)