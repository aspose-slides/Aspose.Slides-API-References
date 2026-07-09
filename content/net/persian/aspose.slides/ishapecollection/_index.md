---
title: IShapeCollection
second_title: Aspose.Sildes برای مرجع API .NET
description: یک مجموعه از اشکال را نشان می‌دهد.
type: docs
weight: 6980
url: /fa/aspose.slides/ishapecollection/
---
## IShapeCollection رابط

یک مجموعه از اشکال را نشان می‌دهد.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## خواص

| نام | توضیح |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | عنصری که در ایندکس مشخص شده قرار دارد را برمی‌گرداند. فقط‌خواندنی [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | شیء گروه والد برای مجموعهٔ اشکال را برمی‌گرداند. فقط‌خواندنی [`IGroupShape`](../igroupshape). |

## متدها

| نام | توضیح |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | یک قاب صوتی جدید ایجاد می‌کند که به یک ترک CD مرتبط است و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | یک قاب صوتی جدید ایجاد می‌کند و با استفاده از شیء صوتی موجود در لیست Presentation.Audios آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | یک قاب صوتی جدید با فایل WAV جاسازی‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. صوت جاسازی‌شده به مجموعهٔ Presentation.Audios افزوده می‌شود. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | یک قاب صوتی جدید ایجاد می‌کند که به یک فایل صوتی خارجی مرتبط است و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | یک شکل خودکار جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | یک شکل خودکار جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند؛ به صورت اختیاری با قالب‌بندی پیش‌فرض قالب را مقداردهی اولیه می‌کند. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه مقداردهی می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه مقداردهی می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | کپی‌ای از شکل مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. شکل کلون‌شده موقعیت و اندازهٔ اصلی را حفظ می‌کند. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | کپی‌ای از شکل مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. شکل جدید عرض و ارتفاع *sourceShape* را حفظ می‌کند. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | کپی‌ای از شکل مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | یک شکل اتصال‌دهنده جدید با سبک قالب پیش‌فرض ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | یک شکل اتصال‌دهنده جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند؛ به صورت اختیاری با سبک قالب پیش‌فرض اعمال می‌شود. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | یک شکل گروه خالی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. قاب گروه به‌صورت خودکار برای قرار گرفتن هر شکل افزوده‌شده تنظیم می‌شود. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | یک شکل گروه جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به اشکال جداگانه تبدیل می‌کند و گروه حاصل را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | یک شکل خودکار مستطیلی جدید برای محتوای ریاضی ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | یک قاب شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | یک قاب شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | یک قاب تصویر جدید حاوی تصویر مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | یک قاب Section Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | یک قاب Section Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | یک نمودار SmartArt جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | یک قاب Summary Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | یک جدول جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | یک قاب ویدئوی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | یک قاب ویدئوی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | یک قاب Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | یک قاب Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | تمام اشکال موجود در مجموعهٔ اشکال را حذف می‌کند. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | ایندکس صفر-پایهٔ اولین وقوع شکل مشخص‌شده در مجموعه را برمی‌گرداند. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | یک قاب صوتی جدید ایجاد می‌کند که به یک ترک CD لینک شده است و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | یک قاب صوتی جدید ایجاد می‌کند و با استفاده از شیء صوتی موجود در لیست Presentation.Audios، آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | یک قاب صوتی جدید با فایل WAV جاسازی‌شده ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. صوت جاسازی‌شده به مجموعهٔ Presentation.Audios افزوده می‌شود. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | یک قاب صوتی جدید ایجاد می‌کند که به یک فایل صوتی خارجی لینک شده است و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | یک شکل خودکار جدید ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند، با قالب‌بندی پیش‌فرض. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | یک شکل خودکار جدید ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند؛ به صورت اختیاری با سبک قالب پیش‌فرض مقداردهی اولیه می‌شود. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه مقداردهی می‌کند و در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه مقداردهی می‌کند و در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | کپی‌ای از شکل مشخص‌شده ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. شکل کلون‌شده موقعیت و اندازهٔ اصلی را حفظ می‌کند. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | کپی‌ای از شکل مشخص‌شده ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. شکل جدید عرض و ارتفاع *sourceShape* را حفظ می‌کند. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | کپی‌ای از شکل مشخص‌شده ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | یک شکل اتصال‌دهنده جدید ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند، با سبک قالب پیش‌فرض. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | یک شکل اتصال‌دهنده جدید ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند؛ به صورت اختیاری با سبک قالب پیش‌فرض اعمال می‌شود. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | یک شکل گروه خالی جدید ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. قاب گروه به‌صورت خودکار برای قرار گرفتن هر شکل افزوده‌شده تنظیم می‌شود. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | یک قاب شیء OLE جدید ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | یک قاب شیء OLE جدید ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | یک قاب تصویر جدید حاوی تصویر مشخص‌شده ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | یک قاب Section Zoom جدید ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | یک قاب Section Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | یک قاب Summary Zoom جدید ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | یک جدول جدید ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | یک قاب ویدئوی جدید ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | یک قاب Zoom جدید ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | یک قاب Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در ایندکس مشخص‌شده در مجموعهٔ اشکال درج می‌کند. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | اولین وقوع شکل مشخص‌شده را از مجموعهٔ اشکال حذف می‌کند. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | شکل موجود در ایندکس مشخص‌شده را از مجموعهٔ اشکال حذف می‌کند. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | شکل مشخص‌شده را به موقعیت جدیدی درون مجموعهٔ اشکال منتقل می‌کند. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | اشکال مشخص‌شده را درون مجموعهٔ اشکال جابه‌جا می‌کند و آن‌ها را از ایندکس داده‌شده به بعد قرار می‌دهد. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | آرایه‌ای شامل تمام اشکال ایجاد و برمی‌گرداند. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | آرایه‌ای شامل تمام اشکال در بازه مشخص‌شده ایجاد و برمی‌گرداند. |

### موارد مرتبط

* رابط [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* رابط [IShape](../ishape)
* فضای‌نامی [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->