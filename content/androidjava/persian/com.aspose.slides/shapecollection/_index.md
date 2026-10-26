---
title: ShapeCollection
second_title: مرجع API جاوا برای Aspose.Slides بر روی اندروید
description: نمایش‌دهندهٔ مجموعه‌ای از اشکال.
type: docs
url: /fa/com.aspose.slides/shapecollection/
---
**وراثت:**  
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)  
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

نمایش‌دهنده یک مجموعه از اشکال.  
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد عناصری که در واقع در مجموعه موجود است را دریافت می‌کند. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در اندیس مشخص‌شده را دریافت می‌کند. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | یک chart جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند، و به انتهای shape collection اضافه می‌شود. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | یک chart جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند، و به انتهای shape collection اضافه می‌شود. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | یک SmartArt diagram جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | یک chart جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند، و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | یک chart جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند، و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | یک Zoom frame جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | یک Zoom frame جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | یک Zoom frame جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | یک Zoom frame جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | یک Section Zoom frame جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | یک Section Zoom frame جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | یک Section Zoom frame جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | یک Section Zoom frame جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | یک Summary Zoom frame جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | یک Summary Zoom frame جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | یک OLE object frame جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | یک OLE object frame جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | یک OLE object frame جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | یک OLE object frame جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | یک video frame جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | یک video frame جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | یک video frame جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | یک audio frame مرتبط با یک ترک CD جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | یک audio frame مرتبط با یک ترک CD جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | یک audio frame مرتبط با یک فایل صوتی خارجی جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | یک audio frame مرتبط با یک فایل صوتی خارجی جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | یک audio frame با فایل WAV جاسازی‌شده جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | یک audio frame با فایل WAV جاسازی‌شده جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | یک audio frame جدید ایجاد می‌کند و با استفاده از شی audio موجود در لیست Presentation.Audios به انتهای shape collection اضافه می‌شود. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | یک audio frame جدید ایجاد می‌کند و با استفاده از شی audio موجود در لیست Presentation.Audios در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | اندیس صفر-پایهٔ اولین رخداد shape مشخص‌شده در مجموعه را بر می‌گرداند. |
| [toArray()](#toArray--) | یک آرایه ایجاد می‌کند و تمام shapeها را در بر می‌گیرد. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | یک آرایه ایجاد می‌کند و تمام shapeها را در بازهٔ مشخص‌شده در بر می‌گیرد. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | shape مشخص‌شده را به موقعیت جدیدی درون shape collection منتقل می‌کند. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | shapes مشخص‌شده را درون shape collection جابه‌جا می‌کند، به‌طوری‌که از اندیس داده‌شده شروع می‌شود. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | یک auto shape جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | یک auto shape جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌کند، به‌صورت اختیاری با قالب‌بندی پیش‌فرض قالب را مقداردهی اولیه می‌کند. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | یک rectangle auto shape جدید برای میزبانی محتوای ریاضی ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | یک auto shape جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند، قالب پیش‌فرض الگو را اعمال می‌کند. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | یک auto shape جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند، به‌صورت اختیاری با استایل پیش‌فرض الگو مقداردهی اولیه می‌کند. |
| [addGroupShape()](#addGroupShape--) | یک group shape خالی جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | یک group shape جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به اشکال فردی تبدیل می‌کند، و گروه حاصل را به انتهای shape collection اضافه می‌کند. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | یک group shape خالی جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | یک connector shape جدید با استایل پیش‌فرض الگو ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | یک connector shape جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌کند، به‌صورت اختیاری استایل پیش‌فرض الگو را اعمال می‌کند. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | یک connector shape جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند، استایل پیش‌فرض الگو را اعمال می‌کند. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | یک connector shape جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند، به‌صورت اختیاری استایل پیش‌فرض الگو را اعمال می‌کند. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | یک picture frame جدید شامل تصویر مشخص‌شده ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | یک picture frame جدید شامل تصویر مشخص‌شده ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | یک table جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | یک table جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [removeAt(int index)](#removeAt-int-) | shape موجود در اندیس مشخص‌شده را از shape collection حذف می‌کند. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | اولین رخداد shape مشخص‌شده را از shape collection حذف می‌کند. |
| [clear()](#clear--) | تمام shapeها را از shape collection حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator برمی‌گرداند که مجموعه را پیمایش می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه برمی‌گرداند. |
| [getParentGroup()](#getParentGroup--) | شیء parent group shape مربوط به مجموعهٔ shapeها را دریافت می‌کند. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | یک کپی از shape مشخص‌شده ایجاد می‌کند و به انتهای shape collection اضافه می‌کند. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | یک کپی از shape مشخص‌شده ایجاد می‌کند و به انتهای shape collection اضافه می‌کند. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | یک کپی از shape مشخص‌شده ایجاد می‌کند و به انتهای shape collection اضافه می‌کند. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | یک کپی از shape مشخص‌شده ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | یک کپی از shape مشخص‌شده ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | یک کپی از shape مشخص‌شده ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقدار نشان‌دهندهٔ این که دسترسی به مجموعه همگام‌سازی شده ( thread-safe ) است را بر می‌گرداند. فقط-خواندنی  boolean . |
| [getSyncRoot()](#getSyncRoot--) | یک synchronization root برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```

تعداد عناصری که در واقع در مجموعه موجود است را دریافت می‌کند. فقط-خواندنی  int .

**Returns:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

عنصر موجود در اندیس مشخص‌شده را دریافت می‌کند. فقط-خواندنی [IShape](../../com.aspose.slides/ishape).

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**Returns:**  
[IShape](../../com.aspose.slides/ishape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

یک chart جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند، و به انتهای shape collection اضافه می‌شود.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه یک Chart در ارائهٔ PowerPoint ایجاد شود.
>  
>  // یک نمونه از کلاس Presentation را ایجاد می‌کند که نمایانگر یک فایل PPTX است
>  Presentation pres = new Presentation();
>  try {
>      // به اولین اسلاید دسترسی می‌یابد
>      ISlide sld = pres.getSlides().get_Item(0);
>      // یک نمودار با داده‌های پیش‌فرض آن اضافه می‌کند
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // عنوان نمودار را تنظیم می‌کند
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // اولین سری را طوری تنظیم می‌کند که مقدارها را نشان دهد
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // اندیس شیت داده‌های نمودار را تنظیم می‌کند
>      int defaultWorksheetIndex = 0;
>      // شیت کار داده‌های نمودار را دریافت می‌کند
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // سری‌ها و دسته‌بندی‌های پیش‌فرض تولید شده را حذف می‌کند
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // سری‌های جدید را اضافه می‌کند
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // دسته‌بندی‌های جدید را اضافه می‌کند
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // سری اول نمودار را می‌گیرد
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // داده‌های سری را پر می‌کند
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // رنگ پر کردن برای سری را تنظیم می‌کند
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // سری دوم نمودار را می‌گیرد
>      series = chart.getChartData().getSeries().get_Item(1);
>      // داده‌های سری را پر می‌کند
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // رنگ پر کردن برای سری را تنظیم می‌کند
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // اولین برچسب را طوری تنظیم می‌کند که نام دسته‌بندی را نشان دهد
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // سری را طوری تنظیم می‌کند که مقدار را برای برچسب سوم نشان دهد
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // فایل PPTX را در دیسک ذخیره می‌کند
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع chart برای افزودن. |
| x | float | مختصات x chart جدید، بر حسب points. |
| y | float | مختصات y chart جدید، بر حسب points. |
| width | float | عرض chart، بر حسب points. |
| height | float | ارتفاع chart، بر حسب points. |

**Returns:**  
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) تازه ایجاد شده.
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

یک chart جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند، و به انتهای shape collection اضافه می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع chart برای افزودن. |
| x | float | مختصات x chart جدید، بر حسب points. |
| y | float | مختصات y chart جدید، بر حسب points. |
| width | float | عرض chart، بر حسب points. |
| height | float | ارتفاع chart، بر حسب points. |
| initWithSample | boolean | true برای مقداردهی اولیه chart با داده‌های نمونه سری و تنظیمات؛ false برای ایجاد chart بدون سری و فقط تنظیمات حداقل، که ساخت آن سریع‌تر می‌شود. |

**Returns:**  
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) تازه ایجاد شده.
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

یک نمودار SmartArt جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه یک SmartArt در ارائهٔ PowerPoint اضافه شود.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x چارچوب نمودار، بر حسب points. |
| y | float | مختصات y چارچوب نمودار، بر حسب points. |
| width | float | عرض چارچوب نمودار، بر حسب points. |
| height | float | ارتفاع چارچوب نمودار، بر حسب points. |
| layoutType | int | نوع layout SmartArt. |

**Returns:**  
[ISmartArt](../../com.aspose.slides/ismartart) - [ISmartArt](../../com.aspose.slides/ismartart) تازه ایجاد شده.
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

یک chart جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند، و در اندیس مشخص‌شده به shape collection وارد می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع chart برای ایجاد. |
| x | float | مختصات x chart جدید، بر حسب points. |
| y | float | مختصات y chart جدید، بر حسب points. |
| width | float | عرض chart، بر حسب points. |
| height | float | ارتفاع chart، بر حسب points. |
| index | int | اندیس صفر-پایه‌ای که chart جدید در آن وارد می‌شود. |

**Returns:**  
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) تازه ایجاد شده.
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

یک chart جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند، و در اندیس مشخص‌شده به shape collection وارد می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع chart برای ایجاد. |
| x | float | مختصات x chart جدید، بر حسب points. |
| y | float | مختصات y chart جدید، بر حسب points. |
| width | float | عرض chart، بر حسب points. |
| height | float | ارتفاع chart، بر حسب points. |
| index | int | اندیس صفر-پایه‌ای که chart جدید در آن وارد می‌شود. |
| initWithSample | boolean | true برای مقداردهی اولیه chart با داده‌های نمونه سری و تنظیمات؛ false برای ایجاد chart بدون سری و فقط تنظیمات حداقل، که ساخت آن سریع‌تر می‌شود. |

**Returns:**  
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) تازه ایجاد شده.
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

یک Zoom frame جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

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

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x Zoom frame جدید، بر حسب points. |
| y | float | مختصات y Zoom frame جدید، بر حسب points. |
| width | float | عرض Zoom frame جدید، بر حسب points. |
| height | float | ارتفاع Zoom frame جدید، بر حسب points. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) مرتبط با Zoom frame؛ باید متعلق به این ارائه باشد. |

**Returns:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) تازه ایجاد شده.
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

یک Zoom frame جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x Zoom frame جدید، بر حسب points. |
| y | float | مختصات y Zoom frame جدید، بر حسب points. |
| width | float | عرض Zoom frame جدید، بر حسب points. |
| height | float | ارتفاع Zoom frame جدید، بر حسب points. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) مرتبط با Zoom frame؛ باید متعلق به این ارائه باشد. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | تصویر برای اسلاید مرتبط [IPPImage](../../com.aspose.slides/ippimage). |

**Returns:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) تازه ایجاد شده.
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

یک Zoom frame جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند.

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


**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که Zoom frame در آن وارد می‌شود. |
| x | float | مختصات x Zoom frame جدید، بر حسب points. |
| y | float | مختصات y Zoom frame جدید، بر حسب points. |
| width | float | عرض Zoom frame جدید، بر حسب points. |
| height | float | ارتفاع Zoom frame جدید، بر حسب points. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) مرتبط با Zoom frame. |

**Returns:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) تازه ایجاد شده.
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

یک Zoom frame جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند.

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که Zoom frame در آن وارد می‌شود. |
| x | float | مختصات x Zoom frame جدید، بر حسب points. |
| y | float | مختصات y Zoom frame جدید، بر حسب points. |
| width | float | عرض Zoom frame جدید، بر حسب points. |
| height | float | ارتفاع Zoom frame جدید، بر حسب points. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) مرتبط با Zoom frame. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | تصویر برای اسلاید مرتبط [IPPImage](../../com.aspose.slides/ippimage). |

**Returns:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) تازه ایجاد شده.
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

یک Section Zoom frame جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x Section Zoom frame جدید، بر حسب points. |
| y | float | مختصات y Section Zoom frame جدید، بر حسب points. |
| width | float | عرض Section Zoom frame جدید، بر حسب points. |
| height | float | ارتفاع Section Zoom frame جدید، بر حسب points. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) مرتبط با Section Zoom frame؛ باید متعلق به این ارائه باشد و حداقل یک اسلاید داشته باشد. |

