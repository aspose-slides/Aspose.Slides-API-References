---
title: IPresentation
second_title: مرجع واجهة برمجة تطبيقات Aspose.Sildes لـ .NET
description: مستند العرض التقديمي
type: docs
weight: 6770
url: /ar/aspose.slides/ipresentation/
---
## واجهة IPresentation

مستند العرض التقديمي

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | إرجاع جميع أجزاء البيانات المخصصة في العرض التقديمي. قراءة فقط [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | إرجاع واجهة IDisposable. قراءة فقط IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | يسمح بالحصول على واجهة IPresentationComponent الأساسية. قراءة فقط [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | إرجاع مجموعة جميع ملفات الصوت المدمجة في العرض التقديمي. قراءة فقط [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | إرجاع مجموعة مؤلفي التعليقات. قراءة فقط [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | إرجاع أو تعيين التاريخ والوقت اللذان سيستبدلان محتوى حقول datetime. وقت إنشاء كائن Presentation هذا بشكل افتراضي. قراءة/كتابة DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | إرجاع البيانات المخصصة للعرض التقديمي. قراءة فقط [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | إرجاع نمط النص الافتراضي للأشكال. قراءة فقط [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | إرجاع مجموعة التوقيعات المستخدمة لتوقيع العرض التقديمي. قراءة فقط [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | إرجاع كائن DocumentProperties الذي يحتوي على خصائص المستند القياسية والمخصصة. قراءة فقط [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | يمثل رقم الشريحة الأولى في العرض التقديمي. قراءة/كتابة Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | إرجاع مدير الخطوط. قراءة فقط [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | إرجاع مدير HeaderFooter للعرض التقديمي. قراءة فقط [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | يوفر وصولاً سهلاً إلى جميع الروابط التشعبية الموجودة في جميع شرائح العرض التقديمي (ليس في الشرائح الرئيسية، التخطيط، ملاحظات). قراءة فقط [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | إرجاع مجموعة جميع الصور في العرض التقديمي. قراءة فقط [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | إرجاع قائمة بجميع شرائح التخطيط المعرفة في العرض التقديمي. قراءة فقط [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | إرجاع مدير النسخة المطبوعة الرئيسية. قراءة فقط [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | إرجاع مدير ملاحظات الرئيسة. قراءة فقط [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | إرجاع قائمة بجميع الشرائح الرئيسية المعرفة في العرض التقديمي. قراءة فقط [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | إرجاع سمة الرئيسة للعرض التقديمي. قراءة فقط [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | إرجاع كائن حجم شريحة الملاحظات. قراءة فقط [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | إرجاع مدير الأذونات لهذا العرض التقديمي. قراءة فقط [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | إرجاع قائمة بجميع أقسام الشرائح المعرفة في العرض التقديمي. قراءة فقط [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | إرجاع مجموعة تسميات الحساسية المطبقة على مستند العرض التقديمي. قراءة فقط [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | إرجاع قائمة بجميع الشرائح المعرفة في العرض التقديمي. قراءة فقط [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | إرجاع كائن حجم الشريحة. قراءة فقط [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | إرجاع معلومات عن الصيغة التي تم تحميل العرض التقديمي منها. قراءة فقط [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | إرجاع مشروع VBA مع ماكروهات العرض التقديمي. قراءة/كتابة [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | إرجاع مجموعة جميع ملفات الفيديو المدمجة في العرض التقديمي. قراءة فقط [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | إرجاع خصائص العرض الواسعة للعرض التقديمي. قراءة فقط [`IViewProperties`](../iviewproperties). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | إرجاع كائنات صورة مصغرة لجميع شرائح العرض التقديمي. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | إرجاع كائنات Bitmap مصغرة للشرائح المحددة من العرض التقديمي. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | إرجاع كائنات صورة مصغرة لجميع شرائح العرض التقديمي بالحجم المحدد. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | إرجاع كائنات صورة مصغرة لجميع شرائح العرض التقديمي مع مقياس مخصص. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | إرجاع كائنات صورة مصغرة للشرائح المحددة من العرض التقديمي بالحجم المحدد. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | إرجاع كائنات صورة مصغرة للشرائح المحددة من العرض التقديمي مع مقياس مخصص. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | إرجاع Slide أو MasterSlide أو LayoutSlide بحسب المعرف. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | تمييز جميع التطابقات للتعبير النمطي باللون المحدد. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | تمييز جميع تطابقات النص النموذجي باللون المحدد. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | تمييز جميع تطابقات النص النموذجي باللون المحدد. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | دمج مقاطع النص ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال المتاحة في جميع الشرائح. |
| [RefreshChartsData](../../aspose.slides/ipresentation/refreshchartsdata)(bool) | إعادة تحميل البيانات لجميع المخططات في العرض التقديمي من دفاتر العمل المصدر. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | استبدال جميع تطابقات التعبير النمطي بالسلسلة المحددة. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | استبدال جميع حالات النص المحدد بنص آخر محدد. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | حفظ جميع شرائح العرض التقديمي إلى مجموعة من الملفات التي تمثل ترميز XAML. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | حفظ جميع شرائح العرض التقديمي إلى تدفق بالصيغة المحددة. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | حفظ جميع شرائح العرض التقديمي إلى ملف بالصّيغة المحددة. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | حفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصّيغة المحددة. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | حفظ جميع شرائح العرض التقديمي إلى تدفق بالصّيغة المحددة ومع خيارات إضافية. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | حفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصّيغة المحددة. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | حفظ جميع شرائح العرض التقديمي إلى ملف بالصّيغة المحددة ومع خيارات إضافية. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | حفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصّيغة المحددة. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | حفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصّيغة المحددة. |

### انظر أيضًا

* واجهة [IPresentationComponent](../ipresentationcomponent)
* نطاق [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->