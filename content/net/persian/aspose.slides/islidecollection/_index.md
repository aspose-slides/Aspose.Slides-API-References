---
title: ISlideCollection
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر مجموعه‌ای از اسلایدها است.
type: docs
weight: 7050
url: /fa/aspose.slides/islidecollection/
---
## ISlideCollection رابط

نمایانگر مجموعه‌ای از اسلایدها است.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | عنصری را در ایندکس مشخص دریافت می‌کند. فقط خواندنی [`ISlide`](../islide). |

## متدها

| نام | توضیح |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | یک نسخه از اسلاید مشخص شده را به انتهای مجموعه اضافه می‌کند. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | یک نسخه از اسلاید مشخص شده را به انتهای مجموعه اضافه می‌کند. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | یک نسخه از اسلاید مشخص شده را به انتهای بخش مشخص شده اضافه می‌کند. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | یک نسخه از اسلاید منبع مشخص شده را به انتهای مجموعه اضافه می‌کند. طرح مناسب به‌صورت خودکار از مستر مشخص‌شده انتخاب می‌شود (طرح مناسب، طرحی است که دارای همان Type یا Name مشابه طرح اسلاید منبع باشد). اگر طرح مناسب وجود نداشته باشد، طرح اسلاید منبع کپی می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | یک اسلاید خالی جدید را به انتهای مجموعه اضافه می‌کند. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | اسلایدهایی را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌سازد. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | اسلایدهایی را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌سازد. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | اسلایدهایی را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌سازد. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | اسلایدهایی را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌سازد. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | اسلایدهایی را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌سازد. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | اسلایدهایی را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌سازد. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | اسلایدهایی را از سند PDF ایجاد می‌کند و به انتهای مجموعه اضافه می‌سازد. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | اسلایدهایی را از سند PDF ایجاد می‌کند و به انتهای مجموعه اضافه می‌سازد. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | اسلایدهایی را از سند PDF ایجاد می‌کند و با توجه به PdfImportOptions به انتهای مجموعه اضافه می‌سازد. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | اسلایدهایی را از سند PDF ایجاد می‌کند و با توجه به گزینه‌های PdfImportOptions به انتهای مجموعه اضافه می‌کند. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | اندیس اسلاید مشخص شده در مجموعه را برمی‌گرداند. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | یک نسخه از اسلاید مشخص شده را در موقعیت مشخص‌شده در مجموعه درج می‌کند. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | یک نسخه از اسلاید مشخص شده را در موقعیت مشخص‌شده در مجموعه درج می‌کند. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | یک نسخه از اسلاید منبع مشخص شده را در موقعیت مشخص‌شده در مجموعه درج می‌کند. طرح مناسب به‌صورت خودکار از مستر مشخص‌شده انتخاب می‌شود (طرح مناسب، طرحی است که دارای همان Type یا Name مشابه طرح اسلاید منبع باشد). اگر طرح مناسبی موجود نباشد، طرح اسلاید منبع کپی می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | یک نسخه از اسلاید مشخص شده را در موقعیت مشخص‌شده در مجموعه درج می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | اسلایدهایی را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | اسلایدهایی را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | اسلایدهایی را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | اسلایدهایی را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | اسلایدهایی را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | اسلایدهایی را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | اسلایدهایی را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | اسلایدهایی را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | اسلایدهایی را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | اسلایدهایی را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه اضافه می‌کند. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | اولین رخداد شیء مشخص شده را از مجموعه حذف می‌کند. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | عنصر موجود در ایندکس مشخص‌شده در مجموعه را حذف می‌کند. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | اسلاید را از مجموعه به موقعیت مشخص‌شده جابجا می‌کند. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | اسلایدها را از مجموعه به موقعیت مشخص‌شده جابجا می‌کند. اسلایدها از ایندکس شروع شده و به ترتیبی که در لیست ظاهر می‌شوند قرار می‌گیرند. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | یک آرایه شامل تمام اسلایدها ایجاد کرده و برمی‌گرداند. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | یک آرایه شامل تمام اسلایدها از بازه مشخص‌شده ایجاد کرده و برمی‌گرداند. |

### موارد مرتبط

* رابط [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* رابط [ISlide](../islide)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->