**Returns:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) تازه ایجاد شده.
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

یک Section Zoom frame جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x Section Zoom frame جدید، بر حسب points. |
| y | float | مختصات y Section Zoom frame جدید، بر حسب points. |
| width | float | عرض Section Zoom frame جدید، بر حسب points. |
| height | float | ارتفاع Section Zoom frame جدید، بر حسب points. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) مرتبط با Section Zoom frame؛ باید متعلق به این ارائه باشد و حداقل یک اسلاید داشته باشد. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) برای نمایش درون Section Zoom frame. |

**Returns:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) تازه ایجاد شده.
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

یک Section Zoom frame جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند.

--------------------

> ```
> This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که Section Zoom frame در آن وارد می‌شود. |
| x | float | مختصات x Section Zoom frame جدید، بر حسب points. |
| y | float | مختصات y Section Zoom frame جدید، بر حسب points. |
| width | float | عرض Section Zoom frame جدید، بر حسب points. |
| height | float | ارتفاع Section Zoom frame جدید، بر حسب points. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) مرتبط با Section Zoom frame؛ باید متعلق به این ارائه باشد و حداقل یک اسلاید داشته باشد. |

**Returns:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) تازه ایجاد شده.
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

یک Section Zoom frame جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند.

--------------------

> ```
> این مثال نشان می‌دهد ایجاد و درج یک شی Section Zoom در اندیس مشخص شدهٔ یک مجموعه
>  (فرض کنید در ارائهٔ "Presentation.pptx" حداقل دو بخش وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که Section Zoom frame در آن وارد می‌شود. |
| x | float | مختصات x Section Zoom frame جدید، بر حسب points. |
| y | float | مختصات y Section Zoom frame جدید، بر حسب points. |
| width | float | عرض Section Zoom frame جدید، بر حسب points. |
| height | float | ارتفاع Section Zoom frame جدید، بر حسب points. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) مرتبط با Section Zoom frame؛ باید متعلق به این ارائه باشد و حداقل یک اسلاید داشته باشد. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | تصویر برای نمایش درون Section Zoom frame. |

**Returns:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) تازه ایجاد شده.
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

یک Summary Zoom frame جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

--------------------

