---
title: IChartPlotArea
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวแทนของคุณสมบัติหัวข้อแผนภูมิ.
type: docs
url: /th/com.aspose.slides/ichartplotarea/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

เป็นตัวแทนของคุณสมบัติหัวข้อแผนภูมิ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFormat()](#getFormat--) | คืนค่ารูปแบบของพื้นที่พล็อต. |
| [getLayoutTargetType()](#getLayoutTargetType--) | หากการจัดวางของพื้นที่พล็อตถูกกำหนดด้วยตนเอง คุณสมบัตินี้ระบุว่าจะจัดวางพื้นที่พล็อตโดยภายใน (ไม่รวมแกนและป้ายแกน) หรือโดยภายนอก (รวมแกนและป้ายแกน). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | หากการจัดวางของพื้นที่พล็อตถูกกำหนดด้วยตนเอง คุณสมบัตินี้ระบุว่าจะจัดวางพื้นที่พล็อตโดยภายใน (ไม่รวมแกนและป้ายแกน) หรือโดยภายนอก (รวมแกนและป้ายแกน). |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


คืนค่ารูปแบบของพื้นที่พล็อต. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```


หากการจัดวางของพื้นที่พล็อตถูกกำหนดด้วยตนเอง คุณสมบัตินี้ระบุว่าจะจัดวางพื้นที่พล็อตโดยภายใน (ไม่รวมแกนและป้ายแกน) หรือโดยภายนอก (รวมแกนและป้ายแกน). อ่าน/เขียน [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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


**คืนค่า:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```


หากการจัดวางของพื้นที่พล็อตถูกกำหนดด้วยตนเอง คุณสมบัตินี้ระบุว่าจะจัดวางพื้นที่พล็อตโดยภายใน (ไม่รวมแกนและป้ายแกน) หรือโดยภายนอก (รวมแกนและป้ายแกน). อ่าน/เขียน [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |