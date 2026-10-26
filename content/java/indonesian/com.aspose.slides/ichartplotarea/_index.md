---
title: IChartPlotArea
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili properti judul diagram.
type: docs
url: /id/com.aspose.slides/ichartplotarea/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Mewakili properti judul diagram.
## Metode

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Mengembalikan format area plot. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Jika tata letak area plot didefinisikan secara manual, properti ini menentukan apakah menata area plot dari dalamnya (tidak termasuk sumbu dan label sumbu) atau dari luar (termasuk sumbu dan label sumbu). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Jika tata letak area plot didefinisikan secara manual, properti ini menentukan apakah menata area plot dari dalamnya (tidak termasuk sumbu dan label sumbu) atau dari luar (termasuk sumbu dan label sumbu). |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Mengembalikan format area plot. Hanya-baca [IFormat](../../com.aspose.slides/iformat).

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```

Jika tata letak area plot didefinisikan secara manual, properti ini menentukan apakah menata area plot dari dalamnya (tidak termasuk sumbu dan label sumbu) atau dari luar (termasuk sumbu dan label sumbu). Baca/tulis [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Mengembalikan:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```

Jika tata letak area plot didefinisikan secara manual, properti ini menentukan apakah menata area plot dari dalamnya (tidak termasuk sumbu dan label sumbu) atau dari luar (termasuk sumbu dan label sumbu). Baca/tulis [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |