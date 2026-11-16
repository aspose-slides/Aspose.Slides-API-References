---
title: ShapeCollection
second_title: Aspose.Sildes برای مرجع API .NET
description: نمایش یک مجموعه از شکل‌ها.
type: docs
weight: 9880
url: /fa/aspose.slides/shapecollection/
---
## کلاس ShapeCollection

نمایش یک مجموعه از شکل‌ها.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | تعداد عناصری که واقعاً در مجموعه وجود دارند را برمی‌گرداند. فقط-خواندنی Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | مقدار نشان‌دهنده این که دسترسی به مجموعه همگام‌سازی شده (امن برای چندین رشته) است را برمی‌گرداند. فقط-خواندنی Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | عنصر در شاخص مشخص‌شده را برمی‌گرداند. فقط-خواندنی [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | شیء گروه شکل والد برای مجموعهٔ شکل‌ها را برمی‌گرداند. فقط-خواندنی [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | ریشهٔ همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | یک قاب صوتی جدید مرتبط با یک ترک CD ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | یک قاب صوتی جدید ایجاد می‌کند و با استفاده از شیء صوتی موجود در فهرست Presentation.Audios آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | یک قاب صوتی جدید با فایل WAV جاسازی‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. صوت جاسازی‌شده به مجموعهٔ Presentation.Audios اضافه می‌شود. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | یک قاب صوتی جدید مرتبط با یک فایل صوتی خارجی ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | یک شکل خودکار جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | یک شکل خودکار جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند؛ در صورت تمایل با قالب‌بندی الگوی پیش‌فرض مقداردهی می‌شود. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه مقداردهی می‌کند و به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه مقداردهی می‌کند و به انتهای مجموعهٔ شکل‌ها اضافه می‌کند؛ در صورت تمایل قالب‌بندی پیش‌فرض اعمال می‌شود. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. شکل کلون‌شده موقعیت و اندازهٔ اصلی را حفظ می‌کند. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. شکل جدید عرض و ارتفاع *sourceShape* را حفظ می‌کند. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | یک شکل اتصالگر جدید با سبک پیش‌فرض الگو ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | یک شکل اتصالگر جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند؛ در صورت تمایل سبک پیش‌فرض الگو اعمال می‌شود. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | یک گروه شکل خالی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. چارچوب گروه به‌طور خودکار برای مطابقت با هر شکلی که به آن اضافه می‌شود تنظیم می‌شود. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | یک گروه شکل جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به شکل‌های جداگانه تبدیل می‌کند و گروه حاصل را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | یک شکل خودکار مستطیلی جدید برای محتوای ریاضی ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | یک چارچوب شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | یک چارچوب شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | یک قاب تصویر جدید حاوی تصویر مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | یک قاب زوم بخش جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | یک قاب زوم بخش جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | یک نمودار SmartArt جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | یک قاب خلاصهٔ زوم جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | یک جدول جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | یک قاب ویدئویی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | یک قاب ویدئویی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | یک قاب زوم جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | یک قاب زوم جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند. |
| [Clear](../../aspose.slides/shapecollection/clear)() | تمام شکل‌ها را از مجموعهٔ شکل‌ها حذف می‌کند. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | تمام عناصر مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | یک شمارندهٔ تکرار (enumerator) که مجموعه را پیمایش می‌کند برمی‌گرداند. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | اندیس صفر‌پایهٔ اولین رخداد شکل مشخص‌شده در مجموعه را برمی‌گرداند. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | یک قاب صوتی جدید مرتبط با یک ترک CD ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | یک قاب صوتی جدید ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد؛ از شیء صوتی موجود در فهرست Presentation.Audios استفاده می‌کند. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | یک قاب صوتی جدید با فایل WAV جاسازی‌شده ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. صوت جاسازی‌شده به مجموعهٔ Presentation.Audios اضافه می‌شود. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | یک قاب صوتی جدید مرتبط با یک فایل صوتی خارجی ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | یک شکل خودکار جدید ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد؛ قالب‌بندی پیش‌فرض الگو اعمال می‌شود. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | یک شکل خودکار جدید ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد؛ در صورت تمایل با سبک پیش‌فرض الگو مقداردهی می‌شود. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه مقداردهی می‌کند و در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌ها و تنظیمات نمونه مقداردهی می‌کند و در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد؛ در صورت تمایل سبک پیش‌فرض الگو اعمال می‌شود. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. شکل کلون‌شده موقعیت و اندازهٔ اصلی را حفظ می‌کند. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. شکل جدید عرض و ارتفاع *sourceShape* را حفظ می‌کند. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | یک شکل اتصالگر جدید ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد؛ سبک پیش‌فرض الگو اعمال می‌شود. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | یک شکل اتصالگر جدید ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد؛ در صورت تمایل سبک پیش‌فرض الگو اعمال می‌شود. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | یک گروه شکل خالی جدید ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. چارچوب گروه به‌طور خودکار برای مطابقت با هر شکلی که به آن اضافه می‌شود تنظیم می‌شود. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | یک چارچوب شیء OLE جدید ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | یک چارچوب شیء OLE جدید ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | یک قاب تصویر جدید حاوی تصویر مشخص‌شده ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | یک قاب زوم بخش جدید ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | یک قاب زوم بخش جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | یک قاب خلاصهٔ زوم جدید ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | یک جدول جدید ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | یک قاب ویدئویی جدید ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | یک قاب زوم جدید ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | یک قاب زوم جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در مکان مشخص‌شدهٔ شاخص در مجموعهٔ شکل‌ها قرار می‌دهد. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | اولین رخداد شکل مشخص‌شده را از مجموعهٔ شکل‌ها حذف می‌کند. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | شکل در شاخص مشخص‌شده را از مجموعهٔ شکل‌ها حذف می‌کند. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | شکل مشخص‌شده را به موقعیت جدیدی درون مجموعهٔ شکل‌ها منتقل می‌کند. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | شکل‌های مشخص‌شده را درون مجموعهٔ شکل‌ها جابه‌جا می‌کند و آن‌ها را از شاخص داده‌شده شروع می‌کند. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | یک آرایهٔ شامل تمام شکل‌ها ایجاد و برمی‌گرداند. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | یک آرایهٔ شامل تمام شکل‌ها در بازهٔ مشخص‌شده ایجاد و برمی‌گرداند. |

### مراجع

* کلاس [DomObject&lt;TParent&gt;](../domobject-1)
* کلاس [GroupShape](../groupshape)
* رابط [IShapeCollection](../ishapecollection)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->