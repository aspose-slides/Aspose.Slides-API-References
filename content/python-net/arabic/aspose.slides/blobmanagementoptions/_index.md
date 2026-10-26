---
title: BlobManagementOptions class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/blobmanagementoptions/
---
## فئة BlobManagementOptions

يمثل الخيارات التي يمكن استخدامها لإدارة قواعد معالجة BLOB وإعدادات BLOB الأخرى.

يعرض نوع BlobManagementOptions الأعضاء التالية:

## المنشئات

| المنşئ | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides/blobmanagementoptions/__init__/#) | ينشئ خيارات إدارة blob افتراضية جديدة. |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/ar/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | تحدد هذه الخاصية ما إذا كان بإمكان كائن فئة Presentation أن يكون مالكًا للمصدر - الملف <br/> أو الدفق أثناء عمر الكائن. إذا كان الكائن مالكًا، فإنه يقفل المصدر. هذا يساعد <br/> على تحسين استهلاك الذاكرة والأداء أثناء العمل مع BLOBs، لكن المصدر (الدفق أو الملف) <br/> لا يمكن تغييره أثناء عمر كائن Presentation. |
| [`is_temporary_files_allowed`](/slides/python-net/ar/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | تحدد هذه الخاصية ما إذا كان يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل بشكل كبير <br/> استهلاك الذاكرة ولكن يتطلب أذونات لإنشاء الملفات.<br/> سيتم حذف جميع الملفات بعد انتهاء العمل مع العرض. |
| [`temp_files_root_path`](/slides/python-net/ar/aspose.slides/blobmanagementoptions/temp_files_root_path/) | المسار الجذر حيث سيتم إنشاء الملفات المؤقتة. سيتم استخدام دليل النظام المؤقت بشكل افتراضي. <br/> يجب أن يكون لعملية الاستضافة أذونات <br/> لإنشاء الملفات والمجلدات هناك. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/ar/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | تحدد الحد الأقصى الإجمالي للحجم (بالبايت) الذي قد تشغله جميع BLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع BLOBs<br/> في الذاكرة؛ فقط عندما يتم الوصول إلى هذا الحد تُستَخدم آليات بديلة (مثل الملفات المؤقتة). الاحتفاظ بـ BLOBs في الذاكرة يزيد الأداء إلى الحد الأقصى لكنه قد يسبب استهلاكًا عاليًا للذاكرة. استخدم<br/> هذه الخاصية لتعديل السلوك وفقًا لبيئتك أو متطلباتك. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)