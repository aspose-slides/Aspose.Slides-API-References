---
title: IShapeCollection
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایانگر مجموعه‌ای از اشکال است.
type: docs
weight: 6980
url: /fa/aspose.slides/ishapecollection/
---
## رابط IShapeCollection

نمایانگر مجموعه‌ای از اشکال است.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## خواص

| نام | توضیح |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | عنصری را که در شاخص مشخص شده قرار دارد، بر می‌گرداند. فقط-خواندنی [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | شیء گروه اشکال والد برای مجموعه اشکال را بر می‌گرداند. فقط-خواندنی [`IGroupShape`](../igroupshape). |

## متدها

| نام | توضیح |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | یک قاب صوتی جدید که به تراک CD لینک شده است ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | یک قاب صوتی جدید ایجاد می‌کند و با استفاده از شیء صوتی موجود در فهرست Presentation.Audios، آن را به انتهای مجموعه اشکال اضافه می‌نماید. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | یک قاب صوتی جدید با فایل WAV جاسازی‌شده ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. صداهای جاسازی‌شده به مجموعه Presentation.Audios افزوده می‌شوند. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | یک قاب صوتی جدید که به فایل صوتی خارجی لینک شده است ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | یک شکل خودکار جدید با فرمت پیش‌فرض ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | یک شکل خودکار جدید ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند؛ در صورت تمایل قالب پیش‌فرض قالب‌بندی اعمال می‌شود. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه اولیه مقداردهی می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه اولیه مقداردهی می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید؛ در صورت تمایل قالب پیش‌فرض نیز اعمال می‌شود. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | یک کپی از شکل مشخص‌شده ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. شکل کلون‌ شده موقعیت و اندازهٔ اصلی را حفظ می‌کند. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | یک کپی از شکل مشخص‌شده ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. شکل جدید عرض و ارتفاع *sourceShape* را به‌دست می‌آورد. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | یک کپی از شکل مشخص‌شده ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | یک شکل‌اتصال جدید با استایل قالب پیش‌فرض ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | یک شکل‌اتصال جدید ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند؛ در صورت تمایل استایل قالب پیش‌فرض اعمال می‌شود. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | یک گروه شیء خالی جدید ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. چارچوب گروه به‌صورت خودکار برای پذیرش هر شکل افزوده‌شده تنظیم می‌شود. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | یک گروه شیء جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به اشکال جداگانه تبدیل می‌کند و گروه حاصل را به انتهای مجموعه اشکال اضافه می‌نماید. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | یک شکل مستطیلی خودکار جدید برای محتوای ریاضی ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | یک قاب شیء OLE جدید ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | یک قاب شیء OLE جدید ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | یک قاب تصویر جدید که شامل تصویر مشخص‌شده است ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | یک قاب Section Zoom جدید ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | یک قاب Section Zoom جدید با تصویر پیش‌فرض ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | یک نمودار SmartArt جدید ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | یک قاب Summary Zoom جدید ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | یک جدول جدید ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | یک قاب ویدئویی جدید ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | یک قاب ویدئویی جدید ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | یک قاب Zoom جدید ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | یک قاب Zoom جدید با تصویر پیش‌فرض ایجاد کرده و به انتهای مجموعه اشکال اضافه می‌کند. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | تمام اشکال را از مجموعه اشکال حذف می‌کند. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | اندیس صفر-محور اولین رخداد شکل مشخص‌شده را در مجموعه باز می‌گرداند. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | یک قاب صوتی جدید که به تراک CD لینک شده است ایجاد می‌کند و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌سازد. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | یک قاب صوتی جدید ایجاد می‌کند و با استفاده از شیء صوتی موجود در فهرست Presentation.Audios، آن را در اندیس مشخص‌شده به مجموعه اشکال وارد می‌سازد. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | یک قاب صوتی جدید با فایل WAV جاسازی‌شده ایجاد می‌کند و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌سازد. صداهای جاسازی‌شده به مجموعه Presentation.Audios افزوده می‌شوند. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | یک قاب صوتی جدید که به فایل صوتی خارجی لینک شده است ایجاد می‌کند و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌سازد. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | یک شکل خودکار جدید ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند؛ قالب پیش‌فرض اعمال می‌شود. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | یک شکل خودکار جدید ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند؛ در صورت تمایل استایل قالب پیش‌فرض اعمال می‌شود. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه اولیه مقداردهی می‌کند و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌سازد. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه اولیه مقداردهی می‌کند و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند؛ در صورت تمایل قالب پیش‌فرض نیز اعمال می‌شود. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | یک کپی از شکل مشخص‌شده ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند. شکل کلون‌ شده موقعیت و اندازهٔ اصلی را حفظ می‌کند. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | یک کپی از شکل مشخص‌شده ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند؛ شکل جدید عرض و ارتفاع *sourceShape* را حفظ می‌کند. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | یک کپی از شکل مشخص‌شده ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | یک شکل اتصال جدید ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند؛ استایل قالب پیش‌فرض اعمال می‌شود. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | یک شکل اتصال جدید ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند؛ در صورت تمایل استایل قالب پیش‌فرض اعمال می‌شود. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | یک گروه شیء خالی جدید ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند. چارچوب گروه به‌صورت خودکار برای پذیرش هر شکل افزوده‌شده تنظیم می‌شود. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | یک قاب شیء OLE جدید ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | یک قاب شیء OLE جدید ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | یک قاب تصویر جدید که شامل تصویر مشخص‌شده است ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | یک قاب Section Zoom جدید ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | یک قاب Section Zoom جدید با تصویر پیش‌فرض ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | یک قاب Summary Zoom جدید ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | یک جدول جدید ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | یک قاب ویدئویی جدید ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال اضافه می‌کند. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | یک قاب Zoom جدید ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | یک قاب Zoom جدید با تصویر پیش‌فرض ایجاد کرده و در اندیس مشخص‌شده به مجموعه اشکال وارد می‌کند. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | اولین رخداد شکل مشخص‌شده را از مجموعه اشکال حذف می‌کند. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | شکلی را که در اندیس مشخص‌شده قرار دارد از مجموعه اشکال حذف می‌کند. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | شکل مشخص‌شده را به موقعیتی جدید درون مجموعه اشکال منتقل می‌کند. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | شکل‌های مشخص‌شده را در مجموعه اشکال جابه‌جا می‌کند؛ آن‌ها را از اندیس داده‌شده شروع می‌کند. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | آرایه‌ای شامل تمام اشکال ایجاد و بر می‌گرداند. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | آرایه‌ای شامل تمام اشکال در بازهٔ مشخص‌شده ایجاد و بر می‌گرداند. |

### مراجع

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [IShape](../ishape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->