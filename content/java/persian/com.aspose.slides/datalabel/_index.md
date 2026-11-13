---
title: DataLabel
second_title: مرجع API Aspose.Slides برای Java
description: نماینده برچسب‌های یک سری.
type: docs
url: /fa/com.aspose.slides/datalabel/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

برچسب‌های یک سری را نمایش می‌دهد.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | یک نمونه جدید از کلاس DataLabel ایجاد می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | نمودار والد را برمی‌گرداند. |
| [isVisible()](#isVisible--) | مقدار False به این معناست که برچسب داده قابل مشاهده نیست (و بنابراین همه پرچم‌های Show* (ShowValue, …) برابر False هستند). |
| [hide()](#hide--) | برچسب داده را با تنظیم تمام پرچم‌های Show* (ShowValue, …) به وضعیت false مخفی می‌کند. |
| [getActualLabelText()](#getActualLabelText--) | متن واقعی برچسب را بر اساس تنظیمات DataLabelFormat یا مقدار TextFrameForOverriding.Text برمی‌گرداند. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | TextFrameForOverriding را با متنی که در پارامتر "text" آمده، مقداردهی اولیه می‌کند. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | می‌تواند حاوی متن قالب‌بندی شده غنی باشد. |
| [getTextFormat()](#getTextFormat--) | قالب متن را برمی‌گرداند. |
| [getX()](#getX--) | مختصات x عنوان را به عنوان بخشی از عرض نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [setX(float value)](#setX-float-) | مختصات x عنوان را به عنوان بخشی از عرض نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [getY()](#getY--) | مختصات y عنوان را به عنوان بخشی از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [setY(float value)](#setY-float-) | مختصات y عنوان را به عنوان بخشی از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [getWidth()](#getWidth--) | عرض عنوان را به عنوان بخشی از عرض نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [setWidth(float value)](#setWidth-float-) | عرض عنوان را به عنوان بخشی از عرض نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [getHeight()](#getHeight--) | ارتفاع عنوان را به عنوان بخشی از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [setHeight(float value)](#setHeight-float-) | ارتفاع عنوان را به عنوان بخشی از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [getRight()](#getRight--) | راست. |
| [getBottom()](#getBottom--) | پایین. |
| [getDataLabelFormat()](#getDataLabelFormat--) | قالب برچسب داده را برمی‌گرداند. |
| [getValueFromCell()](#getValueFromCell--) | سلول داده کتاب کار را می‌گیرد یا تنظیم می‌کند. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | سلول داده کتاب کار را می‌گیرد یا تنظیم می‌کند. |
| [getLabelShapeType()](#getLabelShapeType--) | نوع شکل برچسب داده را می‌گیرد یا تنظیم می‌کند. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | نوع شکل برچسب داده را می‌گیرد یا تنظیم می‌کند. |
| [getActualX()](#getActualX--) | موقعیت واقعی x (چپ) عنصر نمودار را نسبت به گوشه بالای چپ نمودار مشخص می‌کند. |
| [getActualY()](#getActualY--) | بالای واقعی عنصر نمودار را نسبت به گوشه بالای چپ نمودار مشخص می‌کند. |
| [getActualWidth()](#getActualWidth--) | عرض واقعی عنصر نمودار را مشخص می‌کند. |
| [getActualHeight()](#getActualHeight--) | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد FillFormat را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه والد FillFormat را برمی‌گرداند. |

### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

یک نمونه جدید از کلاس DataLabel ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ChartDataPoint والد. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**برمی‌گرداند:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

نمودار والد را برمی‌گرداند. فقط-خواندنی [IChart](../../com.aspose.slides/ichart).

**برمی‌گرداند:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

مقدار False به این معناست که برچسب داده قابل مشاهده نیست (و بنابراین همه پرچم‌های Show* (ShowValue, …) برابر False هستند). فقط-خواندنی boolean .

--------------------

اگر برچسب داده قابل مشاهده باشد می‌توانید با متد Hide() آن را مخفی کنید. اما اگر برچسب داده قابل مشاهده نیست (IsVisible مقدار false است) می‌توانید با تنظیم پرچم‌های Show* (ShowValue, …) به وضعیت true آن را قابل مشاهده کنید.

**برمی‌گرداند:**
boolean

### hide() {#hide--}
```
public final void hide()
```

برچسب داده را با تنظیم تمام پرچم‌های Show* (ShowValue, …) به وضعیت false مخفی می‌کند. پس از این IsVisible مقدار false خواهد داشت.

--------------------

اگر برچسب داده قابل مشاهده نیست (IsVisible مقدار false) می‌توانید با تنظیم پرچم‌های Show* (ShowValue, …) به وضعیت true آن را قابل مشاهده کنید.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

متن واقعی برچسب را بر اساس تنظیمات DataLabelFormat یا مقدار TextFrameForOverriding.Text برمی‌گرداند.

**برمی‌گرداند:**
java.lang.String - شیء java.lang.String.

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

TextFrameForOverriding را با متنی که در پارامتر "text" آمده، مقداردهی اولیه می‌کند. اگر TextFrameForOverriding قبلاً مقداردهی شده باشد به سادگی متن آن را تغییر می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن برای یک TextFrameForOverriding جدید. |

**برمی‌گرداند:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

می‌تواند حاوی متن قالب‌بندی شده غنی باشد. اگر این ویژگی null نباشد، این مقدار متنی قالب‌بندی شده متن تولید خودکار برچسب داده را بازنویسی می‌کند. متن تولید خودکار برچسب داده به متنی گفته می‌شود که توسط ویژگی‌های ShowSeriesName، ShowValue، … مدیریت می‌شود و با ویژگی TextFormatManager.TextFormat قالب‌بندی می‌شود. فقط-خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**برمی‌گرداند:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

قالب متن را برمی‌گرداند. فقط-خواندنی [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**برمی‌گرداند:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getX() {#getX--}
```
public final float getX()
```

مختصات x عنوان را به عنوان بخشی از عرض نمودار برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float .

**برمی‌گرداند:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

مختصات x عنوان را به عنوان بخشی از عرض نمودار برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

مختصات y عنوان را به عنوان بخشی از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float .

**برمی‌گرداند:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

مختصات y عنوان را به عنوان بخشی از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

عرض عنوان را به عنوان بخشی از عرض نمودار برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float .

**برمی‌گرداند:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

عرض عنوان را به عنوان بخشی از عرض نمودار برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

ارتفاع عنوان را به عنوان بخشی از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float .

**برمی‌گرداند:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

ارتفاع عنوان را به عنوان بخشی از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

راست. فقط-خواندنی float .

**برمی‌گرداند:**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

پایین. فقط-خواندنی float .

**برمی‌گرداند:**
float

### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

قالب برچسب داده را برمی‌گرداند. فقط-خواندنی [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**برمی‌گرداند:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

سلول داده کتاب کار را می‌گیرد یا تنظیم می‌کند. هنگامی که ویژگی IDataLabelFormat.ShowLabelValueFromCell مقدار true داشته باشد اعمال می‌شود.

**برمی‌گرداند:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

سلول داده کتاب کار را می‌گیرد یا تنظیم می‌کند. هنگامی که ویژگی IDataLabelFormat.ShowLabelValueFromCell مقدار true داشته باشد اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```

نوع شکل برچسب داده را می‌گیرد یا تنظیم می‌کند. اگر هیچ شکلی تعریف نشده باشد [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) برگردانده می‌شود.

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // نوع شکل اولین برچسب داده را به بیضی تنظیم کنید.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**برمی‌گرداند:**
int

### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public final void setLabelShapeType(int value)
```

نوع شکل برچسب داده را می‌گیرد یا تنظیم می‌کند. اگر هیچ شکلی تعریف نشده باشد [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) برگردانده می‌شود.

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // نوع شکل اولین برچسب داده را به بیضی تنظیم کنید.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

موقعیت واقعی x (چپ) عنصر نمودار را نسبت به گوشه بالای چپ نمودار مشخص می‌کند. پیش از دریافت مقادیر واقعی متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط-خواندنی float.

**برمی‌گرداند:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

بالای واقعی عنصر نمودار را نسبت به گوشه بالای چپ نمودار مشخص می‌کند. پیش از دریافت مقادیر واقعی متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط-خواندنی float.

**برمی‌گرداند:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

عرض واقعی عنصر نمودار را مشخص می‌کند. پیش از دریافت مقادیر واقعی متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط-خواندنی float.

**برمی‌گرداند:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

ارتفاع واقعی عنصر نمودار را مشخص می‌کند. پیش از دریافت مقادیر واقعی متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط-خواندنی float.

**برمی‌گرداند:**
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد FillFormat را برمی‌گرداند. فقط-خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**برمی‌گرداند:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه والد FillFormat را برمی‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**برمی‌گرداند:**
[IPresentation](../../com.aspose.slides/ipresentation)