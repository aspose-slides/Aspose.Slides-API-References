---
title: IPresentation
second_title: مرجع API Aspose.Sildes لـ .NET
description: وثيقة العرض التقديمي
type: docs
weight: 6750
url: /ar/aspose.slides/ipresentation/
---
## IPresentation واجهة

وثيقة العرض التقديمي

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | يعيد جميع أجزاء البيانات المخصصة في العرض التقديمي. للقراءة فقط [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | يعيد واجهة IDisposable. للقراءة فقط IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | يتيح الحصول على واجهة IPPresentationComponent الأساسية. للقراءة فقط [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | يعيد مجموعة جميع ملفات الصوت المضمنة في العرض التقديمي. للقراءة فقط [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | يعيد مجموعة مؤلفي التعليقات. للقراءة فقط [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | يعيد أو يضبط التاريخ والوقت اللذان سيستبدلان محتوى حقول التاريخ والوقت. الوقت هو وقت إنشاء كائن العرض التقديمي هذا افتراضيًا. للقراءة والكتابة DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | يعيد البيانات المخصصة للعرض التقديمي. للقراءة فقط [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | يعيد نمط النص الافتراضي للأشكال. للقراءة فقط [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | يعيد مجموعة التواقيع المستخدمة لتوقيع العرض التقديمي. للقراءة فقط [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | يعيد كائن DocumentProperties الذي يحتوي على خصائص المستند القياسية والمخصصة. للقراءة فقط [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | يمثل رقم الشريحة الأولى في العرض التقديمي. للقراءة والكتابة Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | يعيد مدير الخطوط. للقراءة فقط [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | يعيد مدير رأس وتذييل للعرض التقديمي. للقراءة فقط [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | يوفر وصولًا سهلاً إلى جميع الروابط التشعبية الموجودة في جميع شرائح العرض التقديمي (ليس في الشرائح الرئيسية أو تخطيط أو ملاحظات). للقراءة فقط [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | يعيد مجموعة جميع الصور في العرض التقديمي. للقراءة فقط [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | يعيد قائمة بجميع شرائح التخطيط المعرفة في العرض التقديمي. للقراءة فقط [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | يعيد مدير نموذج النشرات. للقراءة فقط [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | يعيد مدير نموذج الملاحظات. للقراءة فقط [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | يعيد قائمة بجميع الشرائح الرئيسية المعرفة في العرض التقديمي. للقراءة فقط [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | يعيد السمة الرئيسية للعرض التقديمي. للقراءة فقط [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | يعيد كائن حجم شريحة الملاحظات. للقراءة فقط [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | يحصل على مدير الأذونات لهذا العرض التقديمي. للقراءة فقط [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | يعيد قائمة بجميع أقسام الشرائح المعرفة في العرض التقديمي. للقراءة فقط [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | يعيد مجموعة علامات الحساسية المطبقة على مستند العرض التقديمي. للقراءة فقط [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | يعيد قائمة بجميع الشرائح المعرفة في العرض التقديمي. للقراءة فقط [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | يعيد كائن حجم الشريحة. للقراءة فقط [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | يعيد معلومات حول التنسيق الذي تم تحميل العرض التقديمي منه. للقراءة فقط [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | يحصل على مشروع VBA مع ماكروهات العرض التقديمي. للقراءة والكتابة [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | يعيد مجموعة جميع ملفات الفيديو المضمّنة في العرض التقديمي. للقراءة فقط [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | يحصل على خصائص عرض شاملة للعرض التقديمي. للقراءة فقط [`IViewProperties`](../iviewproperties). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | يعيد كائنات صورة مصغرة لجميع شرائح العرض التقديمي. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | يعيد كائنات Bitmap مصغرة للشرائح المحددة في العرض التقديمي. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | يعيد كائنات صورة مصغرة لجميع شرائح العرض التقديمي بالحجم المحدد. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | يعيد كائنات صورة مصغرة لجميع شرائح العرض التقديمي مع تحجيم مخصص. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | يعيد كائنات صورة مصغرة للشرائح المحددة في العرض التقديمي بالحجم المحدد. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | يعيد كائنات صورة مصغرة للشرائح المحددة في العرض التقديمي مع تحجيم مخصص. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | يعيد Slide أو MasterSlide أو LayoutSlide حسب المعرّف. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | يبرز جميع التطابقات للتعبير النمطي باللون المحدد. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | يبرز جميع التطابقات للنص النموذجي باللون المحدد. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | يبرز جميع التطابقات للنص النموذجي باللون المحدد. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | يصغي المقاطع ذات التنسيق المتطابق في جميع الفقرات داخل جميع الأشكال القابلة للمعالجة في جميع الشرائح. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | يستبدل جميع التطابقات للتعبير النمطي بالسلسلة المحددة. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | يستبدل جميع ظهورات النص المحدد بنص آخر محدد. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | يحفظ جميع شرائح العرض التقديمي إلى مجموعة من الملفات التي تمثل ترميز XAML. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | يحفظ جميع شرائح العرض التقديمي إلى تدفق بالصيغة المحددة. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | يحفظ جميع شرائح العرض التقديمي إلى ملف بالصيغة المحددة. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصيغة المحددة. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | يحفظ جميع شرائح العرض التقديمي إلى تدفق بالصيغة المحددة مع خيارات إضافية. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصيغة المحددة. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | يحفظ جميع شرائح العرض التقديمي إلى ملف بالصيغة المحددة ومع خيارات إضافية. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصيغة المحددة. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصيغة المحددة. |

### انظر أيضًا

* interface [IPresentationComponent](../ipresentationcomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->