---
title: DataLabel
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวแทนของป้ายกำกับของชุดข้อมูล.
type: docs
url: /th/com.aspose.slides/datalabel/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

เป็นตัวแทนของป้ายกำกับของชุดข้อมูล.
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | สร้างอินสแตนซ์ใหม่ของคลาส DataLabel. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | คืนค่าแผนภูมิต้นแบบ. |
| [isVisible()](#isVisible--) | False หมายถึงป้ายข้อมูลไม่แสดง (และดังนั้นทั้งหมด Show*-flags (ShowValue, ...) จะเป็น false). |
| [hide()](#hide--) | ทำให้ป้ายข้อมูลซ่อนโดยตั้งค่าทั้งหมด Show*-flags (ShowValue, ...) ให้เป็นสถานะ false. |
| [getActualLabelText()](#getActualLabelText--) | คืนค่าข้อความป้ายกำกับจริงตามการตั้งค่า DataLabelFormat หรือค่าของ TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | สามารถมีข้อความที่จัดรูปแบบอย่างหลากหลายได้. |
| [getTextFormat()](#getTextFormat--) | คืนค่ารูปแบบข้อความ. |
| [getX()](#getX--) | คืนค่า หรือ ตั้งค่าพิกัด x ของหัวเรื่องเป็นอัตราส่วนของความกว้างของแผนภูมิ. |
| [setX(float value)](#setX-float-) | คืนค่า หรือ ตั้งค่าพิกัด x ของหัวเรื่องเป็นอัตราส่วนของความกว้างของแผนภูมิ. |
| [getY()](#getY--) | คืนค่า หรือ ตั้งค่าพิกัด y ของหัวเรื่องเป็นอัตราส่วนของความสูงของแผนภูมิ. |
| [setY(float value)](#setY-float-) | คืนค่า หรือ ตั้งค่าพิกัด y ของหัวเรื่องเป็นอัตราส่วนของความสูงของแผนภูมิ. |
| [getWidth()](#getWidth--) | คืนค่า หรือ ตั้งค่าความกว้างของหัวเรื่องเป็นอัตราส่วนของความกว้างของแผนภูมิ. |
| [setWidth(float value)](#setWidth-float-) | คืนค่า หรือ ตั้งค่าความกว้างของหัวเรื่องเป็นอัตราส่วนของความกว้างของแผนภูมิ. |
| [getHeight()](#getHeight--) | คืนค่า หรือ ตั้งค่าความสูงของหัวเรื่องเป็นอัตราส่วนของความสูงของแผนภูมิ. |
| [setHeight(float value)](#setHeight-float-) | คืนค่า หรือ ตั้งค่าความสูงของหัวเรื่องเป็นอัตราส่วนของความสูงของแผนภูมิ. |
| [getRight()](#getRight--) | ด้านขวา. |
| [getBottom()](#getBottom--) | ด้านล่าง. |
| [getDataLabelFormat()](#getDataLabelFormat--) | คืนค่ารูปแบบป้ายข้อมูล. |
| [getValueFromCell()](#getValueFromCell--) | รับหรือกำหนดเซลข้อมูลของสมุดงาน. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | รับหรือกำหนดเซลข้อมูลของสมุดงาน. |
| [getActualX()](#getActualX--) | ระบุตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. |
| [getActualY()](#getActualY--) | ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. |
| [getActualWidth()](#getActualWidth--) | ระบุความกว้างจริงขององค์ประกอบแผนภูมิ. |
| [getActualHeight()](#getActualHeight--) | ระบุความสูงจริงขององค์ประกอบแผนภูมิ. |
| [getSlide()](#getSlide--) | คืนค่าไสลด์แม่ของ FillFormat. |
| [getPresentation()](#getPresentation--) | คืนค่าสไลด์พรีเซนเทชั่นแม่ของ FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

สร้างอินสแตนซ์ใหม่ของคลาส DataLabel.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ChartDataPoint พาเรนท์. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าออบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**ผลลัพธ์:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

คืนค่าแผนภูมิต้นแบบ. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**ผลลัพธ์:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False หมายถึงป้ายข้อมูลไม่แสดง (และดังนั้นทั้งหมด Show*-flags (ShowValue, ...) จะเป็น false). อ่านอย่างเดียว  boolean .

--------------------

หากป้ายข้อมูลแสดงอยู่คุณสามารถทำให้ซ่อนโดยใช้เมธอด Hide() แต่หากป้ายข้อมูลไม่แสดง (IsVisible เป็น false) คุณสามารถทำให้ป้ายข้อมูลแสดงโดยตั้งค่า Show*-flags (ShowValue, ...) ให้เป็นสถานะ true.

**ผลลัพธ์:**
boolean
### hide() {#hide--}
```
public final void hide()
```

ทำให้ป้ายข้อมูลซ่อนโดยตั้งค่าทั้งหมด Show*-flags (ShowValue, ...) ให้เป็นสถานะ false. IsVisible จะเป็น false หลังจากนี้.

--------------------

หากป้ายข้อมูลไม่แสดง (IsVisible เป็น false) คุณสามารถทำให้ป้ายข้อมูลแสดงโดยตั้งค่า Show*-flags (ShowValue, ...) ให้เป็นสถานะ true.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

คืนค่าข้อความป้ายกำกับจริงตามการตั้งค่า DataLabelFormat หรือค่าของ TextFrameForOverriding.Text.

**ผลลัพธ์:**
java.lang.String - วัตถุ java.lang.String.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ "text". หาก TextFrameForOverriding ได้รับการเริ่มต้นแล้ว จะทำการเปลี่ยนข้อความของมันเท่านั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความสำหรับ TextFrameForOverriding ใหม่. |

**ผลลัพธ์:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

สามารถมีข้อความที่จัดรูปแบบอย่างหลากหลายได้. หากคุณสมบัตินี้ไม่เป็น null แล้วค่าข้อความที่จัดรูปแบบนี้จะทับข้อความที่สร้างอัตโนมัติของป้ายข้อมูล. ข้อความที่สร้างอัตโนมัติของป้ายข้อมูลหมายถึงข้อความที่จัดการโดยคุณสมบัติ ShowSeriesName, ShowValue, ... และถูกจัดรูปแบบด้วยคุณสมบัติ TextFormatManager.TextFormat. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**ผลลัพธ์:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

คืนค่ารูปแบบข้อความ. อ่านอย่างเดียว [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**ผลลัพธ์:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

คืนค่า หรือ ตั้งค่าพิกัด x ของหัวเรื่องเป็นอัตราส่วนของความกว้างของแผนภูมิ. อ่าน/เขียน  float .

**ผลลัพธ์:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

คืนค่า หรือ ตั้งค่าพิกัด x ของหัวเรื่องเป็นอัตราส่วนของความกว้างของแผนภูมิ. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

คืนค่า หรือ ตั้งค่าพิกัด y ของหัวเรื่องเป็นอัตราส่วนของความสูงของแผนภูมิ. อ่าน/เขียน  float .

**ผลลัพธ์:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

คืนค่า หรือ ตั้งค่าพิกัด y ของหัวเรื่องเป็นอัตราส่วนของความสูงของแผนภูมิ. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

คืนค่า หรือ ตั้งค่าความกว้างของหัวเรื่องเป็นอัตราส่วนของความกว้างของแผนภูมิ. อ่าน/เขียน  float .

**ผลลัพธ์:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

คืนค่า หรือ ตั้งค่าความกว้างของหัวเรื่องเป็นอัตราส่วนของความกว้างของแผนภูมิ. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

คืนค่า หรือ ตั้งค่าความสูงของหัวเรื่องเป็นอัตราส่วนของความสูงของแผนภูมิ. อ่าน/เขียน  float .

**ผลลัพธ์:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

คืนค่า หรือ ตั้งค่าความสูงของหัวเรื่องเป็นอัตราส่วนของความสูงของแผนภูมิ. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

ด้านขวา. อ่านอย่างเดียว  float .

**ผลลัพธ์:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

ด้านล่าง. อ่านอย่างเดียว  float .

**ผลลัพธ์:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

คืนค่ารูปแบบป้ายข้อมูล. อ่านอย่างเดียว [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**ผลลัพธ์:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

รับหรือกำหนดเซลข้อมูลของสมุดงาน. ใช้เมื่อคุณสมบัติ IDataLabelFormat.ShowLabelValueFromCell มีค่าเป็น true.

**ผลลัพธ์:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

รับหรือกำหนดเซลข้อมูลของสมุดงาน. ใช้เมื่อคุณสมบัติ IDataLabelFormat.ShowLabelValueFromCell มีค่าเป็น true.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

ระบุตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่า actual. อ่าน  float .

**ผลลัพธ์:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่า actual. อ่าน  float .

**ผลลัพธ์:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

ระบุความกว้างจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่า actual. อ่าน  float .

**ผลลัพธ์:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

ระบุความสูงจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่า actual. อ่าน  float .

**ผลลัพธ์:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนค่าไสลด์แม่ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**ผลลัพธ์:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนค่าสไลด์พรีเซนเทชั่นแม่ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**ผลลัพธ์:**
[IPresentation](../../com.aspose.slides/ipresentation)