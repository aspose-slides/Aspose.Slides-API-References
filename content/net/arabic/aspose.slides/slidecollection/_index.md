---
title: SlideCollection
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل مجموعة من الشرائح.
type: docs
weight: 9970
url: /ar/aspose.slides/slidecollection/
---
## فئة SlideCollection

يمثل مجموعة من الشرائح.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | يحصل على عدد العناصر الفعلية الموجودة في المجموعة. Int32 للقراءة فقط. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). Boolean للقراءة فقط. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | يحصل على العنصر في الفهرس المحدد. [`Slide`](../slide) للقراءة فقط. |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | يعيد جذر التزامن. Object للقراءة فقط. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | يضيف نسخة من شريحة محددة إلى نهاية المجموعة. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | يضيف نسخة من شريحة محددة إلى نهاية المجموعة. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | يضيف نسخة من شريحة محددة إلى نهاية القسم المحدد. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | يضيف نسخة من شريحة مصدر محددة إلى نهاية المجموعة. سيتم اختيار التخطيط المناسب تلقائيًا من القالب المحدد (التخطيط المناسب هو التخطيط الذي يحمل نفس النوع أو الاسم مثل تخطيط الشريحة المصدر). إذا لم يكن هناك تخطيط مناسب فسيتم استنساخ تخطيط الشريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم إلقاء استثناء PptxEditException (إذا كان allowCloneMissingLayout غير صحيح). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | يضيف شريحة فارغة جديدة إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة مع مراعاة خيارات استيراد PDF. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | يعيد مُعددًا يتنقل عبر المجموعة. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | يعيد فهرس الشريحة المحددة في المجموعة. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | يدرج نسخة من شريحة محددة في الموضع المحدد في المجموعة. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | يدرج نسخة من شريحة محددة في الموضع المحدد في المجموعة. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | يدرج نسخة من شريحة مصدر محددة في الموضع المحدد في المجموعة. سيتم اختيار التخطيط المناسب تلقائيًا من القالب المحدد (التخطيط المناسب هو التخطيط الذي يحمل نفس النوع أو الاسم مثل تخطيط الشريحة المصدر). إذا لم يكن هناك تخطيط مناسب فسيتم استنساخ تخطيط الشريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم إلقاء استثناء PptxEditException (إذا كان allowCloneMissingLayout غير صحيح). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | يدرج نسخة من شريحة محددة في الموضع المحدد في المجموعة. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | يزيل أول حدوث لكائن محدد من المجموعة. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | يزيل العنصر في الفهرس المحدد من المجموعة. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | ينقل الشريحة من المجموعة إلى الموضع المحدد. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | ينقل الشرائح من المجموعة إلى الموضع المحدد. سيتم وضع الشرائح بدءًا من الفهرس بالترتيب الذي تظهر به في القائمة. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح ضمن النطاق المحدد. فهرس أول شريحة للإضافة. عدد الشرائح المراد إضافتها. |

### انظر أيضًا

* فئة [DomObject&lt;TParent&gt;](../domobject-1)
* فئة [Presentation](../presentation)
* واجهة [ISlideCollection](../islidecollection)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->