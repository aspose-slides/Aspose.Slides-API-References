---
title: Presentation
second_title: مرجع API الخاص بـ Aspose.Sildes لـ .NET
description: يمثل عرضًا تقديميًا من Microsoft PowerPoint.
type: docs
weight: 9590
url: /ar/aspose.slides/presentation/
---
## فئة Presentation

تمثل عرضاً تقديميًا من Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Presentation](presentation#constructor)() | يقوم هذا المُنشئ بإنشاء عرض تقديمي جديد من الصفر. يحتوي العرض المُنشأ على شريحة فارغة واحدة. |
| [Presentation](presentation#constructor_1)(LoadOptions) | يقوم هذا المُنشئ بإنشاء عرض تقديمي جديد من الصفر. يحتوي العرض المُنشأ على شريحة فارغة واحدة. |
| [Presentation](presentation#constructor_2)(Stream) | هذا المُنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود. |
| [Presentation](presentation#constructor_4)(string) | هذا المُنشئ يحصل على مسار ملف المصدر الذي تُقرأ منه محتويات العرض التقديمي. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | هذا المُنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | هذا المُنشئ يحصل على مسار ملف المصدر الذي تُقرأ منه محتويات العرض التقديمي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | يرجع جميع أجزاء البيانات المخصصة في العرض التقديمي. قراءة فقط [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | يرجع مجموعة جميع ملفات الصوت المدمجة في العرض التقديمي. قراءة فقط [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | يرجع مجموعة مؤلفي التعليقات. قراءة فقط [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | يرجع أو يضبط التاريخ والوقت اللذين سيستبدلان محتوى حقول datetime. وقت إنشاء كائن Presentation هذا بشكل افتراضي. قراءة/كتابة DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | يرجع البيانات المخصصة للعرض التقديمي. قراءة فقط [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | يرجع نمط النص الافتراضي للأشكال. قراءة فقط [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | يرجع مجموعة التوقيعات المستخدمة لتوقيع العرض التقديمي. قراءة فقط [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | يرجع كائن DocumentProperties الذي يحتوي على خصائص المستند القياسية والمخصصة. قراءة فقط [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | يمثل رقم الشريحة الأولى في العرض التقديمي |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | يرجع مدير الخطوط. قراءة فقط [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | يرجع مدير HeaderFooter الفعلي. قراءة فقط [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | يوفر وصولاً سهلاً إلى جميع الارتباطات التشعبية الموجودة في جميع شرائح العرض التقديمي (ليس في الشرائح الرئيسية أو تخطيط أو ملاحظات). قراءة فقط [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | يرجع مجموعة جميع الصور في العرض التقديمي. قراءة فقط [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | يرجع قائمة جميع شرائح التخطيط المعرفة في العرض التقديمي. قراءة فقط [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | يرجع مدير نسخة المستندات الرئيسية. قراءة فقط [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | يرجع مدير ملاحظات الرئيسي. قراءة فقط [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | يرجع قائمة جميع الشرائح الرئيسية المعرفة في العرض التقديمي. قراءة فقط [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | يرجع سمة الرئيسة. قراءة فقط [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | يرجع كائن حجم شريحة الملاحظات. قراءة فقط [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | يحصل على مدير أذونات هذا العرض التقديمي. قراءة فقط [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | يرجع قائمة جميع أقسام الشرائح المعرفة في العرض التقديمي. قراءة فقط [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | يرجع مجموعة تصنيفات الحساسية المطبقة على وثيقة العرض التقديمي. قراءة فقط [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | يرجع قائمة جميع الشرائح المعرفة في العرض التقديمي. قراءة فقط [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | يرجع إعدادات عرض الشرائح للعرض التقديمي. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | يرجع كائن حجم الشريحة. قراءة فقط [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | يرجع معلومات حول الصيغة التي تم تحميل العرض التقديمي منها. قراءة فقط [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | يحصل أو يضبط مشروع VBA مع ماكروات العرض التقديمي. قراءة/كتابة [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | يرجع مجموعة جميع ملفات الفيديو المدمجة في العرض التقديمي. قراءة فقط [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | يحصل على خصائص العرض العامة للعرض التقديمي. قراءة فقط [`IViewProperties`](../iviewproperties). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | يطلق جميع الموارد المستخدمة بواسطة كائن Presentation هذا. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | يرجع كائنات Image لجميع شرائح العرض التقديمي. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | يرجع كائنات Thumbnail Image للشرائح المحددة من العرض التقديمي. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | يرجع كائنات Thumbnail Image لجميع شرائح العرض التقديمي بالحجم المحدد. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | يرجع كائنات Thumbnail Image لجميع شرائح العرض التقديمي مع مقياس مخصص. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | يرجع كائنات Thumbnail Image للشرائح المحددة من العرض التقديمي بالحجم المحدد. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | يرجع كائنات Thumbnail Image للشرائح المحددة من العرض التقديمي مع مقياس مخصص. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | يرجع Slide أو MasterSlide أو LayoutSlide حسب المعرف. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | يبرز جميع مطابقات التعبير النمطي باللون المحدد. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | يبرز جميع مطابقات النص النموذجي باللون المحدد. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | يبرز جميع مطابقات النص النموذجي باللون المحدد. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | يدمج المقاطع ذات نفس التنسيق في جميع الفقرات داخل جميع الأشكال المقبولة في جميع الشرائح. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | يستبدل جميع مطابقات التعبير النمطي بالسلسلة المحددة. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | يستبدل جميع تكرارات النص المحدد بنص آخر محدد. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | يحفظ جميع شرائح العرض التقديمي إلى مجموعة من الملفات التي تمثل ترميز XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | يحفظ جميع شرائح العرض التقديمي إلى تدفق بالتنسيق المحدد. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | يحفظ جميع شرائح العرض التقديمي إلى ملف بالتنسيق المحدد. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالتنسيق المحدد مع الحفاظ على أرقام الصفحات. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | يحفظ جميع شرائح العرض التقديمي إلى تدفق بالتنسيق المحدد ومع خيارات إضافية. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالتنسيق المحدد مع الحفاظ على أرقام الصفحات. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالتنسيق المحدد مع الحفاظ على أرقام الصفحات. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالتنسيق المحدد مع الحفاظ على أرقام الصفحات. |

### الأمثلة

المثال التالي يوضح كيفية إنشاء عرض PowerPoint Presentation.

```csharp
[C#]
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
using (Presentation presentation = new Presentation())
{
    // الحصول على الشريحة الأولى
    ISlide slide = presentation.Slides[0];
    // إضافة AutoShape من النوع Line
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// حفظ ملف العرض التقديمي.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

المثال التالي يوضح كيفية فتح وحفظ العرض التقديمي.

```csharp
[C#]
// تحميل أي ملف مدعوم في Presentation مثل ppt, pptx, odp وغيرها.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// حفظ ملف العرض التقديمي.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### انظر أيضًا

* واجهة [IPresentation](../ipresentation)
* مساحة اسم [Aspose.Slides](../../aspose.slides)
* مجموعة [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->