---
title: IDataLabel
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر برچسب‌های یک سری است.
type: docs
url: /fa/com.aspose.slides/idatalabel/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

نمایانگر برچسب‌های یک سری است.

## متدها

| متد | توضیح |
| --- | --- |
| [isVisible()](#isVisible--) | False به این معنی است که برچسب داده قابل مشاهده نیست (و همه پرچم‌های Show* (ShowValue, ...) نیز false هستند). |
| [hide()](#hide--) | برچسب داده را با تنظیم همه پرچم‌های Show* (ShowValue, ...) به حالت false مخفی کنید. |
| [getDataLabelFormat()](#getDataLabelFormat--) | قالب برچسب داده را برمی‌گرداند. |
| [getValueFromCell()](#getValueFromCell--) | سلول دادهٔ کتاب‌کار را دریافت یا تنظیم می‌کند. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | سلول دادهٔ کتاب‌کار را دریافت یا تنظیم می‌کند. |
| [getActualLabelText()](#getActualLabelText--) | متن واقعی برچسب را بر اساس تنظیمات DataLabelFormat یا مقدار TextFrameForOverriding.Text برمی‌گرداند. |
| [getLabelShapeType()](#getLabelShapeType--) | نوع شکل برچسب داده را دریافت یا تنظیم می‌کند. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | نوع شکل برچسب داده را دریافت یا تنظیم می‌کند. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False به این معنی است که برچسب داده قابل مشاهده نیست (و همه پرچم‌های Show* (ShowValue, ...) نیز false هستند). بولی فقط-خواندنی.

---

اگر برچسب داده قابل مشاهده باشد، می‌توانید با متد Hide() آن را مخفی کنید. اما اگر برچسب داده قابل مشاهده نباشد (IsVisible برابر false است) می‌توانید با تنظیم پرچم‌های Show* (ShowValue, ...) به حالت true، آن را قابل مشاهده کنید.

**باز می‌گردد:**
boolean

### hide() {#hide--}
```
public abstract void hide()
```

برچسب داده را با تنظیم همه پرچم‌های Show* (ShowValue, ...) به حالت false مخفی کنید. پس از این IsVisible برابر false خواهد شد.

---

اگر برچسب داده قابل مشاهده نباشد (IsVisible برابر false است) می‌توانید با تنظیم پرچم‌های Show* (ShowValue, ...) به حالت true، آن را قابل مشاهده کنید.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

قالب برچسب داده را برمی‌گرداند. [IDataLabelFormat](../../com.aspose.slides/idatalabelformat) فقط-خواندنی.

**باز می‌گردد:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

سلول دادهٔ کتاب‌کار را دریافت یا تنظیم می‌کند. در صورتی که ویژگی IDataLabelFormat.ShowLabelValueFromCell برابر true باشد اعمال می‌شود.

**باز می‌گردد:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

سلول دادهٔ کتاب‌کار را دریافت یا تنظیم می‌کند. در صورتی که ویژگی IDataLabelFormat.ShowLabelValueFromCell برابر true باشد اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

متن واقعی برچسب را بر اساس تنظیمات DataLabelFormat یا مقدار TextFrameForOverriding.Text برمی‌گرداند.

**باز می‌گردد:**
java.lang.String - رشتهٔ متن برچسب واقعی

### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

نوع شکل برچسب داده را دریافت یا تنظیم می‌کند. اگر شکلی تعریف نشده باشد [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) را برمی‌گرداند.

---

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

**باز می‌گردد:**
int

### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

نوع شکل برچسب داده را دریافت یا تنظیم می‌کند. اگر شکلی تعریف نشده باشد [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) را برمی‌گرداند.

---

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      //      نوع شکل اولین برچسب داده را به بیضی تنظیم کنید.
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