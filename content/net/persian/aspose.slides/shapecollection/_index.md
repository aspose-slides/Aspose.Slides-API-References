---
title: ShapeCollection
second_title: Aspose.Sildes برای .NET مرجع API
description: یک مجموعه از اشکال را نمایان می‌کند.
type: docs
weight: 9860
url: /fa/aspose.slides/shapecollection/
---
## کلاس ShapeCollection

یک مجموعه از اشکال را نمایش می‌دهد.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | تعداد عناصر واقعاً موجود در مجموعه را برمی‌گرداند. فقط-خواندنی Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (ایمن برای رشته) است. فقط-خواندنی Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | عنصری را که در شاخص مشخص شده قرار دارد برمی‌گرداند. فقط-خواندنی [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | شیء شکل گروه والد برای مجموعه اشکال را برمی‌گرداند. فقط-خواندنی [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | یک ریشهٔ همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | یک قاب صوتی جدید مرتبط با یک مسیر سی‌دی ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | یک قاب صوتی جدید ایجاد می‌کند و با استفاده از یک شیء صدا موجود در فهرست Presentation.Audios، آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | یک قاب صوتی جدید با فایل WAV توکار ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. صوت توکار به مجموعه Presentation.Audios اضافه می‌شود. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | یک قاب صوتی جدید مرتبط با یک فایل صوتی خارجی ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | یک شکل خودکار جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | یک شکل خودکار جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید؛ به‌طور اختیاری با قالب‌بندی پیش‌فرض قالب اولیه مقداردهی اولیه می‌شود. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونهٔ سری و تنظیمات اولیه مقداردهی می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونهٔ سری و تنظیمات اولیه مقداردهی می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | یک نسخهٔ کپی از شکل مشخص شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. شکل کلون‌شده موقعیت و اندازهٔ اصلی را حفظ می‌کند. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | یک نسخهٔ کپی از شکل مشخص شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. شکل جدید عرض و ارتفاع *sourceShape* را حفظ می‌کند. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | یک نسخهٔ کپی از شکل مشخص شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | یک شکل اتصال‌دهنده جدید با استایل پیش‌فرض قالب ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | یک شکل اتصال‌دهنده جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید؛ به‌طور اختیاری استایل پیش‌فرض قالب اعمال می‌شود. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | یک شکل گروه خالی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. قاب گروه به‌صورت خودکار برای قرار گرفتن هر شکل اضافه‌شده تنظیم می‌شود. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | یک شکل گروه جدید ایجاد می‌کند، تصویر SVG مشخص شده را به شکل‌های منفرد تبدیل می‌نماید و گروه حاصل را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | یک شکل خودکار مستطیلی جدید برای محتوای ریاضی ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | یک قاب شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | یک قاب شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | یک قاب تصویر جدید شامل تصویر مشخص شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | یک قاب Section Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | یک قاب Section Zoom جدید با یک تصویر پیش‌فرض ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | یک نمودار SmartArt ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | یک قاب Summary Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | یک جدول جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | یک قاب ویدئویی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | یک قاب ویدئویی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | یک قاب Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | یک قاب Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. |
| [Clear](../../aspose.slides/shapecollection/clear)() | تمام اشکال را از مجموعهٔ اشکال حذف می‌کند. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | تمام عناصر مجموعه را در آرایه مشخص شده کپی می‌کند. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | یک شمارنده را برمی‌گرداند که از طریق مجموعه مرور می‌کند. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | اندیس صفر-پایهٔ اولین رخداد شکل مشخص شده در مجموعه را برمی‌گرداند. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | یک قاب صوتی جدید مرتبط با یک مسیر سی‌دی ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | یک قاب صوتی جدید ایجاد می‌کند و با استفاده از شیء صدا موجود در فهرست Presentation.Audios، آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | یک قاب صوتی جدید با فایل WAV توکار ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. صوت توکار به مجموعه Presentation.Audios اضافه می‌شود. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | یک قاب صوتی جدید مرتبط با یک فایل صوتی خارجی ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | یک شکل خودکار جدید ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید، با اعمال قالب‌بندی پیش‌فرض قالب. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | یک شکل خودکار جدید ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید؛ به‌طور اختیاری با استایل پیش‌فرض قالب مقداردهی اولیه می‌شود. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونهٔ سری و تنظیمات مقداردهی می‌کند و در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونهٔ سری و تنظیمات مقداردهی می‌کند و در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | یک نسخهٔ کپی از شکل مشخص شده ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. شکل کلون‌شده موقعیت و اندازهٔ اصلی را حفظ می‌کند. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | یک نسخهٔ کپی از شکل مشخص شده ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. شکل جدید عرض و ارتفاع *sourceShape* را حفظ می‌کند. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | یک نسخهٔ کپی از شکل مشخص شده ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | یک شکل اتصال‌دهنده جدید ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید، با اعمال استایل پیش‌فرض قالب. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | یک شکل اتصال‌دهنده جدید ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید؛ به‌طور اختیاری استایل پیش‌فرض قالب اعمال می‌شود. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | یک شکل گروه خالی جدید ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. قاب گروه به‌صورت خودکار برای قرار گرفتن هر شکل اضافه‌شده تنظیم می‌شود. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | یک قاب شیء OLE جدید ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | یک قاب شیء OLE جدید ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | یک قاب تصویر جدید شامل تصویر مشخص شده ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | یک قاب Section Zoom جدید ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | یک قاب Section Zoom جدید با یک تصویر پیش‌فرض ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | یک قاب Summary Zoom جدید ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | یک جدول جدید ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | یک قاب ویدئویی جدید ایجاد می‌نماید و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | یک قاب Zoom جدید ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | یک قاب Zoom جدید با یک تصویر پیش‌فرض ایجاد می‌کند و آن را در شاخص مشخص شده در مجموعهٔ اشکال وارد می‌نماید. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | اولین رخداد شکل مشخص شده را از مجموعهٔ اشکال حذف می‌کند. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | شکل موجود در شاخص مشخص شده را از مجموعهٔ اشکال حذف می‌کند. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | شکل مشخص شده را به موقعیت جدیدی درون مجموعهٔ اشکال منتقل می‌کند. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | اشکال مشخص شده را در مجموعهٔ اشکال جابه‌جا می‌کند و از شاخص داده شده آغاز می‌کند. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | یک آرایه حاوی تمام اشکال را ایجاد و برمی‌گرداند. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | یک آرایه حاوی تمام اشکال در بازهٔ مشخص‌شده ایجاد و برمی‌گرداند. |

### موارد مرتبط

* کلاس [DomObject&lt;TParent&gt;](../domobject-1)
* کلاس [GroupShape](../groupshape)
* رابط [IShapeCollection](../ishapecollection)
* فضای نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->