---
title: IDataLabel
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงป้ายกำกับของชุดข้อมูล.
type: docs
url: /th/com.aspose.slides/idatalabel/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

แสดงป้ายกำกับของชุดข้อมูล.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isVisible()](#isVisible--) | False หมายถึงป้ายกำกับข้อมูลไม่แสดง (และแฟล็ก Show*-flags (ShowValue, ...) จะเป็น false). |
| [hide()](#hide--) | ทำให้ป้ายกำกับข้อมูลซ่อนด้วยการตั้งค่าแฟล็ก Show*-flags (ShowValue, ...) เป็นสถานะ false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | คืนค่ารูปแบบของป้ายกำกับข้อมูล. |
| [getValueFromCell()](#getValueFromCell--) | รับหรือกำหนดเซลล์ข้อมูลของ workbook. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | รับหรือกำหนดเซลล์ข้อมูลของ workbook. |
| [getActualLabelText()](#getActualLabelText--) | คืนข้อความป้ายกำกับจริงตามการตั้งค่า DataLabelFormat หรือค่าของ TextFrameForOverriding.Text. |
| [getLabelShapeType()](#getLabelShapeType--) | รับหรือกำหนดประเภทรูปร่างของป้ายกำกับข้อมูล. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | รับหรือกำหนดประเภทรูปร่างของป้ายกำกับข้อมูล. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False หมายถึงป้ายกำกับข้อมูลไม่แสดง (และแฟล็ก Show*-flags (ShowValue, ...) จะเป็น false). บูลีนแบบอ่านอย่างเดียว.

--------------------

หากป้ายกำกับข้อมูลแสดงอยู่ คุณสามารถทำให้ซ่อนด้วยเมธอด Hide() ได้ แต่หากป้ายกำกับข้อมูลไม่แสดง (IsVisible เป็น false) คุณสามารถทำให้ป้ายกำกับข้อมูลแสดงโดยตั้งค่าแฟล็ก Show*-flags (ShowValue, ...) เป็นสถานะ true.

**คืนค่า:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

ทำให้ป้ายกำกับข้อมูลซ่อนโดยตั้งค่าแฟล็ก Show*-flags (ShowValue, ...) เป็นสถานะ false. IsVisible จะเป็น false หลังจากนี้.

--------------------

หากป้ายกำกับข้อมูลไม่แสดง (IsVisible เป็น false) คุณสามารถทำให้ป้ายกำกับข้อมูลแสดงโดยตั้งค่าแฟล็ก Show*-flags (ShowValue, ...) เป็นสถานะ true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

คืนค่ารูปแบบของป้ายกำกับข้อมูล. แบบอ่านอย่างเดียว [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**คืนค่า:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

รับหรือกำหนดเซลล์ข้อมูลของ workbook. ใช้เมื่อคุณสมบัติ IDataLabelFormat.ShowLabelValueFromCell มีค่าเป็น true.

**คืนค่า:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

รับหรือกำหนดเซลล์ข้อมูลของ workbook. ใช้เมื่อคุณสมบัติ IDataLabelFormat.ShowLabelValueFromCell มีค่าเป็น true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

คืนข้อความป้ายกำกับจริงตามการตั้งค่า DataLabelFormat หรือค่าของ TextFrameForOverriding.Text.

**คืนค่า:**
java.lang.String - ข้อความป้ายกำกับจริง String
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

รับหรือกำหนดประเภทรูปร่างของป้ายกำกับข้อมูล. คืนค่า [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) หากไม่มีรูปร่างถูกกำหนด.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // ตั้งค่ารูปแบบของป้ายกำกับข้อมูลแรกเป็น Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

รับหรือกำหนดประเภทรูปร่างของป้ายกำกับข้อมูล. คืนค่า [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) หากไม่มีรูปร่างถูกกำหนด.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // ตั้งค่าประเภทรูปร่างของป้ายกำกับข้อมูลแรกเป็น Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |