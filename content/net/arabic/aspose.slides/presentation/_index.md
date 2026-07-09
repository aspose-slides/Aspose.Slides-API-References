---
title: Presentation
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل عرض PowerPoint من Microsoft.
type: docs
weight: 9590
url: /ar/aspose.slides/presentation/
---
## فئة Presentation

يمثل عرض PowerPoint من Microsoft.

```csharp
public sealed class Presentation : IPresentation
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Presentation](presentation#constructor)() | يقوم هذا المنشئ بإنشاء عرض تقديمي جديد من الصفر. يحتوي العرض التقديمي المنشأ على شريحة فارغة واحدة. |
| [Presentation](presentation#constructor_1)(LoadOptions) | يقوم هذا المنشئ بإنشاء عرض تقديمي جديد من الصفر. يحتوي العرض التقديمي المنشأ على شريحة فارغة واحدة. |
| [Presentation](presentation#constructor_2)(Stream) | هذا المنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود. |
| [Presentation](presentation#constructor_4)(string) | هذا المنشئ يحصل على مسار ملف المصدر الذي يتم منه قراءة محتويات العرض التقديمي. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | هذا المنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | هذا المنشئ يحصل على مسار ملف المصدر الذي يتم منه قراءة محتويات العرض التقديمي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | يعيد جميع أجزاء البيانات المخصصة في العرض التقديمي. قراءة فقط [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | يعيد مجموعة جميع ملفات الصوت المضمنة في العرض التقديمي. قراءة فقط [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | يعيد مجموعة مؤلفي التعليقات. قراءة فقط [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | يعيد أو يضبط التاريخ والوقت اللذين سيستبدلان محتوى حقول DateTime. وقت إنشاء كائن Presentation هذا هو الافتراضي. قراءة/كتابة DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | يعيد بيانات مخصصة للعرض التقديمي. قراءة فقط [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | يعيد نمط النص الافتراضي للأشكال. قراءة فقط [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | يعيد مجموعة التوقيعات المستخدمة لتوقيع العرض التقديمي. قراءة فقط [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | يعيد كائن DocumentProperties الذي يحتوي على خصائص المستند القياسية والمخصصة. قراءة فقط [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | يمثل رقم الشريحة الأولى في العرض التقديمي. |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | يعيد مدير الخطوط. قراءة فقط [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | يعيد مدير HeaderFooter الفعلي. قراءة فقط [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | يوفر وصولًا سهلاً إلى جميع الروابط التشعبية الموجودة في جميع شرائح العرض (ليس في القالب، التخطيط، أو شرائح الملاحظات). قراءة فقط [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | يعيد مجموعة جميع الصور في العرض التقديمي. قراءة فقط [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | يعيد قائمة جميع شرائح التخطيط المعرفة في العرض التقديمي. قراءة فقط [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | يعيد مدير handout master. قراءة فقط [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | يعيد مدير notes master. قراءة فقط [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | يعيد قائمة جميع شرائح القالب المعرفة في العرض التقديمي. قراءة فقط [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | يعيد السمة الرئيسية للقالب. قراءة فقط [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | يعيد كائن حجم شريحة الملاحظات. قراءة فقط [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | يحصل على مدير أذونات هذا العرض التقديمي. قراءة فقط [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | يعيد قائمة جميع أقسام الشرائح المعرفة في العرض التقديمي. قراءة فقط [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | يعيد مجموعة تسميات الحساسية المطبقة على مستند العرض التقديمي. قراءة فقط [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | يعيد قائمة جميع الشرائح المعرفة في العرض التقديمي. قراءة فقط [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | يعيد إعدادات عرض الشرائح للعرض التقديمي. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | يعيد كائن حجم الشريحة. قراءة فقط [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | يعيد معلومات حول الصيغة التي تم تحميل العرض التقديمي منها. قراءة فقط [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | يحصل على مشروع VBA أو يضبطه مع ماكروهات العرض التقديمي. قراءة/كتابة [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | يعيد مجموعة جميع ملفات الفيديو المضمنة في العرض التقديمي. قراءة فقط [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | يحصل على خصائص العرض العامة للعرض التقديمي. قراءة فقط [`IViewProperties`](../iviewproperties). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | يطلق جميع الموارد المستخدمة من قبل كائن Presentation هذا. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | يعيد كائنات Image لجميع شرائح العرض التقديمي. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | يعيد كائنات Thumbnail Image للشرائح المحددة من العرض التقديمي. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | يعيد كائنات Thumbnail Image لجميع شرائح العرض التقديمي بالحجم المحدد. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | يعيد كائنات Thumbnail Image لجميع شرائح العرض التقديمي بمقاس مخصص. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | يعيد كائنات Thumbnail Image للشرائح المحددة من العرض التقديمي بالحجم المحدد. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | يعيد كائنات Thumbnail Image للشرائح المحددة من العرض التقديمي بمقاس مخصص. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | يعيد Slide أو MasterSlide أو LayoutSlide حسب المعرّف. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | يبرز جميع التطابقات للعبارة النمطية باللون المحدد. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | يبرز جميع التطابقات للنص العيني باللون المحدد. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | يبرز جميع التطابقات للنص العيني باللون المحدد. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | يجمع القطع النصية ذات الصياغة نفسها في جميع الفقرات داخل جميع الأشكال المقبولة في جميع الشرائح. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | يستبدل جميع التطابقات للعبارة النمطية بالسلسلة المحددة. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | يستبدل جميع مرات ظهور النص المحدد بنص آخر محدد. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | يحفظ جميع شرائح العرض التقديمي إلى مجموعة من الملفات التي تمثل ترميز XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | يحفظ جميع شرائح العرض التقديمي إلى تدفق بالصيغة المحددة. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | يحفظ جميع شرائح العرض التقديمي إلى ملف بالصيغة المحددة. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصيغة المحددة مع الحفاظ على أرقام الصفحات. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | يحفظ جميع شرائح العرض التقديمي إلى تدفق بالصيغة المحددة ومع خيارات إضافية. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصيغة المحددة مع الحفاظ على أرقام الصفحات. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصيغة المحددة مع الحفاظ على أرقام الصفحات. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصيغة المحددة مع الحفاظ على أرقام الصفحات. |

### أمثلة

المثال التالي يوضح كيفية إنشاء عرض PowerPoint.

```csharp
[C#]
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
using (Presentation presentation = new Presentation())
{
    // الحصول على الشريحة الأولى
    ISlide slide = presentation.Slides[0];
    // إضافة شكل تلقائي من النوع خط
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// حفظ ملف العرض التقديمي.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

المثال التالي يوضح كيفية فتح وحفظ عرض تقديمي.

```csharp
[C#]
// تحميل أي ملف مدعوم في Presentation مثل ppt، pptx، odp إلخ.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// حفظ ملف العرض التقديمي.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### انظر أيضًا

* واجهة [IPresentation](../ipresentation)
* نطاق الأسماء [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->