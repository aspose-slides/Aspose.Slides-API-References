---
title: LoadOptions class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/loadoptions/
---
## LoadOptions فئة

يسمح بتحديد خيارات إضافية (مثل التنسيق أو الخط الافتراضي) عند تحميل عرض تقديمي.

يعرّف نوع LoadOptions الأعضاء التالية:

## المُنشئات

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides/loadoptions/__init__/#) | ينشئ خيارات تحميل افتراضية جديدة. |
| [`__init__(self, load_format)`](/slides/python-net/ar/aspose.slides/loadoptions/__init__/#loadformat) | ينشئ خيارات تحميل جديدة. |

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`load_format`](/slides/python-net/ar/aspose.slides/loadoptions/load_format/) | ترجع أو تضبط تنسيق عرض تقديمي للتحميل.<br/>            قراءة/كتابة [`LoadFormat`](/slides/python-net/ar/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/ar/aspose.slides/loadoptions/default_regular_font/) | ترجع أو تضبط الخط العادي المستخدم في حالة عدم العثور على الخط الأصلي.<br/>            قراءة/كتابة **str**. |
| [`default_symbol_font`](/slides/python-net/ar/aspose.slides/loadoptions/default_symbol_font/) | ترجع أو تضبط خط الرموز المستخدم في حالة عدم العثور على الخط الأصلي.<br/>            قراءة/كتابة **str**. |
| [`default_asian_font`](/slides/python-net/ar/aspose.slides/loadoptions/default_asian_font/) | ترجع أو تضبط الخط الآسيوي المستخدم في حالة عدم العثور على الخط الأصلي.<br/>            قراءة/كتابة **str**. |
| [`password`](/slides/python-net/ar/aspose.slides/loadoptions/password/) | ترجع أو تضبط كلمة المرور.<br/>            قراءة/كتابة **str**. |
| [`only_load_document_properties`](/slides/python-net/ar/aspose.slides/loadoptions/only_load_document_properties/) | هذه الخاصية منطقية إذا كان ملف العرض محميًا بكلمة مرور.<br/>            قيمة true تعني أنه يجب تحميل خصائص المستند فقط من ملف عرض مشفر وتجاهل كلمة المرور.<br/>            قيمة false تعني أنه يجب تحميل العرض المشفر بالكامل باستخدام كلمة المرور الصحيحة.<br/>            إذا لم يكن العرض مشفرًا فستُهمل قيمة الخاصية دائمًا.<br/>            إذا لم تكن خصائص المستند لملف مشفر عامة وكانت قيمة الخاصية true فإن<br/>            لا يمكن تحميل خصائص المستند وستُرمى استثناء.<br/>            قراءة/كتابة **bool**. |
| [`warning_callback`](/slides/python-net/ar/aspose.slides/loadoptions/warning_callback/) | ترجع أو تضبط كائنًا يتلقى التحذيرات ويحدد ما إذا كان عملية التحميل<br/>            ستستمر أو ستُوقف.<br/>            قراءة/كتابة [`IWarningCallback`](/slides/python-net/ar/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/ar/aspose.slides/loadoptions/blob_management_options/) | يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة كائنات البيانات الكبيرة (BLOBs)،<br/>            مثل استخدام الملفات المؤقتة أو الحد الأقصى لعدد بايتات BLOBs في الذاكرة. تم تصميم هذه الخيارات لتحديد<br/>            أفضل نسبة بين الأداء واستهلاك الذاكرة لبيئة أو متطلبات معينة.<br/>            كائن البيانات الكبيرة (BLOB) هو بيانات ثنائية مخزنة ككيان واحد - أي أن BLOB يمكن أن يكون<br/>            صوتًا أو فيديو أو العرض التقديمي نفسه. |
| [`document_level_font_sources`](/slides/python-net/ar/aspose.slides/loadoptions/document_level_font_sources/) | يحدد مصادر الخطوط الخارجية التي سيستخدمها العرض.<br/>            هذه الخطوط متاحة للعرض طوال فترة حياته ولا يتم مشاركتها مع عروض تقديمية أخرى. |
| [`interruption_token`](/slides/python-net/ar/aspose.slides/loadoptions/interruption_token/) | الرمز لمراقبة طلبات الإيقاف.<br/>            <br/>            يدير هذا الرمز كامل عمر كائن [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). أي عملية طويلة الأمد، مثل تحميل<br/>            أو حفظ العرض، ستُقاطع عبر استدعاء طريقة [`InterruptionTokenSource.interrupt`](/slides/python-net/ar/aspose.slides/interruptiontokensource/interrupt) الخاصة<br/>            بـ [`InterruptionTokenSource`](/slides/python-net/ar/aspose.slides/interruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/ar/aspose.slides/loadoptions/resource_loading_callback/) | ترجع أو تضبط واجهة الاستدعاء الراجعة التي تدير تحميل الموارد الخارجية.<br/>            قراءة/كتابة [`IResourceLoadingCallback`](/slides/python-net/ar/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/ar/aspose.slides/loadoptions/spreadsheet_options/) | يحصل على خيارات جداول البيانات. على سبيل المثال، تؤثر هذه الخيارات على حساب صيغ المخططات. |
| [`default_text_language`](/slides/python-net/ar/aspose.slides/loadoptions/default_text_language/) | ترجع أو تضبط اللغة الافتراضية لنص العرض.<br/>             قراءة/كتابة **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/ar/aspose.slides/loadoptions/delete_embedded_binary_objects/) | يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المضمنة أثناء تحميل العرض.<br/>            <br/>أنواع الكائنات الثنائية المضمنة:<br/><br/><br/>* مشروع VBA [`IPresentation.vba_project`](/slides/python-net/ar/aspose.slides/ipresentation/vba_project)<br/>* بيانات كائن OLE المضمنة [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* بيانات التحكم ActiveX الثنائية [`IControl.active_x_control_binary`](/slides/python-net/ar/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            قراءة/كتابة **bool**. |


### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)