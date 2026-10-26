---
title: ShapeCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایشگر مجموعه‌ای از اشکال.
type: docs
url: /fa/com.aspose.slides/shapecollection/
---
**ارث‌بری:**  
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)  
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

نمایش یک مجموعه از اشکال است.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد عناصری که واقعاً در مجموعه موجود هستند را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در اندیس مشخص شده را برمی‌گرداند. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند، و به انتهای مجموعهٔ اشکال اضافه می‌گردد. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند، و به انتهای مجموعهٔ اشکال اضافه می‌گردد. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | یک نمودار SmartArt ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند، و در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌کند. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند، و در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌کند. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | یک فریم Zoom جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | یک فریم Zoom جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | یک فریم Zoom جدید ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌گردد. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | یک فریم Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌گردد. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | یک فریم Section Zoom جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | یک فریم Section Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | یک فریم Section Zoom جدید ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | یک فریم Section Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | یک فریم Summary Zoom جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | یک فریم Summary Zoom جدید ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌گردد. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | یک فریم شیء OLE جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | یک فریم شیء OLE جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | یک فریم شیء OLE جدید ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌شود. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | یک فریم شیء OLE جدید ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌شود. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | یک فریم ویدئویی جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | یک فریم ویدئویی جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | یک فریم ویدئویی جدید ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | یک فریم صوتی جدید مرتبط با یک تراک CD ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | یک فریم صوتی جدید مرتبط با یک تراک CD ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | یک فریم صوتی جدید مرتبط با یک فایل صوتی خارجی ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | یک فریم صوتی جدید مرتبط با یک فایل صوتی خارجی ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | یک فریم صوتی جدید با فایل WAV جاسازی‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | یک فریم صوتی جدید با فایل WAV جاسازی‌شده ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | یک فریم صوتی جدید ایجاد می‌کند و با استفاده از یک شیء صوتی موجود از لیست Presentation.Audios، به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | یک فریم صوتی جدید ایجاد می‌کند و با استفاده از یک شیء صوتی موجود از لیست Presentation.Audios، در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | شاخص صفر مبنایی اولین رخداد شکل مشخص‌شده در مجموعه را برمی‌گرداند. |
| [toArray()](#toArray--) | یک آرایه که شامل تمام اشکال است را ایجاد و برمی‌گرداند. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | یک آرایه که شامل تمام اشکال در بازهٔ مشخص‌شده است را ایجاد و برمی‌گرداند. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | شکل مشخص‌شده را به موقعیت جدیدی درون مجموعهٔ اشکال منتقل می‌کند. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | اشکال مشخص‌شده را در مجموعهٔ اشکال جابه‌جا می‌کند به طوری که از اندیس داده‌شده شروع می‌شوند. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | یک شکل خودکار جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | یک شکل خودکار جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود؛ به‌صورت اختیاری با قالب‌بندی پیش‌فرض قالب شروع می‌شود. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | یک شکل خودکار مستطیل جدید برای میزبانی محتوای ریاضی ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | یک شکل خودکار جدید ایجاد می‌کند و با اعمال قالب پیش‌فرض، در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | یک شکل خودکار جدید ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند؛ به‌صورت اختیاری با سبک پیش‌فرض قالب شروع می‌شود. |
| [addGroupShape()](#addGroupShape--) | یک گروه شکل خالی جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | یک گروه شکل جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به اشکال فردی تبدیل می‌کند، و گروه حاصل را به انتهای مجموعهٔ اشکال اضافه می‌کند. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | یک گروه شکل خالی جدید ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | یک شکل اتصال جدید با سبک قالب پیش‌فرض ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | یک شکل اتصال جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود؛ به‌صورت اختیاری سبک پیش‌فرض قالب اعمال می‌شود. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | یک شکل اتصال جدید ایجاد می‌کند و با اعمال سبک پیش‌فرض قالب، در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | یک شکل اتصال جدید ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند؛ به‌صورت اختیاری سبک پیش‌فرض قالب اعمال می‌شود. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | یک فریم تصویر جدید شامل تصویر مشخص‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | یک فریم تصویر جدید شامل تصویر مشخص‌شده ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | یک جدول جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | یک جدول جدید ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند. |
| [removeAt(int index)](#removeAt-int-) | شکل موجود در اندیس مشخص‌شده را از مجموعهٔ اشکال حذف می‌کند. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | اولین رخداد شکل مشخص‌شده را از مجموعهٔ اشکال حذف می‌کند. |
| [clear()](#clear--) | تمام اشکال را از مجموعهٔ اشکال حذف می‌کند. |
| [iterator()](#iterator--) | یک شمارنده که مجموعه را پیمایش می‌کند برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [getParentGroup()](#getParentGroup--) | شیء گروه شکل والد برای مجموعهٔ اشکال را برمی‌گرداند. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و در اندیس مشخص شده به مجموعهٔ اشکال وارد می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده است (ایمن برای چندین رشته). |
| [getSyncRoot()](#getSyncRoot--) | یک ریشهٔ همگام‌سازی را برمی‌گرداند. |

### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعاً در مجموعه موجود هستند را برمی‌گرداند. فقط-خواندنی  int .

**بازگرداندن:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

عنصر موجود در اندیس مشخص شده را برمی‌گرداند. فقط-خواندنی [IShape](../../com.aspose.slides/ishape).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگرداندن:**  
[IShape](../../com.aspose.slides/ishape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند، و به انتهای مجموعهٔ اشکال اضافه می‌گردد.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Instantiates the Presentation class that represents a PPTX file
>  Presentation pres = new Presentation();
>  try {
>      // Accesses the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Adds a chart with its default data
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Sets the chart title
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Sets the first series to show values
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Sets the index for the chart data sheet
>      int defaultWorksheetIndex = 0;
>      // Gets the chart data worksheet
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Deletes the default generated series and categories
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Adds new series
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Adds new categories
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Takes the first chart series
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Populates series data
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Sets the fill color for the series
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Takes the second chart series
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Populates series data
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Sets the fill color for series
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Sets the first label to show Category name
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Sets the series to show the value for the third label
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // Saves the PPTX file to disk
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع نمودار برای افزودن. |
| x | float | مختصات x نمودار جدید، به نقطه. |
| y | float | مختصات y نمودار جدید، به نقطه. |
| width | float | عرض نمودار، به نقطه. |
| height | float | ارتفاع نمودار، به نقطه. |

**بازگرداندن:**
[IChart](../../com.aspose.slides/ichart) - ایجاد شدهٔ جدید [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند، و به انتهای مجموعهٔ اشکال اضافه می‌گردد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع نمودار برای افزودن. |
| x | float | مختصات x نمودار جدید، به نقطه. |
| y | float | مختصات y نمودار جدید، به نقطه. |
| width | float | عرض نمودار، به نقطه. |
| height | float | ارتفاع نمودار، به نقطه. |
| initWithSample | boolean | درست برای مقداردهی اولیه نمودار جدید با داده‌های نمونه سری و تنظیمات؛ غلط برای ایجاد نمودار بدون سری و فقط تنظیمات کمینه، که ساخت را سریع‌تر می‌کند. |

**بازگرداندن:**
[IChart](../../com.aspose.slides/ichart) - ایجاد شدهٔ جدید [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

یک نمودار SmartArt جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌شود.

--------------------

> ```
> The following example shows how to add smart shape in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x قاب نمودار، به نقطه. |
| y | float | مختصات y قاب نمودار، به نقطه. |
| width | float | عرض قاب نمودار، به نقطه. |
| height | float | ارتفاع قاب نمودار، به نقطه. |
| layoutType | int | نوع طرح‌بندی SmartArt. |

**بازگرداندن:**
[ISmartArt](../../com.aspose.slides/ismartart) - ایجاد شدهٔ جدید [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند، و در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع نمودار برای ایجاد. |
| x | float | مختصات x نمودار جدید، به نقطه. |
| y | float | مختصات y نمودار جدید، به نقطه. |
| width | float | عرض نمودار جدید، به نقطه. |
| height | float | ارتفاع نمودار جدید، به نقطه. |
| index | int | اندیس صفر-مبنا که نمودار جدید در آن در مجموعهٔ اشکال وارد می‌شود. |

**بازگرداندن:**
[IChart](../../com.aspose.slides/ichart) - ایجاد شدهٔ جدید [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند، و در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع نمودار برای ایجاد. |
| x | float | مختصات x نمودار جدید، به نقطه. |
| y | float | مختصات y نمودار جدید، به نقطه. |
| width | float | عرض نمودار جدید، به نقطه. |
| height | float | ارتفاع نمودار جدید، به نقطه. |
| index | int | اندیس صفر-مبنا که نمودار جدید در آن در مجموعهٔ اشکال وارد می‌شود. |
| initWithSample | boolean | درست برای مقداردهی اولیه نمودار جدید با داده‌های نمونه سری و تنظیمات؛ غلط برای ایجاد نمودار بدون سری و فقط تنظیمات کمینه، که ساخت را سریع‌تر می‌کند. |
| x | float | مختصات x نمودار جدید، به نقاط. |
| y | float | مختصات y نمودار جدید، به نقاط. |
| width | float | عرض نمودار جدید، به نقاط. |
| height | float | ارتفاع نمودار جدید، به نقاط. |
| index | int | اندیس صفر مبنا که نمودار جدید در مجموعه اشکال در آن درج می‌شود. |
| initWithSample | boolean | در صورت true برای مقداردهی اولیه نمودار جدید با داده‌های نمونه سری و تنظیمات؛ در صورت false برای ایجاد نمودار بدون سری و فقط تنظیمات حداقل، که باعث سرعت بیشتر ایجاد می‌شود. |

**بازگشت:**  
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) جدید ایجاد شده.

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

یک قاب زوم جدید ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌نماید.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x قاب زوم جدید، به نقاط. |
| y | float | مختصات y قاب زوم جدید، به نقاط. |
| width | float | عرض قاب زوم جدید، به نقاط. |
| height | float | ارتفاع قاب زوم جدید، به نقاط. |
| slide | [ISlide](../../com.aspose.slides/islide) | مورد [ISlide](../../com.aspose.slides/islide) که توسط قاب زوم ارجاع شده؛ باید به این ارائه تعلق داشته باشد. |

**بازگشت:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) جدید ایجاد شده.

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

یک قاب زوم جدید ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌نماید.

--------------------

> ```
> این مثال نشان می‌دهد چگونه یک شی Zoom را به انتهای یک مجموعه اضافه کنیم
>  (فرض کنید که در ارائه‌ی "Presentation.pptx" حداقل دو اسلاید وجود دارد):
>  
  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x قاب زوم جدید، به نقاط. |
| y | float | مختصات y قاب زوم جدید، به نقاط. |
| width | float | عرض قاب زوم جدید، به نقاط. |
| height | float | ارتفاع قاب زوم جدید، به نقاط. |
| slide | [ISlide](../../com.aspose.slides/islide) | مورد [ISlide](../../com.aspose.slides/islide) که توسط قاب زوم ارجاع شده؛ باید به این ارائه تعلق داشته باشد. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | تصویر برای اسلاید ارجاع شده [IPPImage](../../com.aspose.slides/ippimage). |

**بازگشت:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) جدید ایجاد شده.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

یک قاب زوم جدید ایجاد می‌کند و آن را در مجموعه اشکال در اندیس مشخص‌شده وارد می‌نماید.

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر مبنا که قاب زوم در آن وارد می‌شود. |
| x | float | مختصات x قاب زوم جدید، به نقاط. |
| y | float | مختصات y قاب زوم جدید، به نقاط. |
| width | float | عرض قاب زوم جدید، به نقاط. |
| height | float | ارتفاع قاب زوم جدید، به نقاط. |
| slide | [ISlide](../../com.aspose.slides/islide) | مورد [ISlide](../../com.aspose.slides/islide) که توسط قاب زوم ارجاع شده. |

**بازگشت:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) جدید ایجاد شده.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

یک قاب زوم جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در مجموعه اشکال در اندیس مشخص‌شده وارد می‌نماید.

--------------------

> ```
> این مثال نمایش می‌دهد چگونه یک شی Zoom را ایجاد کرده و در شاخص مشخص شده‌ای از یک مجموعه وارد کنیم
>  (فرض کنید که در ارائه‌ی "Presentation.pptx" حداقل دو اسلاید موجود است):
>  
  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر مبنا که قاب زوم در آن وارد می‌شود. |
| x | float | مختصات x قاب زوم جدید، به نقاط. |
| y | float | مختصات y قاب زوم جدید، به نقاط. |
| width | float | عرض قاب زوم جدید، به نقاط. |
| height | float | ارتفاع قاب زوم جدید، به نقاط. |
| slide | [ISlide](../../com.aspose.slides/islide) | مورد [ISlide](../../com.aspose.slides/islide) که توسط قاب زوم ارجاع شده. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | تصویر برای اسلاید ارجاع شده [IPPImage](../../com.aspose.slides/ippimage). |

**بازگشت:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) جدید ایجاد شده.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

یک قاب زوم بخش جدید ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌نماید.

--------------------

> ```
> این مثال نشان می‌دهد چگونه یک شی Section Zoom را به انتهای یک مجموعه اضافه کنیم
>  (فرض کنید که در ارائه‌ی "Presentation.pptx" حداقل دو بخش وجود دارد):
>  
  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x قاب زوم بخش جدید، به نقاط. |
| y | float | مختصات y قاب زوم بخش جدید، به نقاط. |
| width | float | عرض قاب زوم بخش جدید، به نقاط. |
| height | float | ارتفاع قاب زوم بخش جدید، به نقاط. |
| section | [ISection](../../com.aspose.slides/isection) | مورد [ISection](../../com.aspose.slides/isection) که توسط قاب زوم بخش ارجاع شده؛ باید به این ارائه تعلق داشته باشد و حداقل یک اسلاید داشته باشد. |

**بازگشت:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) جدید ایجاد شده.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

یک قاب زوم بخش جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌نماید.

--------------------

> ```
> این مثال نشان می‌دهد چگونه یک شی Section Zoom را به انتهای یک مجموعه اضافه کنیم
>  (فرض کنید که در ارائه‌ی "Presentation.pptx" حداقل دو بخش موجود است):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x قاب زوم بخش جدید، به نقاط. |
| y | float | مختصات y قاب زوم بخش جدید، به نقاط. |
| width | float | عرض قاب زوم بخش جدید، به نقاط. |
| height | float | ارتفاع قاب زوم بخش جدید، به نقاط. |
| section | [ISection](../../com.aspose.slides/isection) | مورد [ISection](../../com.aspose.slides/isection) که توسط قاب زوم بخش ارجاع شده؛ باید به این ارائه تعلق داشته باشد و حداقل یک اسلاید داشته باشد. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) برای نمایش در داخل قاب زوم بخش. |

**بازگشت:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) جدید ایجاد شده.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```
یک فریم Section Zoom جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده درج می‌کند.

--------------------

> ```
> این مثال ایجاد و درج یک شی Section Zoom را در شاخص مشخص شده‌ای از یک مجموعه نشان می‌دهد
>  (فرض کنید که در ارائه‌ی "Presentation.pptx" حداقل دو بخش موجود باشد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر مبنایی که فریم Section Zoom در آن درج می‌شود. |
| x | float | مختصات x فریم Section Zoom جدید، به نقطه. |
| y | float | مختصات y فریم Section Zoom جدید، به نقطه. |
| width | float | عرض فریم Section Zoom جدید، به نقطه. |
| height | float | ارتفاع فریم Section Zoom جدید، به نقطه. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) که توسط فریم Section Zoom ارجاع داده می‌شود؛ باید متعلق به این ارائه باشد و حداقل یک اسلاید داشته باشد. |

**بازگرداندن:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) جدید ایجاد شده.
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

یک فریم Section Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده درج می‌کند.

--------------------

> ```
> این مثال ایجاد و درج یک شی Section Zoom را در شاخص مشخص شده‌ای از یک مجموعه نشان می‌دهد
>  (فرض کنید که در ارائه‌ی "Presentation.pptx" حداقل دو بخش وجود دارد):
>  
  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر مبنایی که فریم Section Zoom در آن درج می‌شود. |
| x | float | مختصات x فریم Section Zoom جدید، به نقطه. |
| y | float | مختصات y فریم Section Zoom جدید، به نقطه. |
| width | float | عرض فریم Section Zoom جدید، به نقطه. |
| height | float | ارتفاع فریم Section Zoom جدید، به نقطه. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) که توسط فریم Section Zoom ارجاع داده می‌شود؛ باید متعلق به این ارائه باشد و حداقل یک اسلاید داشته باشد. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | تصویری که در فریم Section Zoom نمایش داده می‌شود. |

**بازگرداندن:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) جدید ایجاد شده.
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

یک فریم Summary Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند.

--------------------

> ```
> این مثال نشان می‌دهد چگونه یک شی Summary Zoom را به انتهای یک مجموعه اضافه کنیم
>  (فرض کنید که در ارائه‌ی "Presentation.pptx" حداقل دو بخش موجود است):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x فریم Summary Zoom جدید، به نقطه. |
| y | float | مختصات y فریم Summary Zoom جدید، به نقطه. |
| width | float | عرض فریم Summary Zoom جدید، به نقطه. |
| height | float | ارتفاع فریم Summary Zoom جدید، به نقطه. |

--------------------

این متد یک Summary Zoom جدید ایجاد می‌کند و مجموعه‌ای از اشیاء را برای تمام بخش‌های این ارائه در آن قرار می‌دهد. |
**بازگرداندن:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) جدید ایجاد شده.
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

یک فریم Summary Zoom جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده درج می‌کند.

--------------------

> ```
> این مثال ایجاد و افزودن یک شی Summary Zoom را در شاخص مشخص شده‌ای از یک مجموعه نشان می‌دهد
>  (فرض کنید که در ارائه‌ی "Presentation.pptx" حداقل دو بخش وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر مبنایی که فریم Summary Zoom در آن درج می‌شود. |
| x | float | مختصات x فریم Summary Zoom جدید، به نقطه. |
| y | float | مختصات y فریم Summary Zoom جدید، به نقطه. |
| width | float | عرض فریم Summary Zoom جدید، به نقطه. |
| height | float | ارتفاع فریم Summary Zoom جدید، به نقطه. |

--------------------

این متد فریم Summary Zoom را ایجاد می‌کند که پیوندهای خلاصه را برای تمام بخش‌های ارائه جمع‌آوری می‌کند. |
**بازگرداندن:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) جدید ایجاد شده.
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

یک فریم شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند.

--------------------

> ```
> مثال‌های زیر نشان می‌دهند چگونه فریم‌های شی OLE را به اسلایدهای ارائه PowerPoint اضافه کنیم.
>  
>  // یک نمونه از کلاس Presentation که نمایانگر فایل PPTX است
>  Presentation pres = new Presentation();
>  try
>  {
>      // به اسلاید اول دسترسی می‌یابد
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // فایل سل را به استریم بارگذاری می‌کند
>      FileInputStream fs = new FileInputStream("book1.xlsx");
>      ByteArrayOutputStream mstream = new ByteArrayOutputStream();
>      byte[] buf = new byte[4096];
> 
>      while (true)
>      {
>          int bytesRead = fs.read(buf, 0, buf.length);
>          if (bytesRead <= 0)
>              break;
>          mstream.write(buf, 0, bytesRead);
>      }
>      // ایجاد شی داده برای جاسازی
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // افزودن یک شکل فریم شی OLE
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // نوشتن PPTX به دیسک
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x فریم OLE جدید، به نقطه. |
| y | float | مختصات y فریم OLE جدید، به نقطه. |
| width | float | عرض فریم OLE جدید، به نقطه. |
| height | float | ارتفاع فریم OLE جدید، به نقطه. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | اطلاعات درباره داده‌های جاسازی‌شده OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**بازگرداندن:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) جدید ایجاد شده.
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

یک فریم شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x فریم OLE جدید، به نقطه. |
| y | float | مختصات y فریم OLE جدید، به نقطه. |
| width | float | عرض فریم OLE جدید، به نقطه. |
| height | float | ارتفاع فریم OLE جدید، به نقطه. |
| className | java.lang.String | نام کلاس شیء OLE. |
| path | java.lang.String | مسیر به فایل پیوست شده. |

این مسیر به همان شکل در ارائه ذخیره می‌شود. اگر مسیر نسبی مشخص شود، فایل هنگام باز کردن ارائه از یک دایرکتوری متفاوت در دسترس نخواهد بود. |
**بازگرداندن:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) جدید ایجاد شده.
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

یک فریم شیء OLE جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده درج می‌کند.

--------------------

> ```
> این مثال نشان می‌دهد چگونه یک شی OLE را در شاخص دوم وارد کنیم:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر مبنایی که فریم OLE در آن درج می‌شود. |
| x | float | مختصات x قاب OLE جدید، به نقاط. |
| y | float | مختصات y قاب OLE جدید، به نقاط. |
| width | float | عرض قاب OLE جدید، به نقاط. |
| height | float | ارتفاع قاب OLE جدید، به نقاط. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | اطلاعات داده‌ایٔ جاسازی‌شدهٔ OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**بازگشت:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) تازه ایجاد شده.

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

یک قاب شیء OLE جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در اندیس مشخص شده درج می‌نماید.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر مبنا که قاب شیء OLE در آن درج می‌شود. |
| x | float | مختصات x قاب OLE جدید، به نقاط. |
| y | float | مختصات y قاب OLE جدید، به نقاط. |
| width | float | عرض قاب OLE جدید، به نقاط. |
| height | float | ارتفاع قاب OLE جدید، به نقاط. |
| className | java.lang.String | نام کلاس شیء OLE. |
| path | java.lang.String | مسیر فایل مرتبط.  
این مسیر به همان صورت در ارائه ذخیره می‌شود. اگر مسیر نسبی مشخص شود، هنگام باز کردن ارائه از دایرکتوری متفاوت، فایل قابل دسترسی نخواهد بود. |

**بازگشت:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - قاب شیء OLE تازه ایجاد شده.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

یک قاب ویدئوی جدید ایجاد می‌کند و به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات x قاب ویدئوی جدید، به نقاط. |
| y | float | مختصات y قاب ویدئوی جدید، به نقاط. |
| width | float | عرض قاب ویدئوی جدید، به نقاط. |
| height | float | ارتفاع قاب ویدئوی جدید، به نقاط. |
| fname | java.lang.String | مسیر یا نام فایل ویدئویی که باید جاسازی شود. |

**بازگشت:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) تازه ایجاد شده.

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

یک قاب ویدئوی جدید ایجاد می‌کند و به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات x قاب ویدئوی جدید، به نقاط. |
| y | float | مختصات y قاب ویدئوی جدید، به نقاط. |
| width | float | عرض قاب ویدئوی جدید، به نقاط. |
| height | float | ارتفاع قاب ویدئوی جدید، به نقاط. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) برای جاسازی در قاب ویدئویی. |

**بازگشت:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) تازه ایجاد شده.

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

یک قاب ویدئوی جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در اندیس مشخص شده درج می‌نماید.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر مبنا که قاب ویدئویی در آن درج می‌شود. |
| x | float | مختصات x قاب ویدئوی جدید، به نقاط. |
| y | float | مختصات y قاب ویدئوی جدید، به نقاط. |
| width | float | عرض قاب ویدئوی جدید، به نقاط. |
| height | float | ارتفاع قاب ویدئوی جدید، به نقاط. |
| fname | java.lang.String | مسیر یا نام فایل ویدئویی که باید جاسازی شود. |

**بازگشت:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) تازه ایجاد شده.

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

یک قاب صوتی جدید که به یک تراک CD مرتبط است ایجاد می‌کند و به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات x قاب صوتی جدید، به نقاط. |
| y | float | مختصات y قاب صوتی جدید، به نقاط. |
| width | float | عرض قاب صوتی جدید، به نقاط. |
| height | float | ارتفاع قاب صوتی جدید، به نقاط. |

**بازگشت:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه ایجاد شده.

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

یک قاب صوتی جدید که به یک تراک CD مرتبط است ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در اندیس مشخص شده درج می‌نماید.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر مبنا که قاب صوتی در آن درج می‌شود. |
| x | float | مختصات x قاب صوتی جدید، به نقاط. |
| y | float | مختصات y قاب صوتی جدید، به نقاط. |
| width | float | عرض قاب صوتی جدید، به نقاط. |
| height | float | ارتفاع قاب صوتی جدید، به نقاط. |

**بازگشت:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه ایجاد شده.

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

یک قاب صوتی جدید که به یک فایل صوتی خارجی مرتبط است ایجاد می‌کند و به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات x قاب صوتی جدید، به نقاط. |
| y | float | مختصات y قاب صوتی جدید، به نقاط. |
| width | float | عرض قاب صوتی جدید، به نقاط. |
| height | float | ارتفاع قاب صوتی جدید، به نقاط. |
| fname | java.lang.String | مسیر یا نام فایل صوتی خارجی که باید لینک شود. |