> ```
> This example demonstrates adding a Summary Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x Summary Zoom frame جدید، بر حسب points. |
| y | float | مختصات y Summary Zoom frame جدید، بر حسب points. |
| width | float | عرض Summary Zoom frame جدید، بر حسب points. |
| height | float | ارتفاع Summary Zoom frame جدید، بر حسب points. |

--------------------

این متد یک Summary Zoom جدید ایجاد می‌کند و مجموعه‌ای از اشیاء را برای تمام بخش‌های این ارائه در آن قرار می‌دهد.  

**Returns:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) تازه ایجاد شده.
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

یک Summary Zoom frame جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند.

--------------------

> ```
> این مثال نشان می‌دهد ایجاد و درج یک شی Summary Zoom در اندیس مشخص شدهٔ یک مجموعه
>  (فرض کنید در ارائهٔ "Presentation.pptx" حداقل دو بخش وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که Summary Zoom frame در آن وارد می‌شود. |
| x | float | مختصات x Summary Zoom frame جدید، بر حسب points. |
| y | float | مختصات y Summary Zoom frame جدید، بر حسب points. |
| width | float | عرض Summary Zoom frame جدید، بر حسب points. |
| height | float | ارتفاع Summary Zoom frame جدید، بر حسب points. |

--------------------

این متد یک Summary Zoom frame ایجاد می‌کند که لینک‌های خلاصه برای تمام بخش‌های ارائه را تجمیع می‌کند.  

**Returns:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) تازه ایجاد شده.
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

یک OLE object frame جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

--------------------

> ```
> The following examples shows how to adding OLE Object Frames to Slides of PowerPoint Presentation.
>  
>  // یک شیء از کلاس Presentation ایجاد می‌کند که نمایانگر PPTX است
>  Presentation pres = new Presentation();
>  try
>  {
>      // به اولین اسلاید دسترسی می‌یابد
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // یک فایل سل را به‌صورت جریان بارگیری می‌کند
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
>      // یک شیء داده برای جاسازی ایجاد می‌کند
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // یک شکل Ole Object Frame اضافه می‌کند
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      //Write PPTX را بر روی دیسک می‌نویسد
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x OLE frame جدید، بر حسب points. |
| y | float | مختصات y OLE frame جدید، بر حسب points. |
| width | float | عرض OLE frame جدید، بر حسب points. |
| height | float | ارتفاع OLE frame جدید، بر حسب points. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | اطلاعات دربارهٔ داده‌های جاسازی‌شده OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returns:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) تازه ایجاد شده.
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

یک OLE object frame جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x OLE frame جدید، بر حسب points. |
| y | float | مختصات y OLE frame جدید، بر حسب points. |
| width | float | عرض OLE frame جدید، بر حسب points. |
| height | float | ارتفاع OLE frame جدید، بر حسب points. |
| className | java.lang.String | نام کلاس OLE object. |
| path | java.lang.String | مسیر به فایل مرتبط.

این مسیر به همان صورت در ارائه ذخیره می‌شود. اگر مسیر نسبی باشد، هنگام باز کردن ارائه از مسیر دیگری، فایل در دسترس نخواهد بود. |

**Returns:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) تازه ایجاد شده.
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

یک OLE object frame جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند.

--------------------

> ```
> این مثال نحوهٔ درج یک شیء OLE در اندیس دوم را نشان می‌دهد:
>  
>  byte[] fileData = ... // "test.zip"
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```


**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که OLE object frame در آن وارد می‌شود. |
| x | float | مختصات x OLE frame جدید، بر حسب points. |
| y | float | مختصات y OLE frame جدید، بر حسب points. |
| width | float | عرض OLE frame جدید، بر حسب points. |
| height | float | ارتفاع OLE frame جدید، بر حسب points. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | اطلاعات دربارهٔ داده‌های جاسازی‌شده OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returns:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) تازه ایجاد شده.
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

یک OLE object frame جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که OLE object frame در آن وارد می‌شود. |
| x | float | مختصات x OLE frame جدید، بر حسب points. |
| y | float | مختصات y OLE frame جدید، بر حسب points. |
| width | float | عرض OLE frame جدید، بر حسب points. |
| height | float | ارتفاع OLE frame جدید، بر حسب points. |
| className | java.lang.String | نام کلاس OLE object. |
| path | java.lang.String | مسیر به فایل مرتبط.

این مسیر به همان صورت در ارائه ذخیره می‌شود. اگر مسیر نسبی باشد، هنگام باز کردن ارائه از مسیر دیگری، فایل در دسترس نخواهد بود. |

**Returns:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - OLE object frame تازه ایجاد شده.
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

یک video frame جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x video frame جدید، بر حسب points. |
| y | float | مختصات y video frame جدید، بر حسب points. |
| width | float | عرض video frame جدید، بر حسب points. |
| height | float | ارتفاع video frame جدید، بر حسب points. |
| fname | java.lang.String | مسیر یا نام فایل ویدئویی برای جاسازی. |

**Returns:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) تازه ایجاد شده.
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

یک video frame جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x video frame جدید، بر حسب points. |
| y | float | مختصات y video frame جدید، بر حسب points. |
| width | float | عرض video frame جدید، بر حسب points. |
| height | float | ارتفاع video frame جدید، بر حسب points. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) برای جاسازی در video frame. |

**Returns:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) تازه ایجاد شده.
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

یک video frame جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که video frame در آن وارد می‌شود. |
| x | float | مختصات x video frame جدید، بر حسب points. |
| y | float | مختصات y video frame جدید، بر حسب points. |
| width | float | عرض video frame جدید، بر حسب points. |
| height | float | ارتفاع video frame جدید، بر حسب points. |
| fname | java.lang.String | مسیر یا نام فایل ویدئویی برای جاسازی. |

**Returns:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) تازه ایجاد شده.
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

یک audio frame جدید مرتبط با یک ترک CD ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x audio frame جدید، بر حسب points. |
| y | float | مختصات y audio frame جدید، بر حسب points. |
| width | float | عرض audio frame جدید، بر حسب points. |
| height | float | ارتفاع audio frame جدید، بر حسب points. |

**Returns:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه ایجاد شده.
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

یک audio frame جدید مرتبط با یک ترک CD ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که audio frame در آن وارد می‌شود. |
| x | float | مختصات x audio frame جدید، بر حسب points. |
| y | float | مختصات y audio frame جدید، بر حسب points. |
| width | float | عرض audio frame جدید، بر حسب points. |
| height | float | ارتفاع audio frame جدید، بر حسب points. |

**Returns:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه ایجاد شده.
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

یک audio frame جدید مرتبط با یک فایل صوتی خارجی ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x audio frame جدید، بر حسب points. |
| y | float | مختصات y audio frame جدید، بر حسب points. |
| width | float | عرض audio frame جدید، بر حسب points. |
| height | float | ارتفاع audio frame جدید، بر حسب points. |
| fname | java.lang.String | مسیر یا نام فایل صوتی خارجی برای لینک. |

**Returns:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه ایجاد شده.
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

یک audio frame جدید مرتبط با یک فایل صوتی خارجی ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که audio frame در آن وارد می‌شود. |
| x | float | مختصات x audio frame جدید، بر حسب points. |
| y | float | مختصات y audio frame جدید، بر حسب points. |
| width | float | عرض audio frame جدید، بر حسب points. |
| height | float | ارتفاع audio frame جدید، بر حسب points. |
| fname | java.lang.String | مسیر یا نام فایل صوتی خارجی برای لینک. |

**Returns:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه ایجاد شده.
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

یک audio frame جدید با فایل WAV جاسازی‌شده ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. audio جاسازی‌شده به مجموعهٔ Presentation.Audios افزوده می‌شود.

--------------------

> ```
> مثال‌های زیر نشان می‌دهند چگونه یک Audio Frame ایجاد شود.
>  
>  // یک شیء از کلاس Presentation را ایجاد می‌کند که نمایانگر یک فایل ارائه است
>  Presentation pres = new Presentation();
>  try {
>      // اسلاید اول را دریافت می‌کند
>      ISlide sld = pres.getSlides().get_Item(0);
>      // فایل صوتی wav را به صورت جریان بارگذاری می‌کند
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Audio Frame را اضافه می‌کند
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // حالت پخش و حجم صدا را تنظیم می‌کند
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // فایل PowerPoint را بر روی دیسک می‌نویسد
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x audio frame جدید، بر حسب points. |
| y | float | مختصات y audio frame جدید، بر حسب points. |
| width | float | عرض audio frame جدید، بر حسب points. |
| height | float | ارتفاع audio frame جدید، بر حسب points. |
| audio_stream | java.io.InputStream | جریان ورودی شامل داده‌های صوتی WAV برای جاسازی. |

**Returns:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه ایجاد شده.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

یک audio frame جدید با فایل WAV جاسازی‌شده ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. audio جاسازی‌شده به مجموعهٔ Presentation.Audios افزوده می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که audio frame در آن وارد می‌شود. |
| x | float | مختصات x audio frame جدید، بر حسب points. |
| y | float | مختصات y audio frame جدید، بر حسب points. |
| width | float | عرض audio frame جدید، بر حسب points. |
| height | float | ارتفاع audio frame جدید، بر حسب points. |
| audio_stream | java.io.InputStream | جریان ورودی شامل داده‌های صوتی WAV برای جاسازی. |

**Returns:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه ایجاد شده.
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

یک audio frame جدید ایجاد می‌کند و با استفاده از شی audio موجود در لیست Presentation.Audios به انتهای shape collection اضافه می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x audio frame جدید، بر حسب points. |
| y | float | مختصات y audio frame جدید، بر حسب points. |
| width | float | عرض audio frame جدید، بر حسب points. |
| height | float | ارتفاع audio frame جدید، بر حسب points. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | یک نمونهٔ [IAudio](../../com.aspose.slides/iaudio) از مجموعهٔ Presentation.Audios. |

**Returns:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه ایجاد شده.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

یک audio frame جدید ایجاد می‌کند و در اندیس مشخص‌شده با استفاده از شی audio موجود در لیست Presentation.Audios به shape collection وارد می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که audio frame در آن وارد می‌شود. |
| x | float | مختصات x audio frame جدید، بر حسب points. |
| y | float | مختصات y audio frame جدید، بر حسب points. |
| width | float | عرض audio frame جدید، بر حسب points. |
| height | float | ارتفاع audio frame جدید، بر حسب points. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | یک نمونهٔ [IAudio](../../com.aspose.slides/iaudio) از مجموعهٔ Presentation.Audios برای جاسازی. |

**Returns:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه ایجاد شده.
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

اندیس صفر-پایهٔ اولین رخداد shape مشخص‌شده در مجموعه را بر می‌گرداند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | shape مورد جستجو در مجموعه. |

**Returns:**  
int - اندیس صفر-پایهٔ اولین رخداد shape در shape collection اگر یافت شد؛ در غیر این صورت، \\u20131.
### toArray() {#toArray--}
```
public final IShape[] toArray()
```

یک آرایه ایجاد می‌کند و تمام shapeها را در بر می‌گیرد.

**Returns:**  
com.aspose.slides.IShape[] - آرایه‌ای از اشیاء [IShape](../../com.aspose.slides/ishape).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

یک آرایه ایجاد می‌کند و تمام shapeها را در بازهٔ مشخص‌شده در بر می‌گیرد.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | اندیس اولین shape برای برگرداندن. |
| count | int | تعداد shapeهایی که باید برگردانده شوند. |

**Returns:**  
com.aspose.slides.IShape[] - آرایه‌ای از اشیاء [IShape](../../com.aspose.slides/ishape).
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

shape مشخص‌شده را به موقعیت جدیدی درون shape collection منتقل می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس هدف صفر-پایه‌ای که shape در آن قرار می‌گیرد. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای جابجایی درون مجموعه. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

shapes مشخص‌شده را درون shape collection جابه‌جا می‌کند، به‌طوری‌که از اندیس داده‌شده شروع می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس هدف صفر-پایه‌ای که اولین shape مشخص‌شده در آن قرار می‌گیرد؛ shapeهای بعدی به ترتیب ارائه‌شده قرار می‌گیرند. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | یک یا چند نمونهٔ [IShape](../../com.aspose.slides/ishape) برای جابجایی در مجموعه. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

یک auto shape جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) auto shape برای افزودن. |
| x | float | مختصات x چارچوب shape، بر حسب points. |
| y | float | مختصات y چارچوب shape، بر حسب points. |
| width | float | عرض چارچوب shape، بر حسب points. |
| height | float | ارتفاع چارچوب shape، بر حسب points. |

