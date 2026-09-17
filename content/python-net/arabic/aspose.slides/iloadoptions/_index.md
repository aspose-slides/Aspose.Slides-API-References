---
title: ILoadOptions class
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/iloadoptions/
---
## الفئة ILoadOptions

يسمح بتحديد خيارات إضافية (مثل التنسيق أو الخط الافتراضي) عند تحميل عرض تقديمي.

نوع ILoadOptions يعرض الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`load_format`](/slides/python-net/ar/aspose.slides/iloadoptions/load_format/) | تُعيد أو تعيّن تنسيق عرض تقديمي للتحميل.<br/>            قراءة/كتابة [`LoadFormat`](/slides/python-net/ar/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/ar/aspose.slides/iloadoptions/default_regular_font/) | تُعيد أو تعيّن الخط العادي المستخدم في حال عدم العثور على الخط المصدر.<br/>            قراءة-كتابة **str**. |
| [`default_symbol_font`](/slides/python-net/ar/aspose.slides/iloadoptions/default_symbol_font/) | تُعيد أو تعيّن خط الرموز المستخدم في حال عدم العثور على الخط المصدر.<br/>            قراءة-كتابة **str**. |
| [`default_asian_font`](/slides/python-net/ar/aspose.slides/iloadoptions/default_asian_font/) | تُعيد أو تعيّن الخط الآسيوي المستخدم في حال عدم العثور على الخط المصدر.<br/>            قراءة-كتابة **str**. |
| [`password`](/slides/python-net/ar/aspose.slides/iloadoptions/password/) | تُحصل أو تعيّن كلمة المرور.<br/>            قراءة-كتابة **str**. |
| [`only_load_document_properties`](/slides/python-net/ar/aspose.slides/iloadoptions/only_load_document_properties/) | هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور.<br/>            تعني القيمة true أن خصائص المستند فقط يجب أن تُحمَّل من ملف عرض مشفر ويجب تجاهل كلمة المرور.<br/>            تعني القيمة false أنه يجب تحميل العرض المشفر بالكامل باستخدام كلمة المرور الصحيحة.<br/>            إذا لم يكن العرض مشفرًا فسيتم دائمًا تجاهل قيمة الخاصية.<br/>            إذا لم تكن خصائص المستند لملف مشفر عامة وكانت قيمة الخاصية true فستُعَدّ خصائص المستند غير قابلة للتحميل وسيتم إلقاء استثناء.<br/>            قراءة-كتابة **bool**. |
| [`warning_callback`](/slides/python-net/ar/aspose.slides/iloadoptions/warning_callback/) | تُعيد أو تعيّن كائنًا يتلقى التحذيرات ويحدد ما إذا كانت عملية التحميل <br/>            ستستمر أم ستُوقف.<br/>            قراءة/كتابة [`IWarningCallback`](/slides/python-net/ar/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/ar/aspose.slides/iloadoptions/blob_management_options/) | تمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة كائنات البيانات الثنائية الكبيرة (BLOBs)،<br/>            مثل استخدام الملفات المؤقتة أو الحد الأقصى لبايتات BLOBs في الذاكرة. تُرَكّز هذه الخيارات على تحقيق أفضل نسبة أداء/استهلاك للذاكرة لبيئة أو متطلبات معينة.<br/>            كائن البيانات الثنائية الكبيرة (BLOB) هو بيانات ثنائية مخزَّنة ككيان واحد - أي يمكن أن يكون BLOB <br/>            صوتًا أو فيديو أو العرض نفسه. |
| [`document_level_font_sources`](/slides/python-net/ar/aspose.slides/iloadoptions/document_level_font_sources/) | تحدد مصادر الخطوط الخارجية التي سيستخدمها العرض.<br/>            هذه الخطوط متاحة للعرض طوال فترة حياته ولا يتم مشاركتها مع عروض أخرى |
| [`interruption_token`](/slides/python-net/ar/aspose.slides/iloadoptions/interruption_token/) | الرمز لمراقبة طلبات الإيقاف.<br/>            <br/>            يدير هذا الرمز عمر كامل كائن [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). أي عملية طويلة الأمد، مثل تحميل العرض أو حفظه، سيتم إيقافها عبر استدعاء طريقة [`IInterruptionTokenSource.interrupt`](/slides/python-net/ar/aspose.slides/iinterruptiontokensource/interrupt) الخاصة بـ <br/>            [`IInterruptionTokenSource`](/slides/python-net/ar/aspose.slides/iinterruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/ar/aspose.slides/iloadoptions/resource_loading_callback/) | تُعيد أو تعيّن واجهة رد الاتصال التي تدير تحميل الموارد الخارجية.<br/>            قراءة/كتابة [`IResourceLoadingCallback`](/slides/python-net/ar/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/ar/aspose.slides/iloadoptions/spreadsheet_options/) | تمثل الخيارات التي يمكن استخدامها لتحديد سلوك جداول البيانات الإضافية. |
| [`default_text_language`](/slides/python-net/ar/aspose.slides/iloadoptions/default_text_language/) | تُعيد أو تعيّن اللغة الافتراضية لنص العرض.<br/>             قراءة-كتابة **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/ar/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المدمجة أثناء تحميل العرض.<br/>            <br/>أنواع الكائنات الثنائية المدمجة:<br/><br/><br/>* مشروع VBA [`IPresentation.vba_project`](/slides/python-net/ar/aspose.slides/ipresentation/vba_project)<br/>* بيانات كائن OLE المدمجة [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* بيانات تحكم ActiveX الثنائية [`IControl.active_x_control_binary`](/slides/python-net/ar/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            قراءة-كتابة **bool**. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)