**بازگشت:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه ایجاد شده.

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

یک قاب صوتی جدید که به یک فایل صوتی خارجی مرتبط است ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در اندیس مشخص شده درج می‌نماید.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر مبنا که قاب صوتی در آن درج می‌شود. |
| x | float | مختصات x قاب صوتی جدید، به نقاط. |
| y | float | مختصات y قاب صوتی جدید، به نقاط. |
| width | float | عرض قاب صوتی جدید، به نقاط. |
| height | float | ارتفاع قاب صوتی جدید، به نقاط. |
| fname | java.lang.String | مسیر یا نام فایل صوتی خارجی که باید لینک شود. |

**بازگشت:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه ایجاد شده.

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

یک قاب صوتی جدید با یک فایل WAV جاسازی‌شده ایجاد می‌کند و به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید. صوت جاسازی‌شده به مجموعهٔ Presentation.Audios اضافه می‌شود.

--------------------

> ```
> مثال‌های زیر نشان می‌دهند چگونه فریم صدا را ایجاد کنیم.
>  
>  // یک شی از کلاس Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
>  Presentation pres = new Presentation();
>  try {
>      // اسلاید اول را دریافت می‌کند
>      ISlide sld = pres.getSlides().get_Item(0);
>      // فایل صوتی wav را به استریم بارگذاری می‌کند
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // فریم صدا را اضافه می‌کند
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // حالت پخش و حجم صدا را تنظیم می‌کند
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // فایل پاورپوینت را بر روی دیسک می‌نویسد
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات x قاب صوتی جدید، به نقاط. |
| y | float | مختصات y قاب صوتی جدید، به نقاط. |
| width | float | عرض قاب صوتی جدید، به نقاط. |
| height | float | ارتفاع قاب صوتی جدید، به نقاط. |
| audio_stream | java.io.InputStream | یک جریان ورودی حاوی داده‌های صوتی WAV برای جاسازی. |

**بازگشت:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه ایجاد شده.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

یک قاب صوتی جدید با یک فایل WAV جاسازی‌شده ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در اندیس مشخص شده درج می‌نماید. صوت جاسازی‌شده به مجموعهٔ Presentation.Audios اضافه می‌شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر مبنا که قاب صوتی در آن درج می‌شود. |
| x | float | مختصات x قاب صوتی جدید، به نقاط. |
| y | float | مختصات y قاب صوتی جدید، به نقاط. |
| width | float | عرض قاب صوتی جدید، به نقاط. |
| height | float | ارتفاع قاب صوتی جدید، به نقاط. |
| audio_stream | java.io.InputStream | یک جریان ورودی حاوی داده‌های صوتی WAV برای جاسازی. |

**بازگشت:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه ایجاد شده.

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

یک قاب صوتی جدید ایجاد می‌کند و با استفاده از یک شیء صوتی موجود از فهرست Presentation.Audios آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات x قاب صوتی جدید، به نقاط. |
| y | float | مختصات y قاب صوتی جدید، به نقاط. |
| width | float | عرض قاب صوتی جدید، به نقاط. |
| height | float | ارتفاع قاب صوتی جدید، به نقاط. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | یک نمونهٔ [IAudio](../../com.aspose.slides/iaudio) از مجموعهٔ Presentation.Audios. |

**بازگشت:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه ایجاد شده.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

یک قاب صوتی جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در اندیس مشخص شده درج می‌نماید با استفاده از یک شیء صوتی موجود از فهرست Presentation.Audios.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر مبنا که قاب صوتی در آن درج می‌شود. |
| x | float | مختصات x قاب صوتی جدید، به نقاط. |
| y | float | مختصات y قاب صوتی جدید، به نقاط. |
| width | float | عرض قاب صوتی جدید، به نقاط. |
| height | float | ارتفاع قاب صوتی جدید، به نقاط. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | یک نمونهٔ [IAudio](../../com.aspose.slides/iaudio) از مجموعهٔ Presentation.Audios برای جاسازی. |

**بازگشت:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه ایجاد شده.

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

اندیس صفر مبنای اولین رخداد شکل مشخص‌شده در مجموعه را برمی‌گرداند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | شکلی که باید در مجموعه پیدا شود. |

**بازگشت:**
int - اندیس صفر مبنای اولین رخداد شکل در مجموعهٔ شکل‌ها در صورت یافتن؛ در غیر این صورت، \\u20131.

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

یک آرایه شامل تمام اشکال ایجاد و بازمی‌گرداند.

**بازگشت:**
com.aspose.slides.IShape[] - یک آرایه از اشیاء [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

یک آرایه شامل تمام اشکال در بازهٔ مشخص‌شده ایجاد و بازمی‌گرداند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | اندیس اولین شکلی که باید بازگردانده شود. |
| count | int | تعداد اشکالی که باید بازگردانده شود. |

**بازگشت:**
com.aspose.slides.IShape[] - یک آرایه از اشیاء [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

شکل مشخص‌شده را به موقعیتی جدید درون مجموعهٔ شکل‌ها منتقل می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس هدف صفر مبنا که شکل در آن قرار خواهد گرفت. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای جابجایی در مجموعه. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

اشکال مشخص‌شده را در مجموعهٔ شکل‌ها جابجا می‌کند و آن‌ها را از اندیس داده‌شده شروع می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس هدف صفر مبنا که اولین شکل مشخص‌شده در آن قرار خواهد گرفت؛ اشکال بعدی به ترتیب ارائه‌شده دنبال می‌شوند. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | یک یا چند نمونه [IShape](../../com.aspose.slides/ishape) برای جابجایی درون مجموعه. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

یک شکل خودکار جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) شکل خودکار برای افزودن. |
| x | float | مختصات x قاب شکل، به پوینت. |
| y | float | مختصات y قاب شکل، به پوینت. |
| width | float | عرض قاب شکل، به پوینت. |
| height | float | ارتفاع قاب شکل، به پوینت. |

**خروجی:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) جدیداً ایجاد شده.

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

یک شکل خودکار جدید ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌نماید، به‌صورت اختیاری با قالب پیش‌فرض قالب‌بندی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) شکل خودکار برای افزودن. |
| x | float | مختصات x قاب شکل، به پوینت. |
| y | float | مختصات y قاب شکل، به پوینت. |
| width | float | عرض قاب شکل، به پوینت. |
| height | float | ارتفاع قاب شکل، به پوینت. |
| createFromTemplate | boolean | True برای اعمال سبک قالب پیش‌فرض (سبک ساده، متن مرکزی، و نام غیر خالی) به شکل جدید؛ false برای ایجاد شکل با تمام خصوصیات تنظیم شده به مقادیر پیش‌فرض. |

**خروجی:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) جدیداً ایجاد شده.

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

یک شکل خودکار مستطیلی جدید برای میزبانی محتوای ریاضی ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌نماید.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه یک معادله ریاضی را در ارائه PowerPoint اضافه کنیم.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape mathShape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 720, 150);
>      IMathParagraph mathParagraph = ((MathPortion)mathShape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      IMathFraction fraction = new MathematicalText("x").divide("y");
>      mathParagraph.add(new MathBlock(fraction));
>      IMathBlock mathBlock = new MathematicalText("c")
>          .setSuperscript("2")
>          .join("=")
>          .join(new MathematicalText("a").setSuperscript("2"))
>          .join("+")
>          .join(new MathematicalText("b").setSuperscript("2"));
>      mathParagraph.add(mathBlock);
>      pres.save("math.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x قاب شکل، به پوینت. |
| y | float | مختصات y قاب شکل، به پوینت. |
| width | float | عرض قاب شکل، به پوینت. |
| height | float | ارتفاع قاب شکل، به پوینت. |

**خروجی:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) جدیداً ایجاد شده.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

یک شکل خودکار جدید ایجاد می‌کند و آن را در ایندکس مشخص شده به مجموعه شکل‌ها وارد می‌کند، با اعمال قالب پیش‌فرض قالب‌بندی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که شکل خودکار جدید در آن وارد می‌شود. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) شکل خودکار برای وارد کردن. |
| x | float | مختصات x قاب شکل، به پوینت. |
| y | float | مختصات y قاب شکل، به پوینت. |
| width | float | عرض قاب شکل، به پوینت. |
| height | float | ارتفاع قاب شکل، به پوینت. |

**خروجی:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) جدیداً ایجاد شده.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

یک شکل خودکار جدید ایجاد می‌کند و آن را در ایندکس مشخص شده به مجموعه شکل‌ها وارد می‌کند، به‌صورت اختیاری با قالب پیش‌فرض سبک قالب‌بندی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که شکل خودکار در آن وارد می‌شود. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) شکل خودکار برای وارد کردن. |
| x | float | مختصات x قاب شکل، به پوینت. |
| y | float | مختصات y قاب شکل، به پوینت. |
| width | float | عرض قاب شکل، به پوینت. |
| height | float | ارتفاع قاب شکل، به پوینت. |
| createFromTemplate | boolean | True برای اعمال سبک قالب پیش‌فرض (شامل نام غیر خالی، سبک ساده، و متن مرکزی)؛ false برای ایجاد شکل با تمام خصوصیات تنظیم شده به مقادیر پیش‌فرض. |

**خروجی:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) جدیداً ایجاد شده.

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

یک گروه شکل خالی جدید ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌نماید. چهارچوب گروه به‌صورت خودکار برای دربرگیری هر شکلی که به آن اضافه شود تنظیم می‌شود.

--------------------

> ```
> The following example shows how to add a group shape to a slide of PowerPoint Presentation.
>  
>  // Instantiate Presentation class
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Accessing the shape collection of slides
>      IShapeCollection slideShapes = sld.getShapes();
>      // Adding a group shape to the slide
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Adding shapes inside added group shape
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Adding group shape frame
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // Write the PPTX file to disk
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**خروجی:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) جدیداً ایجاد شده.

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

یک گروه شکل جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به شکل‌های جداگانه تبدیل می‌کند، و گروه حاصل را به انتهای مجموعه شکل‌ها اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) حاوی محتوای وکتور برای تبدیل به شکل‌ها. |
| x | float | مختصات x چارچوب گروه، به پوینت. |
| y | float | مختصات y چارچوب گروه، به پوینت. |
| width | float | عرض چارچوب گروه، به پوینت. |
| height | float | ارتفاع چارچوب گروه، به پوینت. |

**خروجی:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) جدیداً ایجاد شده.

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

یک گروه شکل خالی جدید ایجاد می‌کند و آن را در ایندکس مشخص‌شده به مجموعه شکل‌ها وارد می‌کند. چارچوب گروه به‌صورت خودکار برای دربرگیری هر شکلی که به آن اضافه شود تنظیم می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که گروه شکل در آن وارد می‌شود. |

**خروجی:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) جدیداً ایجاد شده.

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

یک شکل کانکتور جدید با سبک قالب پیش‌فرض ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌نماید.

--------------------

> ```
> این مثال نشان می‌دهد چگونه یک کانکتور (یک کانکتور خمیده) بین دو شکل (یک بیضی و یک مستطیل) در ارائه PowerPoint اضافه کنیم.
>  
>  // یک شی از کلاس Presentation ایجاد می‌کند که نمایانگر یک فایل PPTX است
>  Presentation pres = new Presentation();
>  try {
>      // به مجموعه اشکال اسلاید خاص دسترسی می‌یابد
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // یک شکل خودکار بیضی اضافه می‌کند
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // یک شکل خودکار مستطیل اضافه می‌کند
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // یک شکل کانکتور را به مجموعه اشکال اسلاید اضافه می‌کند
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // اشکال را با استفاده از کانکتور متصل می‌کند
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // متد reroute را فراخوانی می‌کند که مسیر کوتاه‌ترین خودکار بین اشکال را تنظیم می‌نماید
>      connector.reroute();
>      // ارائه را ذخیره می‌کند
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) کانکتور برای افزودن. |
| x | float | مختصات x چارچوب کانکتور، به پوینت. |
| y | float | مختصات y چارچوب کانکتور، به پوینت. |
| width | float | عرض چارچوب کانکتور، به پوینت. |
| height | float | ارتفاع چارچوب کانکتور، به پوینت. |

**خروجی:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) جدیداً ایجاد شده.

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

یک شکل کانکتور جدید ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌کند، به‌صورت اختیاری با اعمال سبک قالب پیش‌فرض.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) کانکتور برای ایجاد. |
| x | float | مختصات x چارچوب کانکتور، به پوینت. |
| y | float | مختصات y چارچوب کانکتور، به پوینت. |
| width | float | عرض چارچوب کانکتور، به پوینت. |
| height | float | ارتفاع چارچوب کانکتور، به پوینت. |
| createFromTemplate | boolean | True برای اعمال سبک قالب پیش‌فرض (نام غیر خالی، سبک ساده)؛ false برای ایجاد کانکتور با مقادیر پیش‌فرض خصوصیات. |

**خروجی:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) جدیداً ایجاد شده.

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

یک شکل کانکتور جدید ایجاد می‌کند و آن را در ایندکس مشخص‌شده به مجموعه شکل‌ها وارد می‌کند، با اعمال سبک قالب پیش‌فرض.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که کانکتور در آن وارد می‌شود. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) کانکتور برای وارد کردن. |
| x | float | مختصات x چارچوب کانکتور، به پوینت. |
| y | float | مختصات y چارچوب کانکتور، به پوینت. |
| width | float | عرض چارچوب کانکتور، به پوینت. |
| height | float | ارتفاع چارچوب کانکتور، به پوینت. |

**خروجی:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) جدیداً ایجاد شده.

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

یک شکل کانکتور جدید ایجاد می‌کند و آن را در ایندکس مشخص‌شده به مجموعه شکل‌ها وارد می‌کند، به‌صورت اختیاری با اعمال سبک قالب پیش‌فرض.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که کانکتور در آن وارد می‌شود. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) کانکتور برای وارد کردن. |
| x | float | مختصات x چارچوب کانکتور، به پوینت. |
| y | float | مختصات y چارچوب کانکتور، به پوینت. |
| width | float | عرض چارچوب کانکتور، به پوینت. |
| height | float | ارتفاع چارچوب کانکتور، به پوینت. |
| createFromTemplate | boolean | True برای اعمال سبک قالب پیش‌فرض (نام غیر خالی، سبک ساده)؛ false برای ایجاد کانکتور با مقادیر پیش‌فرض خصوصیات. |

**خروجی:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) جدیداً ایجاد شده.

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

یک فریم تصویر جدید شامل تصویر مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | int | نوع شکل موجود در [ShapeType](../../com.aspose.slides/shapetype) را تعیین می‌کند، به‌جز تمام انواع خطوط: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | مختصات x فریم تصویر، به پوینت. |
| y | float | مختصات y فریم تصویر، به پوینت. |
| width | float | عرض فریم تصویر، به پوینت. |
| height | float | ارتفاع فریم تصویر، به پوینت. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) برای نمایش در فریم تصویر. |

**خروجی:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) جدیداً ایجاد شده.

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

یک فریم تصویر جدید شامل تصویر مشخص‌شده ایجاد می‌کند و آن را در ایندکس مشخص‌شده به مجموعه شکل‌ها وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که فریم تصویر در آن وارد می‌شود. |
| shapeType | int | نوع شکل موجود در [ShapeType](../../com.aspose.slides/shapetype) را تعیین می‌کند، به‌جز تمام انواع خطوط: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | مختصات x فریم تصویر، به پوینت. |
| y | float | مختصات y فریم تصویر، به پوینت. |
| width | float | عرض فریم تصویر، به پوینت. |
| height | float | ارتفاع فریم تصویر، به پوینت. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) برای نمایش در فریم تصویر. |

**خروجی:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) جدیداً ایجاد شده.

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

یک جدول جدید ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌نماید.

--------------------

> ```
> مثال‌های زیر نشان می‌دهد چگونه جدول را در ارائه PowerPoint اضافه کنیم.
>  
>  // یک نمونه از کلاس Presentation ایجاد می‌کند که نمایانگر فایل PPTX است
>  Presentation pres = new Presentation();
>  try
>  {
>      // به اسلاید اول دسترسی می‌یابد
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // تعیین ستون‌ها با عرض و ردیف‌ها با ارتفاع
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // افزودن شکل جدول به اسلاید
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // تنظیم فرمت حاشیه برای هر سلول
>      for (int row = 0; row < tbl.getRows().size(); row++)
>      {
>          for (int cell = 0; cell < tbl.getRows().get_Item(row).size(); cell++)
>          {
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().setFillType((FillType.Solid));
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().setWidth(5);
>          }
>      }
>      // ترکیب سلول‌های 1 و 2 از ردیف 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // افزودن متن به سلول ترکیب شده
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // ذخیره PPTX بر روی دیسک
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x جدول، به پوینت. |
| y | float | مختصات y جدول، به پوینت. |
| columnWidths | double[] | آرایه‌ای از double‌ها که عرض ستون‌های جدول را نشان می‌دهد، به پوینت. |
| rowHeights | double[] | آرایه‌ای از double‌ها که ارتفاع ردیف‌های جدول را نشان می‌دهد، به پوینت. |

**بازگشت:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) جدید ایجاد شده.

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

یک جدول جدید می‌سازد و آن را در مجموعه اشکال در شاخص مشخص‌شده قرار می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر-مبنا که جدول در آن درج می‌شود. |
| x | float | مختصات x جدول، به پوینت. |
| y | float | مختصات y جدول، به پوینت. |
| columnWidths | double[] | آرایه‌ای از double‌ها که عرض ستون‌های جدول را نشان می‌دهد، به پوینت. |
| rowHeights | double[] | آرایه‌ای از double‌ها که ارتفاع ردیف‌های جدول را نشان می‌دهد، به پوینت. |

**بازگشت:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) جدید ایجاد شده.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

شکل موجود در شاخص مشخص‌شده را از مجموعه اشکال حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر-مبنا برای شکل مورد حذف. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

اولین رخداد شکل مشخص‌شده را از مجموعه اشکال حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای حذف. |

### clear() {#clear--}
```
public final void clear()
```

تمام اشکال را از مجموعه اشکال حذف می‌کند.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

یک enumerator برمی‌گرداند که بر روی مجموعه پیمایش می‌کند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - یک IGenericEnumerator که می‌توان برای پیمایش مجموعه استفاده کرد.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - یک java.util.Iterator برای کل مجموعه.

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

شیء شکل گروه والد برای مجموعه اشکال را دریافت می‌کند. فقط-خواندنی [IGroupShape](../../com.aspose.slides/igroupshape).

**بازگشت:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

یک نسخه از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | شکل برای کلون کردن. |
| x | float | مختصات x فریم شکل جدید، به پوینت. |
| y | float | مختصات y فریم شکل جدید، به پوینت. |
| width | float | عرض فریم شکل جدید، به پوینت. |
| height | float | ارتفاع فریم شکل جدید، به پوینت. |

**بازگشت:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) جدید ایجاد شده.

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

یک نسخه از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. شکل جدید عرض و ارتفاع shape منبع را حفظ می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | شکل برای کلون کردن. |
| x | float | مختصات x فریم شکل جدید، به پوینت. |
| y | float | مختصات y فریم شکل جدید، به پوینت. |

**بازگشت:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) جدید ایجاد شده.

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

یک نسخه از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. شکل کلون‌شده موقعیت و اندازه اصلی را حفظ می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون کردن. |

**بازگشت:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) جدید ایجاد شده.

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

یک نسخه از شکل مشخص‌شده ایجاد می‌کند و آن را در مجموعه اشکال در شاخص مشخص‌شده وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر-مبنا که شکل کلون‌شده در آن درج می‌شود. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون کردن. |
| x | float | مختصات x فریم شکل کلون‌شده، به پوینت. |
| y | float | مختصات y فریم شکل کلون‌شده، به پوینت. |
| width | float | عرض فریم شکل کلون‌شده، به پوینت. |
| height | float | ارتفاع فریم شکل کلون‌شده، به پوینت. |

**بازگشت:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) جدید ایجاد شده.

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

یک نسخه از شکل مشخص‌شده ایجاد می‌کند و آن را در مجموعه اشکال در شاخص مشخص‌شده وارد می‌کند. شکل جدید عرض و ارتفاع shape منبع را حفظ می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر-مبنا که شکل کلون‌شده در آن درج می‌شود. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون کردن. |
| x | float | مختصات x فریم شکل کلون‌شده، به پوینت. |
| y | float | مختصات y فریم شکل کلون‌شده، به پوینت. |

**بازگشت:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) جدید ایجاد شده.

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

یک نسخه از شکل مشخص‌شده ایجاد می‌کند و آن را در مجموعه اشکال در شاخص مشخص‌شده وارد می‌کند. شکل کلون‌شده موقعیت و اندازه اصلی را حفظ می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر-مبنا که شکل کلون‌شده در آن درج می‌شود. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون کردن. |

**بازگشت:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) جدید ایجاد شده.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر مجموعه را در آرایه هدف کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | شاخص شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه هماهنگ (thread-safe) است یا نه. فقط-خواندنی boolean .

**بازگشت:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشه‌ی همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object .

**بازگشت:**
java.lang.Object