---
title: SlideCollection
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر مجموعه‌ای از اسلایدها است.
type: docs
weight: 9970
url: /fa/aspose.slides/slidecollection/
---
## کلاس SlideCollection

نمایانگر یک مجموعه از اسلایدها.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | تعداد عناصری که واقعاً در مجموعه موجود است را برمی‌گرداند. فقط خواندنی Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (امن برای چندنخی). فقط خواندنی Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | عنصر موجود در اندیس مشخص شده را برمی‌گرداند. فقط خواندنی [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | ریشه‌ی همگام‌سازی را برمی‌گرداند. فقط خواندنی Object. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | یک نسخه از اسلاید مشخص شده را به انتهای مجموعه اضافه می‌کند. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | یک نسخه از اسلاید مشخص شده را به انتهای مجموعه اضافه می‌کند. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | یک نسخه از اسلاید مشخص شده را به انتهای بخش مشخص‌شده اضافه می‌کند. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | یک نسخه از اسلاید منبع مشخص را به انتهای مجموعه اضافه می‌کند. طرح مناسب به‌طور خودکار از مستر مشخص شده انتخاب می‌شود (طرح مناسب همان طرحی است که Type یا Name آن با طرح اسلاید منبع یکسان باشد). اگر طرح مناسب وجود نداشته باشد، طرح اسلاید منبع کلون خواهد شد (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | یک اسلاید خالی جدید به انتهای مجموعه اضافه می‌کند. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | اسلایدها را از سند PDF ایجاد کرده و با در نظر گرفتن گزینه‌های PdfImportOptions به انتهای مجموعه اضافه می‌کند. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | تمام عناصر مجموعه را به آرایه مشخص‌شده کپی می‌کند. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | یک Enumerator که در مجموعه تکرار می‌کند را برمی‌گرداند. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | اندیس اسلاید مشخص‌شده در مجموعه را برمی‌گرداند. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | یک نسخه از اسلاید مشخص‌شده را در موقعیت مشخص شده در مجموعه درج می‌کند. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | یک نسخه از اسلاید مشخص‌شده را در موقعیت مشخص شده در مجموعه درج می‌کند. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | یک نسخه از اسلاید منبع مشخص شده را در موقعیت مشخص شده در مجموعه درج می‌کند. طرح مناسب به‌طور خودکار از مستر مشخص شده انتخاب می‌شود (طرح مناسب همان طرحی است که Type یا Name آن با طرح اسلاید منبع یکسان باشد). اگر طرح مناسب وجود نداشته باشد، طرح اسلاید منبع کلون خواهد شد (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | یک نسخه از اسلاید مشخص‌شده را در موقعیت مشخص شده در مجموعه درج می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده در مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده در مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده در مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده در مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده در مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده در مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده در مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده در مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده در مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده در مجموعه وارد می‌کند. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | اولین رخداد شیء خاص را از مجموعه حذف می‌کند. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | عنصر موجود در اندیس مشخص‌شده را از مجموعه حذف می‌کند. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | اسلاید را از مجموعه به موقعیت مشخص‌شده منتقل می‌کند. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | اسلایدها را از مجموعه به موقعیت مشخص‌شده منتقل می‌کند. اسلایدها از اندیس شروع شده به ترتیب ظاهر شدن در لیست قرار می‌گیرند. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | یک آرایه حاوی تمام اسلایدها ایجاد کرده و برمی‌گرداند. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | یک آرایه حاوی تمام اسلایدهای بازه مشخص‌شده ایجاد کرده و برمی‌گرداند. اندیس اولین اسلاید برای اضافه کردن و تعداد اسلایدهای مورد افزودن. |

### موارد مرتبط

* کلاس [DomObject&lt;TParent&gt;](../domobject-1)
* کلاس [Presentation](../presentation)
* رابط [ISlideCollection](../islidecollection)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->