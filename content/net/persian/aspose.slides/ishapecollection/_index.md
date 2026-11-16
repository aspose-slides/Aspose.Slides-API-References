---
title: IShapeCollection
second_title: Aspose.Sildes برای .NET مرجع API
description: نماینده یک مجموعه از اشکال.
type: docs
weight: 7000
url: /fa/aspose.slides/ishapecollection/
---
## IShapeCollection رابط

یک مجموعه از اشکال را نمایندگی می‌کند.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## خواص

| نام | توضیح |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | عنصر را در ایندکس مشخص شده دریافت می‌کند. فقط-خواندنی [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | شیء شکل گروه والد برای مجموعه اشکال را دریافت می‌کند. فقط-خواندنی [`IGroupShape`](../igroupshape). |

## متدها

| نام | توضیح |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | یک قاب صوتی جدید ایجاد می‌کند که به یک تراک CD مرتبط است و آن را به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | یک قاب صوتی جدید ایجاد می‌کند و با استفاده از یک شی صوتی موجود از فهرست Presentation.Audios آن را به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | یک قاب صوتی جدید با یک فایل WAV جاسازی‌شده ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌کند. صوت جاسازی‌شده به مجموعه Presentation.Audios افزوده می‌شود. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | یک قاب صوتی جدید که به یک فایل صوتی خارجی مرتبط است ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | یک شکل خودکار جدید با قالب پیش‌فرض ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | یک شکل خودکار جدید ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌کند؛ در صورت تمایل با قالب پیش‌فرض الگو مقداردهی اولیه می‌شود. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه سری مقداردهی اولیه می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه سری مقداردهی اولیه می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | یک نسخهٔ کپی از شکل مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌کند. شکل کپی‌شده موقعیت و اندازهٔ اصلی را حفظ می‌کند. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | یک نسخهٔ کپی از شکل مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌کند. شکل جدید عرض و ارتفاع *sourceShape* را حفظ می‌کند. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | یک نسخهٔ کپی از شکل مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | یک شکل اتصال‌دهنده جدید با سبک پیش‌فرض الگو ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | یک شکل اتصال‌دهنده جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند؛ در صورت تمایل سبک پیش‌فرض الگو اعمال می‌شود. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | یک گروه شکل خالی جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. قاب گروه به‌طور خودکار برای جا گرفتن هر شکلی که به آن اضافه شود تنظیم می‌شود. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | یک گروه شکل جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به اشکال جداگانه تبدیل می‌کند و گروه حاصل را به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | یک شکل خودکار مستطیل جدید برای میزبانی محتوای ریاضی ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | یک قاب شیء OLE جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | یک قاب شیء OLE جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | یک قاب تصویر جدید حاوی تصویر مشخص‌شده ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | یک قاب Section Zoom جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | یک قاب Section Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | یک نمودار SmartArt ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | یک قاب Summary Zoom جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | یک جدول جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | یک قاب ویدئویی جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | یک قاب ویدئویی جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | یک قاب Zoom جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | یک قاب Zoom جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | تمام اشکال را از مجموعه اشکال حذف می‌کند. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | شاخص صفر مبنا از اولین رخداد شکل مشخص‌شده در مجموعه را برمی‌گرداند. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | یک قاب صوتی جدید که به یک تراک CD مرتبط است ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | یک قاب صوتی جدید ایجاد می‌کند و با استفاده از یک شی صوتی موجود از فهرست Presentation.Audios آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | یک قاب صوتی جدید با یک فایل WAV جاسازی‌شده ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. صوت جاسازی‌شده به مجموعه Presentation.Audios افزوده می‌شود. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | یک قاب صوتی جدید که به یک فایل صوتی خارجی مرتبط است ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | یک شکل خودکار جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند، قالب پیش‌فرض الگو اعمال می‌شود. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | یک شکل خودکار جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند؛ در صورت تمایل با سبک پیش‌فرض الگو مقداردهی اولیه می‌شود. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه سری مقداردهی اولیه می‌کند و در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه سری مقداردهی اولیه می‌کند و در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. شکل کپی‌شده موقعیت و اندازهٔ اصلی را حفظ می‌کند. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. شکل جدید عرض و ارتفاع *sourceShape* را حفظ می‌کند. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | یک شکل اتصال‌دهنده جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند، سبک پیش‌فرض الگو اعمال می‌شود. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | یک شکل اتصال‌دهنده جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند؛ در صورت تمایل سبک پیش‌فرض الگو اعمال می‌شود. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | یک گروه شکل خالی جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. قاب گروه به‌طور خودکار برای جا گرفتن هر شکلی که به آن اضافه شود تنظیم می‌شود. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | یک قاب شیء OLE جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | یک قاب شیء OLE جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | یک قاب تصویر جدید حاوی تصویر مشخص‌شده ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | یک قاب Section Zoom جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | یک قاب Section Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | یک قاب Summary Zoom جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | یک جدول جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | یک قاب ویدئویی جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | یک قاب Zoom جدید ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | یک قاب Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در اندیس مشخص‌شده در مجموعه اشکال وارد می‌کند. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | اولین رخداد شکل مشخص‌شده را از مجموعه اشکال حذف می‌کند. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | شکل در اندیس مشخص‌شده را از مجموعه اشکال حذف می‌کند. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | شکل مشخص‌شده را به موقعیت جدیدی در مجموعه اشکال منتقل می‌کند. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | اشکال مشخص‌شده را در مجموعه اشکال جابه‌جا می‌کند و آن‌ها را از اندیس داده‌شده شروع می‌کند. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | یک آرایه شامل تمام اشکال ایجاد و برمی‌گرداند. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | یک آرایه شامل تمام اشکال در بازهٔ مشخص‌شده ایجاد و برمی‌گرداند. |

### موارد مرتبط

* رابط [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* رابط [IShape](../ishape)
* فضای نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->