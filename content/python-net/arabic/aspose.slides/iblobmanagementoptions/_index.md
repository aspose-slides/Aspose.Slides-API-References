---
title: IBlobManagementOptions class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions فئة

كائن ثنائي كبير (BLOB) هو بيانات ثنائية مخزنة ككيان واحد - أي أن BLOB يمكن أن يكون 
            صوتًا أو فيديو أو عرضًا تقديميًا بنفسه. تُستخدم مجموعة من التقنيات لتحسين استهلاك الذاكرة 
            أثناء التعامل مع BLOBs - التي قد تكون مخزنة مسبقًا في العرض أو تُضاف لاحقًا برمجيًا. 
            باستخدام [`IBlobManagementOptions`](/slides/python-net/ar/aspose.slides/iblobmanagementoptions) يمكنك تغيير جوانب سلوك مختلفة تتعلق بمعالجة BLOBs 
            خلال عمر المثيل [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation).

نوع IBlobManagementOptions يعرض الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/ar/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | تحدد هذه الخاصية ما إذا كان كائن من الفئة Presentation يمكن أن يكون مالكًا للمصدر - الملف <br/>            أو التدفق خلال عمر المثيل. إذا كان المثيل مالكًا، فإنه يقفل المصدر. هذا يساعد <br/>            على تحسين استهلاك الذاكرة والأداء أثناء التعامل مع BLOBs، لكن لا يمكن تغيير المصدر (التدفق أو الملف) <br/>            خلال عمر المثيل الخاص بـ Presentation. هذا مثال: |
| [`is_temporary_files_allowed`](/slides/python-net/ar/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | تحدد هذه الخاصية ما إذا كان يمكن إنشاء ملفات مؤقتة أثناء التعامل مع BLOBs، مما يقلل بشكل كبير <br/>            من استهلاك الذاكرة ولكنه يتطلب أذونات لإنشاء الملفات.<br/>            سيتم حذف جميع الملفات بعد الانتهاء من العمل مع العرض التقديمي. |
| [`temp_files_root_path`](/slides/python-net/ar/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | مسار الجذر حيث سيتم إنشاء الملفات المؤقتة. سيتم استخدام الدليل المؤقت للنظام بشكل افتراضي. <br/>            يجب أن تكون لعملية الاستضافة الأذونات <br/>            لإنشاء الملفات والمجلدات هناك. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/ar/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | تحدد الحد الأقصى الإجمالي للحجم (بالبايت) الذي قد تشغله جميع BLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع BLOBs<br/>            في الذاكرة؛ وعند الوصول إلى هذا الحد تُستَخدم آليات بديلة (مثل الملفات المؤقتة). الاحتفاظ بـ BLOBs في الذاكرة يعزز الأداء لكنه قد يؤدي إلى استهلاك عالي للذاكرة. استخدم<br/>            هذه الخاصية لتخصيص السلوك وفقًا لبيئتك أو متطلباتك. |

### انظر أيضًا
* فئة [`IBlobManagementOptions`](/slides/python-net/ar/aspose.slides/iblobmanagementoptions)
* فئة [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)