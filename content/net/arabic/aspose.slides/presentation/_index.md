---
title: Presentation
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل عرض Microsoft PowerPoint.
type: docs
weight: 9610
url: /ar/aspose.slides/presentation/
---
## فئة Presentation

يمثل عرض Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Presentation](presentation#constructor)() | يُنشئ هذا المنشئ عرضًا جديدًا من الصفر. يحتوي العرض المُنشأ على شريحة واحدة فارغة. |
| [Presentation](presentation#constructor_1)(LoadOptions) | يُنشئ هذا المنشئ عرضًا جديدًا من الصفر. يحتوي العرض المُنشأ على شريحة واحدة فارغة. |
| [Presentation](presentation#constructor_2)(Stream) | يُعد هذا المنشئ الآلية الأساسية لقراءة عرض موجود. |
| [Presentation](presentation#constructor_4)(string) | يحصل هذا المنشئ على مسار ملف المصدر الذي تُقرأ منه محتويات العرض. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | يُعد هذا المنشئ الآلية الأساسية لقراءة عرض موجود. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | يحصل هذا المنشئ على مسار ملف المصدر الذي تُقرأ منه محتويات العرض. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | يرجع جميع أجزاء البيانات المخصصة في الـ Presentation. قراءة فقط [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | يرجع مجموعة جميع ملفات الصوت المضمنة في الـ Presentation. قراءة فقط [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | يرجع مجموعة مؤلفي التعليقات. قراءة فقط [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | يرجع أو يعيّن التاريخ والوقت اللذان سيستبدلان محتوى حقول التاريخ/الوقت. الوقت الافتراضي هو وقت إنشاء كائن الـ Presentation. قراءة/كتابة DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | يرجع البيانات المخصصة للـ Presentation. قراءة فقط [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | يرجع نمط النص الافتراضي للأشكال. قراءة فقط [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | يرجع مجموعة التواقيع المستخدمة لتوقيع الـ Presentation. قراءة فقط [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | يرجع كائن DocumentProperties الذي يحتوي على خصائص المستند المعيارية والمخصصة. قراءة فقط [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | يمثل رقم الشريحة الأولى في الـ Presentation. |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | يرجع مدير الخطوط. قراءة فقط [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | يرجع مدير HeaderFooter الفعلي. قراءة فقط [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | يوفر وصولًا سهلًا إلى جميع الارتباطات التشعبية الموجودة في شرايح الـ Presentation (ليس في القالب، التخطيط، شرايح الملاحظات). قراءة فقط [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | يرجع مجموعة جميع الصور في الـ Presentation. قراءة فقط [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | يرجع قائمة جميع شرايح التخطيط المعرفة في الـ Presentation. قراءة فقط [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | يرجع مدير نموذج النشرة. قراءة فقط [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | يرجع مدير نموذج الملاحظات. قراءة فقط [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | يرجع قائمة جميع شرايح القالب المعرفة في الـ Presentation. قراءة فقط [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | يرجع سمة القالب. قراءة فقط [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | يرجع كائن حجم شريحة الملاحظات. قراءة فقط [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | يحصل على مدير الأذونات لهذا الـ Presentation. قراءة فقط [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | يرجع قائمة جميع أقسام الشريحة المعرفة في الـ Presentation. قراءة فقط [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | يرجع مجموعة تصنيفات الحساسية المطبقة على مستند الـ Presentation. قراءة فقط [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | يرجع قائمة جميع الشرايح المعرفة في الـ Presentation. قراءة فقط [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | يرجع إعدادات عرض الشرائح للـ Presentation. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | يرجع كائن حجم الشريحة. قراءة فقط [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | يرجع معلومات عن التنسيق الذي تم تحميل الـ Presentation منه. قراءة فقط [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | يحصل أو يعيّن مشروع VBA مع ماكروهات الـ Presentation. قراءة/كتابة [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | يرجع مجموعة جميع ملفات الفيديو المضمنة في الـ Presentation. قراءة فقط [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | يحصل على خصائص العرض العامة للـ Presentation. قراءة فقط [`IViewProperties`](../iviewproperties). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | يحرّر جميع الموارد المستخدمة بواسطة كائن الـ Presentation هذا. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | يرجع كائنات Image لجميع شرايح الـ Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | يرجع كائنات Image المصغرة للشرائح المحددة من الـ Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | يرجع كائنات Image المصغرة لجميع شرايح الـ Presentation بالحجم المحدد. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | يرجع كائنات Image المصغرة لجميع شرايح الـ Presentation بمقاس مخصص. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | يرجع كائنات Image المصغرة للشرائح المحددة من الـ Presentation بالحجم المحدد. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | يرجع كائنات Image المصغرة للشرائح المحددة من الـ Presentation بمقاس مخصص. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | يرجع شريحة Slide أو MasterSlide أو LayoutSlide حسب المعرف. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | يبرز جميع التطابقات للتعبير النمطي باللون المحدد. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | يبرز جميع التطابقات للنص النموذجي باللون المحدد. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | يبرز جميع التطابقات للنص النموذجي باللون المحدد. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | يجمع المقاطع ذات التنسيق نفسه في جميع الفقرات داخل جميع الأشكال المقبولة في جميع الشرايح. |
| [RefreshChartsData](../../aspose.slides/presentation/refreshchartsdata)(bool) | يعيد تحميل البيانات لجميع المخططات في الـ Presentation من دفاتر عملها المصدرية. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | يستبدل جميع التطابقات للتعبير النمطي بالسلسلة المحددة. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | يستبدل جميع حدوثات النص المحدد بنص آخر محدد. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | يحفظ جميع شرايح الـ Presentation إلى مجموعة ملفات تمثل ترميز XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | يحفظ جميع شرايح الـ Presentation إلى تدفق بالصيغة المحددة. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | يحفظ جميع شرايح الـ Presentation إلى ملف بالصيغة المحددة. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | يحفظ الشرايح المحددة من الـ Presentation إلى تدفق بالصيغة المحددة مع الحفاظ على أرقام الصفحات. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | يحفظ جميع شرايح الـ Presentation إلى تدفق بالصيغة المحددة ومع خيارات إضافية. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | يحفظ الشرايح المحددة من الـ Presentation إلى ملف بالصيغة المحددة مع الحفاظ على أرقام الصفحات. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | يحفظ الشرايح المحددة من الـ Presentation إلى تدفق بالصيغة المحددة مع الحفاظ على أرقام الصفحات. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | يحفظ الشرايح المحددة من الـ Presentation إلى ملف بالصيغة المحددة مع الحفاظ على أرقام الصفحات. |

### أمثلة

المثال التالي يوضح كيفية إنشاء عرض PowerPoint.

```csharp
[C#]
// إنشاء كائن Presentation يمثل ملف عرض
using (Presentation presentation = new Presentation())
{
    // الحصول على الشريحة الأولى
    ISlide slide = presentation.Slides[0];
    // إضافة شكل تلقائي من النوع خط
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// حفظ ملف العرض.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

المثال التالي يوضح كيفية فتح وحفظ الـ Presentation.

```csharp
[C#]
// تحميل أي ملف مدعوم في Presentation مثل ppt, pptx, odp إلخ.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// حفظ ملف العرض.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### انظر أيضًا

* interface [IPresentation](../ipresentation)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->