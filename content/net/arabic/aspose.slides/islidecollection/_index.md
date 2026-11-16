---
title: ISlideCollection
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل مجموعة من الشرائح.
type: docs
weight: 7070
url: /ar/aspose.slides/islidecollection/
---
## ISlideCollection واجهة

يمثل مجموعة من الشرائح.

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
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | يضيف نسخة من شريحة محددة إلى نهاية المجموعة. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | يضيف نسخة من شريحة محددة إلى نهاية المجموعة. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | يضيف نسخة من شريحة محددة إلى نهاية القسم المحدد. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | يضيف نسخة من شريحة المصدر المحددة إلى نهاية المجموعة. سيتم اختيار التخطيط المناسب تلقائيًا من القالب المحدد (التخطيط المناسب هو التخطيط الذي يمتلك نفس النوع أو الاسم كالتخطيط الخاص بالشريحة المصدر). إذا لم يتوفر تخطيط مناسب، سيتم استنساخ تخطيط الشريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو ستُطرح استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | يضيف شريحة فارغة جديدة إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة مع مراعاة خيارات استيراد PDF. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | يعيد فهرس الشريحة المحددة في المجموعة. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | يدرج نسخة من شريحة محددة في الموضع المحدد في المجموعة. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | يدرج نسخة من شريحة محددة في الموضع المحدد في المجموعة. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | يدرج نسخة من شريحة المصدر المحددة في الموضع المحدد في المجموعة. سيتم اختيار التخطيط المناسب تلقائيًا من القالب المحدد (التخطيط المناسب هو التخطيط الذي يمتلك نفس النوع أو الاسم كالتخطيط الخاص بالشريحة المصدر). إذا لم يتوفر تخطيط مناسب، سيتم استنساخ تخطيط الشريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو ستُطرح استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | يدرج نسخة من شريحة محددة في الموضع المحدد في المجموعة. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | ينشئ شرائح من نص HTML ويدرجها في المجموعة عند الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | ينشئ شرائح من نص HTML ويدرجها في المجموعة عند الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | ينشئ شرائح من نص HTML ويدرجها في المجموعة عند الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | ينشئ شرائح من نص HTML ويدرجها في المجموعة عند الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | ينشئ شرائح من نص HTML ويدرجها في المجموعة عند الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويدرجها في المجموعة عند الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويدرجها في المجموعة عند الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | ينشئ شرائح من نص HTML ويدرجها في المجموعة عند الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | ينشئ شرائح من نص HTML ويدرجها في المجموعة عند الموضع المحدد. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | ينشئ شرائح من نص HTML ويدرجها في المجموعة عند الموضع المحدد. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | يزيل أول حدوث لكائن محدد من المجموعة. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | يزيل العنصر عند الفهرس المحدد في المجموعة. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | ينقل الشريحة من المجموعة إلى الموضع المحدد. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | ينقل الشرائح من المجموعة إلى الموضع المحدد. ستوضع الشرائح بدءًا من الفهرس وفقًا للترتيب الذي تظهر به في القائمة. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | ينشئ ويعيد مصفوفة تحتوي على جميع الشرائح من النطاق المحدد. |

### انظر أيضًا

* واجهة [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* واجهة [ISlide](../islide)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->