**Returns:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) تازه ایجاد شده.
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

یک auto shape جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌کند، به‌صورت اختیاری با قالب‌بندی پیش‌فرض الگو مقداردهی اولیه می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) auto shape برای افزودن. |
| x | float | مختصات x چارچوب shape، بر حسب points. |
| y | float | مختصات y چارچوب shape، بر حسب points. |
| width | float | عرض چارچوب shape، بر حسب points. |
| height | float | ارتفاع چارچوب shape، بر حسب points. |
| createFromTemplate | boolean | true برای اعمال استایل پیش‌فرض الگو (سبک ساده، متن مرکزگذاری شده، نام غیرخالی) به shape جدید؛ false برای ایجاد shape با همهٔ خصوصیت‌ها به مقادیر پیش‌فرض. |

**Returns:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) تازه ایجاد شده.
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

یک rectangle auto shape جدید برای میزبانی محتوای ریاضی ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه معادلهٔ ریاضی را در ارائهٔ PowerPoint اضافه کنیم.
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


**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x چارچوب shape، بر حسب points. |
| y | float | مختصات y چارچوب shape، بر حسب points. |
| width | float | عرض چارچوب shape، بر حسب points. |
| height | float | ارتفاع چارچوب shape، بر حسب points. |

**Returns:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) تازه ایجاد شده.
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

یک auto shape جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند، قالب‌بندی پیش‌فرض الگو را اعمال می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که auto shape جدید در آن وارد می‌شود. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) auto shape برای ورود. |
| x | float | مختصات x چارچوب shape، بر حسب points. |
| y | float | مختصات y چارچوب shape، بر حسب points. |
| width | float | عرض چارچوب shape، بر حسب points. |
| height | float | ارتفاع چارچوب shape، بر حسب points. |

**Returns:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) تازه ایجاد شده.
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

یک auto shape جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند، به‌صورت اختیاری با استایل پیش‌فرض الگو مقداردهی اولیه می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که auto shape در آن وارد می‌شود. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) auto shape برای ورود. |
| x | float | مختصات x چارچوب shape، بر حسب points. |
| y | float | مختصات y چارچوب shape، بر حسب points. |
| width | float | عرض چارچوب shape، بر حسب points. |
| height | float | ارتفاع چارچوب shape، بر حسب points. |
| createFromTemplate | boolean | true برای اعمال استایل پیش‌فرض الگو (نام غیرخالی، سبک ساده، متن مرکزگذاری شده)؛ false برای ایجاد shape با تمام خصوصیت‌های پیش‌فرض. |

**Returns:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) تازه ایجاد شده.
### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

یک group shape خالی جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود. چارچوب گروه به‌صورت خودکار برای گنجاندن هر shape افزوده‌شده تنظیم می‌شود.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه یک group shape به اسلایدی از ارائهٔ PowerPoint اضافه شود.
>  
>  // یک شیء از کلاس Presentation ایجاد می‌کند
>  Presentation pres = new Presentation();
>  try {
>      // اولین اسلاید را دریافت می‌کند
>      ISlide sld = pres.getSlides().get_Item(0);
>      // دسترسی به مجموعهٔ شکل‌های اسلایدها
>      IShapeCollection slideShapes = sld.getShapes();
>      // افزودن یک group shape به اسلاید
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // افزودن اشکال داخل group shape اضافه‌شده
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // افزودن چارچوب group shape
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // نوشتن فایل PPTX بر روی دیسک
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) تازه ایجاد شده.
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

