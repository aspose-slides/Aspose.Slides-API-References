---
title: ISlideCollection
second_title: مرجع API Aspose.Sildes برای .NET
description: یک مجموعه از اسلایدها را نشان می‌دهد.
type: docs
weight: 7050
url: /fa/aspose.slides/islidecollection/
---
## ISlideCollection رابط

یک مجموعه از اسلایدها را نشان می‌دهد.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | عنصر را در شاخص مشخص دریافت می‌کند. فقط-خواندنی [`ISlide`](../islide). |

## متدها

| نام | توضیح |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | یک کپی از اسلاید مشخص شده را به انتهای مجموعه اضافه می‌کند. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | یک کپی از اسلاید مشخص شده را به انتهای مجموعه اضافه می‌کند. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | یک کپی از اسلاید مشخص شده را به انتهای بخش مشخص شده اضافه می‌کند. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | یک کپی از اسلاید منبع مشخص شده را به انتهای مجموعه اضافه می‌کند. چیدمان مناسب به‌صورت خودکار از مستر مشخص شده انتخاب می‌شود (چیدمان مناسب همان چیدمانی است که Type یا Name آن مشابه چیدمان اسلاید منبع باشد). اگر چیدمان مناسبی وجود نداشته باشد، چیدمان اسلاید منبع کپی می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException صادر می‌شود (اگر allowCloneMissingLayout برابر false باشد). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | یک اسلاید خالی جدید را به انتهای مجموعه اضافه می‌کند. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | اسلایدها را از سند PDF ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | اسلایدها را از سند PDF ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | اسلایدها را از سند PDF ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | اسلایدها را از سند PDF ایجاد می‌کند و با در نظر گرفتن گزینه‌های PdfImportOptions به انتهای مجموعه اضافه می‌نماید. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | شاخص اسلاید مشخص‌شده در مجموعه را برمی‌گرداند. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | یک کپی از اسلاید مشخص‌شده را در موقعیت مشخص شده در مجموعه وارد می‌کند. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | یک کپی از اسلاید مشخص‌شده را در موقعیت مشخص شده در مجموعه وارد می‌کند. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | یک کپی از اسلاید منبع مشخص‌شده را در موقعیت مشخص شده در مجموعه وارد می‌کند. چیدمان مناسب به‌صورت خودکار از مستر مشخص شده انتخاب می‌شود (چیدمان مناسب همان چیدمانی است که Type یا Name آن مشابه چیدمان اسلاید منبع باشد). اگر چیدمان مناسبی وجود نداشته باشد، چیدمان اسلاید منبع کپی می‌شود (اگر allowCloneMissingLayout برابر true باشد) یا PptxEditException صادر می‌شود (اگر allowCloneMissingLayout برابر false باشد). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | یک کپی از اسلاید مشخص‌شده را در موقعیت مشخص شده در مجموعه وارد می‌کند. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌نماید. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص‌شده به مجموعه وارد می‌نماید. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | اولین رخداد شیء مشخص‌شده را از مجموعه حذف می‌کند. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | عنصر در شاخص مشخص‌شده از مجموعه را حذف می‌کند. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | اسلاید را از مجموعه به موقعیت مشخص‌شده منتقل می‌کند. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | اسلایدها را از مجموعه به موقعیت مشخص‌شده منتقل می‌کند. اسلایدها از شاخص شروع شده به ترتیب ظهور در فهرست قرار می‌گیرند. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | یک آرایه شامل تمام اسلایدها ایجاد و برمی‌گرداند. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | یک آرایه شامل تمام اسلایدهای بازه‌ی مشخص‌شده ایجاد و برمی‌گرداند. |

### مراجع

* رابط [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* رابط [ISlide](../islide)
* فضای نام [Aspose.Slides](../../aspose.slides)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->