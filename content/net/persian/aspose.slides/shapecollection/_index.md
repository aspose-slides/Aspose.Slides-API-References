---
title: ShapeCollection
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایش‌دهندهٔ مجموعه‌ای از اشکال.
type: docs
weight: 9860
url: /fa/aspose.slides/shapecollection/
---
## ShapeCollection کلاس

نمایش‌دهندهٔ مجموعه‌ای از اشکال.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | تعداد عناصری که واقعاً در مجموعه موجود هستند را دریافت می‌کند. فقط خواندنی Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده است (امنیت‌پذیر در برابر ریسه). فقط خواندنی Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | عنصر موجود در ایندکس مشخص‌شده را دریافت می‌کند. فقط خواندنی [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | شیء شکل گروه والد برای مجموعهٔ اشکال را دریافت می‌کند. فقط خواندنی [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | ریشهٔ همگام‌سازی را برمی‌گرداند. فقط خواندنی Object. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | یک قاب صوتی جدید که به یک تراک CD مرتبط است ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | یک قاب صوتی جدید ایجاد می‌کند و با استفاده از شیء صوتی موجود در فهرست Presentation.Audios آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | یک قاب صوتی جدید با فایل WAV توکار ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. صوت توکار به فهرست Presentation.Audios افزوده می‌شود. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | یک قاب صوتی جدید که به یک فایل صوتی خارجی مرتبط است ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | یک شکل خودکار جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | یک شکل خودکار جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند؛ در صورت نیاز با قالب‌بندی پیش‌فرض قالب را مقداردهی اولیه می‌کند. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری‌ها و تنظیمات اولیه مقداردهی می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری‌ها و تنظیمات اولیه مقداردهی می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. شکل کلون‌شده موقعیت و اندازهٔ اصل را حفظ می‌کند. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. شکل جدید عرض و ارتفاع *sourceShape* را حفظ می‌کند. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | یک شکل اتصال جدید با استایل قالب پیش‌فرض ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | یک شکل اتصال جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند؛ در صورت نیاز استایل قالب پیش‌فرض را اعمال می‌کند. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | یک گروه شکل خالی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. قاب گروه به‌صورت خودکار برای قرارگیری هر شکلی که به آن افزوده شود تنظیم می‌شود. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | یک گروه شکل جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به اشکال جداگانه تبدیل می‌کند و گروه حاصل را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | یک شکل خودکار مستطیلی برای میزبانی محتوای ریاضی ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | یک قاب شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | یک قاب شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | یک قاب تصویر جدید شامل تصویر مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | یک قاب Section Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | یک قاب Section Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | یک نمودار SmartArt جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | یک قاب Summary Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | یک جدول جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | یک قاب ویدئویی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | یک قاب ویدئویی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | یک قاب Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | یک قاب Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [Clear](../../aspose.slides/shapecollection/clear)() | تمام اشکال را از مجموعهٔ اشکال حذف می‌کند. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | تمام عناصر مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | یک شمارنده (enumerator) باز می‌گرداند که از طریق مجموعه پیمایش می‌کند. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | اندیس صفر-پایهٔ اولین رخداد شکل مشخص‌شده در مجموعه را برمی‌گرداند. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | یک قاب صوتی جدید که به یک تراک CD مرتبط است ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعهٔ اشکال وارد می‌کند. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | یک قاب صوتی جدید ایجاد می‌کند و با استفاده از شیء صوتی موجود در فهرست Presentation.Audios آن را در اندیس مشخص‌شده در مجموعهٔ اشکال وارد می‌کند. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | یک قاب صوتی جدید با فایل WAV توکار ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعهٔ اشکال وارد می‌کند. صوت توکار به فهرست Presentation.Audios افزوده می‌شود. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | یک قاب صوتی جدید که به یک فایل صوتی خارجی مرتبط است ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعهٔ اشکال وارد می‌کند. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | یک شکل خودکار جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعهٔ اشکال وارد می‌کند؛ قالب‌بندی پیش‌فرض قالب اعمال می‌شود. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | یک شکل خودکار جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعهٔ اشکال وارد می‌کند؛ در صورت نیاز با قالب‌بندی پیش‌فرض قالب مقداردهی می‌شود. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری‌ها و تنظیمات اولیه مقداردهی می‌کند و در اندیس مشخص‌شده در مجموعهٔ اشکال وارد می‌کند. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری‌ها و تنظیمات اولیه مقداردهی می‌کند و در اندیس مشخص‌شده در مجموعهٔ اشکال وارد می‌کند. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعهٔ اشکال وارد می‌کند. شکل کلون‌شده موقعیت و اندازهٔ اصل را حفظ می‌کند. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعهٔ اشکال وارد می‌کند. شکل جدید عرض و ارتفاع *sourceShape* را حفظ می‌کند. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعهٔ اشکال وارد می‌کند. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | یک شکل اتصال جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعهٔ اشکال وارد می‌کند؛ قالب پیش‌فرض قالب اعمال می‌شود. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | یک شکل اتصال جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعهٔ اشکال وارد می‌کند؛ در صورت نیاز استایل قالب پیش‌فرض اعمال می‌شود. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | یک گروه شکل خالی جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده به مجموعهٔ اشکال اضافه می‌کند. قاب گروه به‌صورت خودکار برای قرارگیری هر شکلی که به آن افزوده شود تنظیم می‌شود. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | یک قاب شیء OLE جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعهٔ اشکال وارد می‌کند. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | یک قاب شیء OLE جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعهٔ اشکال وارد می‌کند. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | یک قاب تصویر جدید شامل تصویر مشخص‌شده ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعهٔ اشکال وارد می‌کند. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | یک قاب Section Zoom جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده به مجموعهٔ اشکال اضافه می‌کند. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | یک قاب Section Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در اندیس مشخص‌شده به مجموعهٔ اشکال اضافه می‌کند. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | یک قاب Summary Zoom جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده به مجموعهٔ اشکال اضافه می‌کند. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | یک جدول جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده به مجموعهٔ اشکال اضافه می‌کند. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | یک قاب ویدئویی جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده به مجموعهٔ اشکال اضافه می‌کند. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | یک قاب Zoom جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده به مجموعهٔ اشکال اضافه می‌کند. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | یک قاب Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در اندیس مشخص‌شده به مجموعهٔ اشکال اضافه می‌کند. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | اولین رخداد شکل مشخص‌شده را از مجموعهٔ اشکال حذف می‌کند. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | شکل موجود در اندیس مشخص‌شده را از مجموعهٔ اشکال حذف می‌کند. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | شکل مشخص‌شده را به موقعیت جدیدی داخل مجموعهٔ اشکال منتقل می‌کند. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | شکل‌های مشخص‌شده را داخل مجموعهٔ اشکال جابه‌جا می‌کند و آن‌ها را از ایندکس تعیین‌شده شروع می‌کند. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | یک آرایه حاوی تمام اشکال ایجاد و برمی‌گرداند. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | یک آرایه شامل تمام اشکال در بازهٔ مشخص‌شده ایجاد و برمی‌گرداند. |

### موارد مرتبط

* کلاس [DomObject&lt;TParent&gt;](../domobject-1)
* کلاس [GroupShape](../groupshape)
* رابط [IShapeCollection](../ishapecollection)
* فضای‌نامی [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->