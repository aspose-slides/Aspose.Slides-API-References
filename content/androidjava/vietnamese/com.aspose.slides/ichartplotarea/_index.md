---
title: IChartPlotArea
second_title: Aspose.Slides cho Android qua Tham khảo API Java
description: Biểu thị các thuộc tính tiêu đề biểu đồ.
type: docs
url: /vi/com.aspose.slides/ichartplotarea/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Biểu thị các thuộc tính tiêu đề biểu đồ.
## Phương thức

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Trả về định dạng của khu vực biểu đồ. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Nếu bố cục của khu vực biểu đồ được định nghĩa thủ công, thuộc tính này xác định việc bố trí khu vực biểu đồ bên trong (không bao gồm trục và nhãn trục) hoặc bên ngoài (bao gồm trục và nhãn trục). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Nếu bố cục của khu vực biểu đồ được định nghĩa thủ công, thuộc tính này xác định việc bố trí khu vực biểu đồ bên trong (không bao gồm trục và nhãn trục) hoặc bên ngoài (bao gồm trục và nhãn trục). |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Trả về định dạng của khu vực biểu đồ. Chỉ đọc [IFormat](../../com.aspose.slides/iformat).

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```


Nếu bố cục của khu vực biểu đồ được định nghĩa thủ công, thuộc tính này xác định việc bố trí khu vực biểu đồ bên trong (không bao gồm trục và nhãn trục) hoặc bên ngoài (bao gồm trục và nhãn trục). Đọc/ghi [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```


**Trả về:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```


Nếu bố cục của khu vực biểu đồ được định nghĩa thủ công, thuộc tính này xác định việc bố trí khu vực biểu đồ bên trong (không bao gồm trục và nhãn trục) hoặc bên ngoài (bao gồm trục và nhãn trục). Đọc/ghi [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |