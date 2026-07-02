---
title: SlideCollection
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر مجموعه‌ای از اسلایدها است.
type: docs
weight: 9970
url: /fa/aspose.slides/slidecollection/
---
## کلاس SlideCollection

Represents a collection of a slides.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | تعداد عناصری که واقعاً در collection موجود است را برمی‌گرداند. فقط خواندنی Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به collection همگام‌سازی شده است (thread-safe). فقط خواندنی Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | عنصر موجود در ایندکس مشخص شده را برمی‌گرداند. فقط خواندنی [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | ریشه همگام‌سازی را برمی‌گرداند. فقط خواندنی Object. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | یک کپی از اسلاید مشخص شده را به انتهای collection اضافه می‌کند. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | یک کپی از اسلاید مشخص شده را به انتهای collection اضافه می‌کند. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | یک کپی از اسلاید مشخص شده را به انتهای بخش مشخص شده اضافه می‌کند. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | یک کپی از اسلاید منبع مشخص شده را به انتهای collection اضافه می‌کند. طرح مناسب به‌صورت خودکار از master مشخص شده انتخاب می‌شود (طرح مناسب همان طرحی است که Type یا Name مشابه طرح اسلاید منبع دارد). اگر طرح مناسب وجود نداشته باشد، طرح اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | یک اسلاید خالی جدید را به انتهای collection اضافه می‌کند. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | اسلایدها را از متن HTML ایجاد می‌کند و به انتهای collection اضافه می‌نماید. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | اسلایدها را از متن HTML ایجاد می‌کند و به انتهای collection اضافه می‌نماید. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | اسلایدها را از متن HTML ایجاد می‌کند و به انتهای collection اضافه می‌نماید. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد می‌کند و به انتهای collection اضافه می‌نماید. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد می‌کند و به انتهای collection اضافه می‌نماید. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد می‌کند و به انتهای collection اضافه می‌نماید. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | اسلایدها را از سند PDF ایجاد می‌کند و به انتهای collection اضافه می‌نماید. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | اسلایدها را از سند PDF ایجاد می‌کند و به انتهای collection اضافه می‌نماید. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | اسلایدها را از سند PDF ایجاد می‌کند و به انتهای collection اضافه می‌نماید. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | اسلایدها را از سند PDF ایجاد می‌کند و با در نظر گرفتن PdfImportOptions به انتهای collection اضافه می‌کند. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | تمام عناصر collection را به آرایه مشخص شده کپی می‌کند. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | یک enumerator که از طریق collection پیمایش می‌کند را برمی‌گرداند. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | اندیس اسلاید مشخص شده در collection را برمی‌گرداند. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | یک کپی از اسلاید مشخص شده را در موقعیت مشخص شده داخل collection وارد می‌کند. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | یک کپی از اسلاید مشخص شده را در موقعیت مشخص شده داخل collection وارد می‌کند. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | یک کپی از اسلاید منبع مشخص شده را در موقعیت مشخص شده داخل collection وارد می‌کند. طرح مناسب به‌صورت خودکار از master مشخص شده انتخاب می‌شود (طرح مناسب همان طرحی است که Type یا Name مشابه طرح اسلاید منبع دارد). اگر طرح مناسب وجود نداشته باشد، طرح اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | یک کپی از اسلاید مشخص شده را در موقعیت مشخص شده داخل collection وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص شده داخل collection وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص شده داخل collection وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص شده داخل collection وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص شده داخل collection وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص شده داخل collection وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص شده داخل collection وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص شده داخل collection وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص شده داخل collection وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص شده داخل collection وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص شده داخل collection وارد می‌نماید. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | اولین رخداد یک شیء خاص را از collection حذف می‌کند. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | عنصر موجود در ایندکس مشخص شده از collection را حذف می‌کند. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | اسلاید را از collection به موقعیت مشخص شده جابجا می‌کند. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | اسلایدها را از collection به موقعیت مشخص شده جابجا می‌کند. اسلایدها از ایندکس شروع می‌شوند به ترتیب ظاهر شدن در لیست. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | یک آرایه شامل تمام اسلایدها را ایجاد و برمی‌گرداند. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | یک آرایه شامل تمام اسلایدهای بازه مشخص شده را ایجاد و برمی‌گرداند. ایندکس اولین اسلاید برای افزودن. تعداد اسلایدهای برای افزودن. |

### موارد مرتبط

* کلاس [DomObject&lt;TParent&gt;](../domobject-1)
* کلاس [Presentation](../presentation)
* اینترفیس [ISlideCollection](../islidecollection)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->