---
title: DataLabel
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนของป้ายกำกับซีรีส์
type: docs
url: /th/com.aspose.slides/datalabel/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ใช้ทั้งหมด:**  
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject  
```
public class DataLabel implements IDataLabel, IDOMObject
```

เป็นตัวแทนของป้ายกำกับซีรีส์.  
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | สร้างอินสแตนซ์ใหม่ของคลาส DataLabel. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | คืนค่าแผนภูมิต้นแบบ. |
| [isVisible()](#isVisible--) | ค่าผิดหมายความว่าป้ายข้อมูลไม่ปรากฏ (และทำให้ทุกฟลัก Show*- (ShowValue, ...) มีค่าเป็นเท็จ). |
| [hide()](#hide--) | ซ่อนป้ายข้อมูลโดยตั้งค่าฟลัก Show*- (ShowValue, ...) ทั้งหมดเป็นเท็จ. |
| [getActualLabelText()](#getActualLabelText--) | คืนค่าข้อความป้ายจริงตามการตั้งค่า DataLabelFormat หรืค่า TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ “text”. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | สามารถบรรจุข้อความที่จัดรูปแบบแบบ Rich. |
| [getTextFormat()](#getTextFormat--) | คืนค่ารูปแบบข้อความ. |
| [getX()](#getX--) | คืนค่า หรือ ตั้งค่าพิกัด x ของหัวเรื่องเป็นส่วนละครึ่งของความกว้างของแผนภูมิ. |
| [setX(float value)](#setX-float-) | คืนค่า หรือ ตั้งค่าพิกัด x ของหัวเรื่องเป็นส่วนละครึ่งของความกว้างของแผนภูมิ. |
| [getY()](#getY--) | คืนค่า หรือ ตั้งค่าพิกัด y ของหัวเรื่องเป็นส่วนละครึ่งของความสูงของแผนภูมิ. |
| [setY(float value)](#setY-float-) | คืนค่า หรือ ตั้งค่าพิกัด y ของหัวเรื่องเป็นส่วนละครึ่งของความสูงของแผนภูมิ. |
| [getWidth()](#getWidth--) | คืนค่า หรือ ตั้งค่าความกว้างของหัวเรื่องเป็นส่วนละครึ่งของความกว้างของแผนภูมิ. |
| [setWidth(float value)](#setWidth-float-) | คืนค่า หรือ ตั้งค่าความกว้างของหัวเรื่องเป็นส่วนละครึ่งของความกว้างของแผนภูมิ. |
| [getHeight()](#getHeight--) | คืนค่า หรือ ตั้งค่าความสูงของหัวเรื่องเป็นส่วนละครึ่งของความสูงของแผนภูมิ. |
| [setHeight(float value)](#setHeight-float-) | คืนค่า หรือ ตั้งค่าความสูงของหัวเรื่องเป็นส่วนละครึ่งของความสูงของแผนภูมิ. |
| [getRight()](#getRight--) | ขวา. |
| [getBottom()](#getBottom--) | ด้านล่าง. |
| [getDataLabelFormat()](#getDataLabelFormat--) | คืนค่ารูปแบบป้ายข้อมูล. |
| [getValueFromCell()](#getValueFromCell--) | รับ หรือ ตั้งค่าเซลล์ข้อมูลเวิร์กบุ๊ก. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | รับ หรือ ตั้งค่าเซลล์ข้อมูลเวิร์กบุ๊ก. |
| [getLabelShapeType()](#getLabelShapeType--) | รับ หรือ ตั้งค่าประเภทรูปทรงของป้ายข้อมูล. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | รับ หรือ ตั้งค่าประเภทรูปทรงของป้ายข้อมูล. |
| [getActualX()](#getActualX--) | ระบุตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. |
| [getActualY()](#getActualY--) | ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. |
| [getActualWidth()](#getActualWidth--) | ระบุความกว้างจริงขององค์ประกอบแผนภูมิ. |
| [getActualHeight()](#getActualHeight--) | ระบุความสูงจริงขององค์ประกอบแผนภูมิ. |
| [getSlide()](#getSlide--) | คืนสไลด์แม่ของ FillFormat. |
| [getPresentation()](#getPresentation--) | คืนการนำเสนอแม่ของ FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

สร้างอินสแตนซ์ใหม่ของคลาส DataLabel.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ChartDataPoint พาเรนต์. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**ค่าที่คืนกลับ:**  
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

คืนค่าแผนภูมิต้นแบบ. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**ค่าที่คืนกลับ:**  
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

ค่าผิดหมายความว่าป้ายข้อมูลไม่ปรากฏ (และทำให้ทุกฟลัก Show*- (ShowValue, ...) มีค่าเป็นเท็จ). อ่านอย่างเดียว  boolean .

--------------------

หากป้ายข้อมูลปรากฏ คุณสามารถซ่อนมันด้วยเมธอด hide() แต่หากป้ายข้อมูลไม่ปรากฏ (IsVisible เป็นค่าเท็จ) คุณสามารถทำให้ป้ายข้อมูลปรากฏได้โดยตั้งค่าฟลัก Show*- (ShowValue, ...) ให้เป็นสถานะจริง.

**ค่าที่คืนกลับ:**  
boolean
### hide() {#hide--}
```
public final void hide()
```

ซ่อนป้ายข้อมูลโดยตั้งค่าฟลัก Show*- (ShowValue, ...) ทั้งหมดเป็นเท็จ. IsVisible จะเป็นค่าเท็จหลังจากนี้.

--------------------

หากป้ายข้อมูลไม่ปรากฏ (IsVisible เป็นค่าเท็จ) คุณสามารถทำให้ป้ายข้อมูลปรากฏได้โดยตั้งค่าฟลัก Show*- (ShowValue, ...) ให้เป็นสถานะจริง.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

คืนค่าข้อความป้ายจริงตามการตั้งค่า DataLabelFormat หรืค่า TextFrameForOverriding.Text.

**ค่าที่คืนกลับ:**  
java.lang.String - วัตถุ java.lang.String.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ “text”. หาก TextFrameForOverriding ถูกเริ่มต้นแล้วจะเปลี่ยนข้อความเท่านั้น.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความสำหรับ TextFrameForOverriding ใหม่. |

**ค่าที่คืนกลับ:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

สามารถบรรจุข้อความที่จัดรูปแบบแบบ Rich. หากคุณสมบัตินี้ไม่เป็น null ข้อความที่จัดรูปแบบนี้จะทับข้อความที่สร้างอัตโนมัติของป้ายข้อมูล. ข้อความที่สร้างอัตโนมัติของป้ายข้อมูลหมายถึงข้อความที่จัดการโดยคุณสมบัติ ShowSeriesName, ShowValue, ... และถูกจัดรูปแบบด้วยคุณสมบัติ TextFormatManager.TextFormat. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**ค่าที่คืนกลับ:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

คืนค่ารูปแบบข้อความ. อ่านอย่างเดียว [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**ค่าที่คืนกลับ:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

คืนค่า หรือ ตั้งค่าพิกัด x ของหัวเรื่องเป็นส่วนละครึ่งของความกว้างของแผนภูมิ. อ่าน/เขียน  float .

**ค่าที่คืนกลับ:**  
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

คืนค่า หรือ ตั้งค่าพิกัด x ของหัวเรื่องเป็นส่วนละครึ่งของความกว้างของแผนภูมิ. อ่าน/เขียน  float .

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

คืนค่า หรือ ตั้งค่าพิกัด y ของหัวเรื่องเป็นส่วนละครึ่งของความสูงของแผนภูมิ. อ่าน/เขียน  float .

**ค่าที่คืนกลับ:**  
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

คืนค่า หรือ ตั้งค่าพิกัด y ของหัวเรื่องเป็นส่วนละครึ่งของความสูงของแผนภูมิ. อ่าน/เขียน  float .

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

คืนค่า หรือ ตั้งค่าความกว้างของหัวเรื่องเป็นส่วนละครึ่งของความกว้างของแผนภูมิ. อ่าน/เขียน  float .

**ค่าที่คืนกลับ:**  
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

คืนค่า หรือ ตั้งค่าความกว้างของหัวเรื่องเป็นส่วนละครึ่งของความกว้างของแผนภูมิ. อ่าน/เขียน  float .

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

คืนค่า หรือ ตั้งค่าความสูงของหัวเรื่องเป็นส่วนละครึ่งของความสูงของแผนภูมิ. อ่าน/เขียน  float .

**ค่าที่คืนกลับ:**  
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

คืนค่า หรือ ตั้งค่าความสูงของหัวเรื่องเป็นส่วนละครึ่งของความสูงของแผนภูมิ. อ่าน/เขียน  float .

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

ขวา. อ่านอย่างเดียว  float .

**ค่าที่คืนกลับ:**  
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

ด้านล่าง. อ่านอย่างเดียว  float .

**ค่าที่คืนกลับ:**  
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

คืนค่ารูปแบบป้ายข้อมูล. อ่านอย่างเดียว [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**ค่าที่คืนกลับ:**  
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

รับ หรือ ตั้งค่าเซลล์ข้อมูลเวิร์กบุ๊ก. ใช้เมื่อคุณสมบัติ IDataLabelFormat.ShowLabelValueFromCell มีค่าเป็น true.

**ค่าที่คืนกลับ:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

รับ หรือ ตั้งค่าเซลล์ข้อมูลเวิร์กบุ๊ก. ใช้เมื่อคุณสมบัติ IDataLabelFormat.ShowLabelValueFromCell มีค่าเป็น true.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```

รับ หรือ ตั้งค่าประเภทรูปทรงของป้ายข้อมูล. คืนค่า [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) หากไม่มีการกำหนดรูปทรง.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // ตั้งค่าประเภทรูปทรงของป้ายข้อมูลแรกเป็น Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ค่าที่คืนกลับ:**  
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public final void setLabelShapeType(int value)
```

รับ หรือ ตั้งค่าประเภทรูปทรงของป้ายข้อมูล. คืนค่า [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) หากไม่มีการกำหนดรูปทรง.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // ตั้งค่าประเภทรูปทรงของป้ายข้อมูลแรกเป็น Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

ระบุตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**ค่าที่คืนกลับ:**  
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**ค่าที่คืนกลับ:**  
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

ระบุความกว้างจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**ค่าที่คืนกลับ:**  
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

ระบุความสูงจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**ค่าที่คืนกลับ:**  
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนสไลด์แม่ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**ค่าที่คืนกลับ:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนการนำเสนอแม่ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**ค่าที่คืนกลับ:**  
[IPresentation](../../com.aspose.slides/ipresentation)