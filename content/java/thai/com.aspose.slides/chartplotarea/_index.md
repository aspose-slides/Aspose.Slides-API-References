---
title: ChartPlotArea
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงสี่เหลี่ยมที่ควรใช้ในการวางแผนภูมิ
type: docs
url: /th/com.aspose.slides/chartplotarea/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IChartPlotArea](../../com.aspose.slides/ichartplotarea)
```
public class ChartPlotArea extends DomObject<Chart> implements IChartPlotArea
```

แสดงสี่เหลี่ยมที่ควรวางแผนภูมิ

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFormat()](#getFormat--) | คืนรูปแบบของพื้นที่พล็อต |
| [getX()](#getX--) | คืนค่าหรือกำหนดพิกัด x ของมุมบนซ้ายของกล่องขอบเขตพื้นที่พล็อตเป็นส่วนของความกว้างของแผนภูมิ (จาก 0 ถึง 1) |
| [setX(float value)](#setX-float-) | คืนค่าหรือกำหนดพิกัด x ของมุมบนซ้ายของกล่องขอบเขตพื้นที่พล็อตเป็นส่วนของความกว้างของแผนภูมิ (จาก 0 ถึง 1) |
| [getY()](#getY--) | คืนค่าหรือกำหนดพิกัด y ของมุมบนซ้ายของกล่องขอบเขตพื้นที่พล็อตเป็นส่วนของความสูงของแผนภูมิ (จาก 0 ถึง 1) |
| [setY(float value)](#setY-float-) | คืนค่าหรือกำหนดพิกัด y ของมุมบนซ้ายของกล่องขอบเขตพื้นที่พล็อตเป็นส่วนของความสูงของแผนภูมิ (จาก 0 ถึง 1) |
| [getWidth()](#getWidth--) | คืนค่าหรือกำหนดความกว้างของกล่องขอบเขตพื้นที่พล็อตเป็นส่วนของความกว้างของแผนภูมิ (จาก 0 ถึง 1) |
| [setWidth(float value)](#setWidth-float-) | คืนค่าหรือกำหนดความกว้างของกล่องขอบเขตพื้นที่พล็อตเป็นส่วนของความกว้างของแผนภูมิ (จาก 0 ถึง 1) |
| [getHeight()](#getHeight--) | คืนค่าหรือกำหนดความสูงของกล่องขอบเขตพื้นที่พล็อตเป็นส่วนของความสูงของแผนภูมิ (จาก 0 ถึง 1) |
| [setHeight(float value)](#setHeight-float-) | คืนค่าหรือกำหนดความสูงของกล่องขอบเขตพื้นที่พล็อตเป็นส่วนของความสูงของแผนภูมิ (จาก 0 ถึง 1) |
| [getRight()](#getRight--) | ด้านขวา |
| [getBottom()](#getBottom--) | ด้านล่าง |
| [getChart()](#getChart--) | แผนภูมิ |
| [isLocationAutocalculated()](#isLocationAutocalculated--) | กำหนดวิธีการคำนวณตำแหน่ง: true — คำนวณอัตโนมัติ; กำหนดโดยคุณสมบัติ X, Y, Width, Height |
| [getLayoutTargetType()](#getLayoutTargetType--) | หากการจัดวางพื้นที่พล็อตกำหนดด้วยตนเอง คุณสมบัตินี้ระบุว่าจะจัดวางพื้นที่พล็อตโดยภายใน (ไม่รวมแกนและป้ายแกน) หรือโดยภายนอก (รวมแกนและป้ายแกน) |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | หากการจัดวางพื้นที่พล็อตกำหนดด้วยตนเอง คุณสมบัตินี้ระบุว่าจะจัดวางพื้นที่พล็อตโดยภายใน (ไม่รวมแกนและป้ายแกน) หรือโดยภายนอก (รวมแกนและป้ายแกน) |
| [getActualX()](#getActualX--) | ระบุตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ |
| [getActualY()](#getActualY--) | ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ |
| [getActualWidth()](#getActualWidth--) | ระบุความกว้างจริงขององค์ประกอบแผนภูมิ |
| [getActualHeight()](#getActualHeight--) | ระบุความสูงจริงขององค์ประกอบแผนภูมิ |
| [getSlide()](#getSlide--) | คืนสไลด์แม่ของ FillFormat |
| [getPresentation()](#getPresentation--) | คืนการนำเสนอแม่ของ FillFormat |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

คืนรูปแบบของพื้นที่พล็อต. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)

### getX() {#getX--}
```
public final float getX()
```

คืนค่าหรือกำหนดพิกัด x ของมุมบนซ้ายของกล่องขอบเขตพื้นที่พล็อตเป็นส่วนของความกว้างของแผนภูมิ (จาก 0 ถึง 1). อ่าน/เขียน float.

**คืนค่า:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

คืนค่าหรือกำหนดพิกัด x ของมุมบนซ้ายของกล่องขอบเขตพื้นที่พล็อตเป็นส่วนของความกว้างของแผนภูมิ (จาก 0 ถึง 1). อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

คืนค่าหรือกำหนดพิกัด y ของมุมบนซ้ายของกล่องขอบเขตพื้นที่พล็อตเป็นส่วนของความสูงของแผนภูมิ (จาก 0 ถึง 1). อ่าน/เขียน float.

**คืนค่า:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

คืนค่าหรือกำหนดพิกัด y ของมุมบนซ้ายของกล่องขอบเขตพื้นที่พล็อตเป็นส่วนของความสูงของแผนภูมิ (จาก 0 ถึง 1). อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

คืนค่าหรือกำหนดความกว้างของกล่องขอบเขตพื้นที่พล็อตเป็นส่วนของความกว้างของแผนภูมิ (จาก 0 ถึง 1). อ่าน/เขียน float.

**คืนค่า:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

คืนค่าหรือกำหนดความกว้างของกล่องขอบเขตพื้นที่พล็อตเป็นส่วนของความกว้างของแผนภูมิ (จาก 0 ถึง 1). อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

คืนค่าหรือกำหนดความสูงของกล่องขอบเขตพื้นที่พล็อตเป็นส่วนของความสูงของแผนภูมิ (จาก 0 ถึง 1). อ่าน/เขียน float.

**คืนค่า:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

คืนค่าหรือกำหนดความสูงของกล่องขอบเขตพื้นที่พล็อตเป็นส่วนของความสูงของแผนภูมิ (จาก 0 ถึง 1). อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

ด้านขวา. อ่านอย่างเดียว float.

**คืนค่า:**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

ด้านล่าง. อ่านอย่างเดียว float.

**คืนค่า:**
float

### getChart() {#getChart--}
```
public final IChart getChart()
```

แผนภูมิ. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**คืนค่า:**
[IChart](../../com.aspose.slides/ichart)

### isLocationAutocalculated() {#isLocationAutocalculated--}
```
public final boolean isLocationAutocalculated()
```

กำหนดวิธีการคำนวณตำแหน่ง: true — คำนวณอัตโนมัติ; กำหนดโดยคุณสมบัติ X, Y, Width, Height. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getLayoutTargetType() {#getLayoutTargetType--}
```
public final int getLayoutTargetType()
```

หากการจัดวางพื้นที่พล็อตกำหนดด้วยตนเอง คุณสมบัตินี้ระบุว่าจะจัดวางพื้นที่พล็อตโดยภายใน (ไม่รวมแกนและป้ายแกน) หรือโดยภายนอก (รวมแกนและป้ายแกน). อ่าน/เขียน [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```


**คืนค่า:**
int

### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public final void setLayoutTargetType(int value)
```

หากการจัดวางพื้นที่พล็อตกำหนดด้วยตนเอง คุณสมบัตินี้ระบุว่าจะจัดวางพื้นที่พล็อตโดยภายใน (ไม่รวมแกนและป้ายแกน) หรือโดยภายนอก (รวมแกนและป้ายแกน). อ่าน/เขียน [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

ระบุตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**คืนค่า:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**คืนค่า:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

ระบุความกว้างจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**คืนค่า:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

ระบุความสูงจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**คืนค่า:**
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนสไลด์แม่ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**คืนค่า:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนการนำเสนอแม่ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation)