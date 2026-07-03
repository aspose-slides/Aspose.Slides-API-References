---
title: ISlideCollection
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل مجموعة من الشرائح.
type: docs
weight: 7050
url: /ar/aspose.slides/islidecollection/
---
## ISlideCollection واجهة

يمثل مجموعة من Slides.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | يحصل على العنصر في الفهرس المحدد. للقراءة فقط [`ISlide`](../islide). |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | يضيف نسخة من slide محدد إلى نهاية المجموعة. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | يضيف نسخة من slide محدد إلى نهاية المجموعة. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | يضيف نسخة من slide محدد إلى نهاية القسم المحدد. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | يضيف نسخة من slide المصدر المحدد إلى نهاية المجموعة. سيتم اختيار layout المناسب تلقائيًا من master المحدد (layout المناسب هو layout الذي له نفس Type أو Name كما في layout لslide المصدر). إذا لم يكن هناك layout مناسب فسيتم استنساخ layout لslide المصدر (إذا كان allowCloneMissingLayout true) أو سيتم إلقاء PptxEditException (إذا كان allowCloneMissingLayout false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | يضيف slide فارغ جديد إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة مع مراعاة pdf import options. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | يرجع فهرس slide المحدد في المجموعة. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | يدرج نسخة من slide محدد إلى الموقع المحدد في المجموعة. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | يدرج نسخة من slide محدد إلى الموقع المحدد في المجموعة. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | يدرج نسخة من slide المصدر المحدد إلى الموقع المحدد في المجموعة. سيتم اختيار layout المناسب تلقائيًا من master المحدد (layout المناسب هو layout الذي له نفس Type أو Name كما في layout لslide المصدر). إذا لم يكن هناك layout مناسب فسيتم استنساخ layout لslide المصدر (إذا كان allowCloneMissingLayout true) أو سيتم إلقاء PptxEditException (إذا كان allowCloneMissingLayout false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | يدرج نسخة من slide محدد إلى الموقع المحدد في المجموعة. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | ينشئ شرائح من نص HTML ويدرجها في المجموعة في الموقع المحدد. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | يزيل أول حدوث لكائن محدد من المجموعة. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | يزيل العنصر في الفهرس المحدد من المجموعة. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | ينقل slide من المجموعة إلى الموقع المحدد. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | ينقل الشرائح من المجموعة إلى الموقع المحدد. سيتم وضع الشرائح بدءًا من الفهرس وفقًا لترتيب ظهورها في القائمة. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | ينشئ ويرجع مصفوفة تحتوي على جميع الشرائح. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | ينشئ ويرجع مصفوفة تحتوي على جميع الشرائح من النطاق المحدد. |

### انظر أيضًا

* واجهة [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* واجهة [ISlide](../islide)
* نطاق [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->