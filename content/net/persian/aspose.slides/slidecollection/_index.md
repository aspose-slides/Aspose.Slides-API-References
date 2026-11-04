---
title: SlideCollection
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایش‌دهندهٔ مجموعه‌ای از اسلایدها.
type: docs
weight: 9990
url: /fa/aspose.slides/slidecollection/
---
## کلاس SlideCollection

نمایش دهندهٔ مجموعه‌ای از اسلایدها.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## ویژگی‌ها

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | تعداد عناصری که در واقع در مجموعه وجود دارد را برمی‌گرداند. فقط‌خواندنی Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (ایمن برای رشته). فقط‌خواندنی Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | عنصر موجود در شاخص مشخص‌شده را برمی‌گرداند. فقط‌خواندنی [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | ریشه همگام‌سازی را برمی‌گرداند. فقط‌خواندنی Object. |

## متدها

| Name | Description |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | یک نسخه کپی از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | یک نسخه کپی از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | یک نسخه کپی از اسلاید مشخص‌شده را به انتهای بخش مشخص‌شده اضافه می‌کند. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | یک نسخه کپی از اسلاید منبع مشخص‌شده را به انتهای مجموعه اضافه می‌کند. طرح مناسب به‌صورت خودکار از مستر مشخص‌شده انتخاب می‌شود (طرح مناسب همان طرحی است که نوع یا نامش با طرح اسلاید منبع برابر باشد). اگر طرح مناسبی وجود نداشته باشد، طرح اسلاید منبع کپی خواهد شد (اگر allowCloneMissingLayout برابر true باشد) یا استثنای PptxEditException رخ می‌دهد (اگر allowCloneMissingLayout برابر false باشد). |
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
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | اسلایدها را از سند PDF ایجاد کرده و با در نظر گرفتن گزینه‌های واردسازی PDF به انتهای مجموعه اضافه می‌کند. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | تمام عناصر را از مجموعه به آرایه مشخص‌شده کپی می‌کند. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | یک enumerator را برمی‌گرداند که از مجموعه عبور می‌کند. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | اندیس اسلاید مشخص‌شده در مجموعه را برمی‌گرداند. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | یک نسخه کپی از اسلاید مشخص‌شده را در موقعیت مشخص‌شده از مجموعه درج می‌کند. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | یک نسخه کپی از اسلاید مشخص‌شده را در موقعیت مشخص‌شده از مجموعه درج می‌کند. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | یک نسخه کپی از اسلاید منبع مشخص‌شده را در موقعیت مشخص‌شده از مجموعه درج می‌کند. طرح مناسب به‌صورت خودکار از مستر مشخص‌شده انتخاب می‌شود (طرح مناسب همان طرحی است که نوع یا نامش با طرح اسلاید منبع برابر باشد). اگر طرح مناسبی وجود نداشته باشد، طرح اسلاید منبع کپی خواهد شد (اگر allowCloneMissingLayout برابر true باشد) یا استثنای PptxEditException رخ می‌دهد (اگر allowCloneMissingLayout برابر false باشد). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | یک نسخه کپی از اسلاید مشخص‌شده را در موقعیت مشخص‌شده از مجموعه درج می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | عنصر موجود در شاخص مشخص‌شده از مجموعه را حذف می‌کند. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | اسلاید را از مجموعه به موقعیت مشخص‌شده جابه‌جا می‌کند. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | اسلایدها را از مجموعه به موقعیت مشخص‌شده جابه‌جا می‌کند. اسلایدها از اندیس شروع شده به ترتیب ظاهر شدن در لیست قرار می‌گیرند. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | یک آرایه شامل تمام اسلایدها ایجاد و برمی‌گرداند. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | یک آرایه شامل تمام اسلایدها از بازهٔ مشخص‌شده ایجاد و برمی‌گرداند. شاخص اولین اسلاید برای افزودن و تعداد اسلایدهای افزوده‌شده. |

### مراجع

* کلاس [DomObject&lt;TParent&gt;](../domobject-1)
* کلاس [Presentation](../presentation)
* رابط [ISlideCollection](../islidecollection)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->