یک group shape جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به اشکال فردی تبدیل می‌کند، و گروه حاصل را به انتهای shape collection اضافه می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) حاوی محتوای برداری برای تبدیل به shapeها. |
| x | float | مختصات x چارچوب گروه، بر حسب points. |
| y | float | مختصات y چارچوب گروه، بر حسب points. |
| width | float | عرض چارچوب گروه، بر حسب points. |
| height | float | ارتفاع چارچوب گروه، بر حسب points. |

**Returns:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) تازه ایجاد شده.
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

یک group shape خالی جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. چارچوب گروه به‌صورت خودکار برای گنجاندن هر shape افزوده‌شده تنظیم می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که group shape در آن وارد می‌شود. |

**Returns:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) تازه ایجاد شده.
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

یک connector shape جدید با استایل پیش‌فرض الگو ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه یک connector (یک connector خمیده) بین دو شکل (یک بیضی و یک مستطیل) در ارائهٔ PowerPoint اضافه شود.
>  
>  // یک شیء از کلاس Presentation ایجاد می‌کند که نمایانگر یک فایل PPTX است
>  Presentation pres = new Presentation();
>  try {
>      // به مجموعهٔ شکل‌ها برای یک اسلاید خاص دسترسی پیدا می‌کند
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // یک autoshape بیضی اضافه می‌کند
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // یک autoshape مستطیل اضافه می‌کند
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // یک shape connector به مجموعهٔ شکل‌های اسلاید اضافه می‌کند
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // شکل‌ها را با استفاده از connector متصل می‌کند
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // فراخوانی reroute که مسیر کوتاه‌ترین خودکار بین شکل‌ها را تنظیم می‌کند
>      connector.reroute();
>      // ارائه را ذخیره می‌کند
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) connector shape برای افزودن. |
| x | float | مختصات x چارچوب connector، بر حسب points. |
| y | float | مختصات y چارچوب connector، بر حسب points. |
| width | float | عرض چارچوب connector، بر حسب points. |
| height | float | ارتفاع چارچوب connector، بر حسب points. |

**Returns:**  
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) تازه ایجاد شده.
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

یک connector shape جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌کند، به‌صورت اختیاری استایل پیش‌فرض الگو را اعمال می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) connector shape برای ایجاد. |
| x | float | مختصات x چارچوب connector، بر حسب points. |
| y | float | مختصات y چارچوب connector، بر حسب points. |
| width | float | عرض چارچوب connector، بر حسب points. |
| height | float | ارتفاع چارچوب connector، بر حسب points. |
| createFromTemplate | boolean | true برای اعمال استایل پیش‌فرض الگو (نام غیرخالی، سبک ساده)؛ false برای ایجاد connector با مقادیر پیش‌فرض. |

**Returns:**  
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) تازه ایجاد شده.
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

یک connector shape جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند، استایل پیش‌فرض الگو را اعمال می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که connector shape در آن وارد می‌شود. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) connector shape برای ورود. |
| x | float | مختصات x چارچوب connector، بر حسب points. |
| y | float | مختصات y چارچوب connector، بر حسب points. |
| width | float | عرض چارچوب connector، بر حسب points. |
| height | float | ارتفاع چارچوب connector، بر حسب points. |

**Returns:**  
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) تازه ایجاد شده.
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

یک connector shape جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند، به‌صورت اختیاری استایل پیش‌فرض الگو را اعمال می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که connector shape در آن وارد می‌شود. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) connector shape برای ورود. |
| x | float | مختصات x چارچوب connector، بر حسب points. |
| y | float | مختصات y چارچوب connector، بر حسب points. |
| width | float | عرض چارچوب connector، بر حسب points. |
| height | float | ارتفاع چارچوب connector، بر حسب points. |
| createFromTemplate | boolean | true برای اعمال استایل پیش‌فرض الگو (نام غیرخالی، سبک ساده)؛ false برای ایجاد connector با مقادیر پیش‌فرض. |

**Returns:**  
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) تازه ایجاد شده.
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

یک picture frame جدید شامل تصویر مشخص‌شده ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | int | نوع shape موجود در [ShapeType](../../com.aspose.slides/shapetype)، به‌جز تمام انواع خطوط:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | مختصات x picture frame، بر حسب points. |
| y | float | مختصات y picture frame، بر حسب points. |
| width | float | عرض picture frame، بر حسب points. |
| height | float | ارتفاع picture frame، برحسب points. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) برای نمایش در picture frame. |

**Returns:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) تازه ایجاد شده.
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

یک picture frame جدید شامل تصویر مشخص‌شده ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که picture frame در آن وارد می‌شود. |
| shapeType | int | نوع shape موجود در [ShapeType](../../com.aspose.slides/shapetype)، به‌جز تمام انواع خطوط:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | مختصات x picture frame، بر حسب points. |
| y | float | مختصات y picture frame، بر حسب points. |
| width | float | عرض picture frame، بر حسب points. |
| height | float | ارتفاع picture frame، بر حسب points. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) برای نمایش در picture frame. |

**Returns:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) تازه ایجاد شده.
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

یک table جدید ایجاد می‌کند و به انتهای shape collection اضافه می‌شود.

--------------------

> ```
> The following examples shows how to add table in PowerPoint Presentation.
>  
>  // یک شیء از کلاس Presentation ایجاد می‌کند که نمایانگر فایل PPTX است
>  Presentation pres = new Presentation();
>  try
>  {
>      // به اولین اسلاید دسترسی می‌یابد
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // ستون‌ها را با عرض‌ها و ردیف‌ها را با ارتفاع‌ها تعریف می‌کند
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // یک شکل جدول را به اسلاید اضافه می‌کند
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // قالب حاشیه را برای هر سلول تنظیم می‌کند
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
>      // سلول‌های ۱ و ۲ ردیف ۱ را ادغام می‌کند
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // متن را به سلول ادغام شده اضافه می‌کند
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // PPTX را روی دیسک ذخیره می‌کند
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x table، بر حسب points. |
| y | float | مختصات y table، بر حسب points. |
| columnWidths | double[] | آرایه‌ای از اعداد دوگانه که عرض ستون‌های table را نشان می‌دهد، بر حسب points. |
| rowHeights | double[] | آرایه‌ای از اعداد دوگانه که ارتفاع ردیف‌های table را نشان می‌دهد، بر حسب points. |

**Returns:**  
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) تازه ایجاد شده.
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

یک table جدید ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که table در آن وارد می‌شود. |
| x | float | مختصات x table، بر حسب points. |
| y | float | مختصات y table، بر حسب points. |
| columnWidths | double[] | آرایه‌ای از اعداد دوگانه که عرض ستون‌های table را نشان می‌دهد، بر حسب points. |
| rowHeights | double[] | آرایه‌ای از اعداد دوگانه که ارتفاع ردیف‌های table را نشان می‌دهد، بر حسب points. |

**Returns:**  
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) تازه ایجاد شده.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

shape موجود در اندیس مشخص‌شده را از shape collection حذف می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای shape برای حذف. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

اولین رخداد shape مشخص‌شده را از shape collection حذف می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای حذف. |

### clear() {#clear--}
```
public final void clear()
```

تمام shapeها را از shape collection حذف می‌کند.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

یک enumerator برمی‌گرداند که مجموعه را پیمایش می‌کند.

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - IGenericEnumeratorی که می‌توان برای پیمایش مجموعه استفاده کرد.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

یک java iterator برای کل مجموعه برمی‌گرداند.

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - java.util.Iterator برای کل مجموعه.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

شیء parent group shape مربوط به مجموعهٔ shapeها را دریافت می‌کند. فقط-خواندنی [IGroupShape](../../com.aspose.slides/igroupshape).

**Returns:**  
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

یک کپی از shape مشخص‌شده ایجاد می‌کند و به انتهای shape collection اضافه می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | shape برای کلون. |
| x | float | مختصات x چارچوب shape جدید، بر حسب points. |
| y | float | مختصات y چارچوب shape جدید، بر حسب points. |
| width | float | عرض چارچوب shape جدید، بر حسب points. |
| height | float | ارتفاع چارچوب shape جدید، بر حسب points. |

**Returns:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) تازه ایجاد شده.
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

یک کپی از shape مشخص‌شده ایجاد می‌کند و به انتهای shape collection اضافه می‌کند. shape جدید عرض و ارتفاع sourceShape را حفظ می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | shape برای کلون. |
| x | float | مختصات x چارچوب shape جدید، بر حسب points. |
| y | float | مختصات y چارچوب shape جدید، بر حسب points. |

**Returns:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) تازه ایجاد شده.
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

یک کپی از shape مشخص‌شده ایجاد می‌کند و به انتهای shape collection اضافه می‌کند. shape کلون شده موقعیت و اندازهٔ اصلی را حفظ می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون. |

**Returns:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) تازه ایجاد شده.
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

یک کپی از shape مشخص‌شده ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که shape کلون شده در آن وارد می‌شود. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون. |
| x | float | مختصات x چارچوب shape کلون شده، بر حسب points. |
| y | float | مختصات y چارچوب shape کلون شده، بر حسب points. |
| width | float | عرض چارچوب shape کلون شده، بر حسب points. |
| height | float | ارتفاع چارچوب shape کلون شده، بر حسب points. |

**Returns:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) تازه ایجاد شده.
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

یک کپی از shape مشخص‌شده ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. shape جدید عرض و ارتفاع sourceShape را حفظ می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که shape کلون شده در آن وارد می‌شود. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون. |
| x | float | مختصات x چارچوب shape کلون شده، بر حسب points. |
| y | float | مختصات y چارچوب shape کلون شده، بر حسب points. |

**Returns:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) تازه ایجاد شده.
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

یک کپی از shape مشخص‌شده ایجاد می‌کند و در اندیس مشخص‌شده به shape collection وارد می‌کند. shape کلون شده موقعیت و اندازهٔ اصلی را حفظ می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که shape کلون شده در آن وارد می‌شود. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون. |

**Returns:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) تازه ایجاد شده.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایهٔ هدف. |
| index | int | اندیس شروع در آرایهٔ هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقدار نشان‌دهندهٔ این که دسترسی به مجموعه همگام‌سازی شده ( thread-safe ) است را بر می‌گرداند. فقط-خواندنی  boolean .

**Returns:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک synchronization root برمی‌گرداند. فقط-خواندنی  Object .

**Returns:**  
java.lang.Object