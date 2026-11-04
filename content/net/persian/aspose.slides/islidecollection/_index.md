---
title: ISlideCollection
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایش‌دهنده یک مجموعه از اسلایدها.
type: docs
weight: 7070
url: /fa/aspose.slides/islidecollection/
---
## ISlideCollection رابط

نمایش‌دهنده یک مجموعه از اسلایدها.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | عنصری را که در اندیس مشخص شده قرار دارد برمی‌گرداند. فقط-قابل-خواندن [`ISlide`](../islide). |

## متدها

| نام | توضیح |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | یک کپی از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | یک کپی از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | یک کپی از اسلاید مشخص‌شده را به انتهای بخش تعیین‌شده اضافه می‌کند. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | یک کپی از اسلاید منبع مشخص‌شده را به انتهای مجموعه اضافه می‌کند. طرح‌بندی مناسب به‌صورت خودکار از مستر مشخص‌شده انتخاب می‌شود (طرح‌بندی مناسب، طرح‌بندی‌ای است که نوع یا نام آن با طرح‌بندی اسلاید منبع یکسان باشد). اگر طرح‌بندی مناسبی موجود نباشد، طرح‌بندی اسلاید منبع کپی می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | یک اسلاید خالی جدید را به انتهای مجموعه اضافه می‌کند. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | اسلایدها را از سند PDF ایجاد کرده و با در نظر گرفتن گزینه‌های وارد کردن PDF به انتهای مجموعه اضافه می‌کند. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | یک اندیس از اسلاید مشخص‌شده در مجموعه را برمی‌گرداند. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | یک کپی از اسلاید مشخص‌شده را در موقعیت تعیین‌شده از مجموعه درج می‌کند. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | یک کپی از اسلاید مشخص‌شده را در موقعیت تعیین‌شده از مجموعه درج می‌کند. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | یک کپی از اسلاید منبع مشخص‌شده را در موقعیت تعیین‌شده از مجموعه درج می‌کند. طرح‌بندی مناسب به‌صورت خودکار از مستر مشخص‌شده انتخاب می‌شود (طرح‌بندی مناسب، طرح‌بندی‌ای است که نوع یا نام آن با طرح‌بندی اسلاید منبع یکسان باشد). اگر طرح‌بندی مناسبی موجود نباشد، طرح‌بندی اسلاید منبع کپی می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | یک کپی از اسلاید مشخص‌شده را در موقعیت تعیین‌شده از مجموعه درج می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت تعیین‌شده به مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت تعیین‌شده به مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت تعیین‌شده به مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت تعیین‌شده به مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت تعیین‌شده به مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت تعیین‌شده به مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت تعیین‌شده به مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت تعیین‌شده به مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت تعیین‌شده به مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | اسلایدها را از متن HTML ایجاد کرده و در موقعیت تعیین‌شده به مجموعه وارد می‌کند. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | عنصر موجود در اندیس مشخص‌شده از مجموعه را حذف می‌کند. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | اسلاید را از مجموعه به موقعیت تعیین‌شده منتقل می‌کند. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | اسلایدها را از مجموعه به موقعیت تعیین‌شده منتقل می‌کند. اسلایدها از اندیس شروع شده به ترتیب ظاهر شدن در لیست قرار خواهند گرفت. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | یک آرایه شامل تمام اسلایدها ایجاد کرده و برمی‌گرداند. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | یک آرایه شامل تمام اسلایدهای بازه مشخص‌شده ایجاد کرده و برمی‌گرداند. |

### همچنین ببینید

* رابط [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* رابط [ISlide](../islide)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->