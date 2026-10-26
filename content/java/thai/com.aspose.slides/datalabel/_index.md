---
title: DataLabel
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงป้ายกำกับของซีรีส์.
type: docs
url: /th/com.aspose.slides/datalabel/
---
**Inheritance:**  
การสืบทอด:  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject  
```
public class DataLabel implements IDataLabel, IDOMObject
```

Represents a series labels.  
แสดงป้ายกำกับของซีรีส์.

## Constructors

| Constructor | Description |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | สร้างอินสแตนซ์ใหม่ของคลาส DataLabel. |

## Methods

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | ส่งกลับแผนภูมิเพียวพัน. |
| [isVisible()](#isVisible--) | False หมายความว่าป้ายกำกับข้อมูลไม่ปรากฏ (และดังนั้นทุกแฟล็ก Show*-flags (ShowValue, ...) จะเป็น false). |
| [hide()](#hide--) | ทำให้ป้ายกำกับข้อมูลซ่อนโดยตั้งค่าแฟล็ก Show*-flags (ShowValue, ...) ให้เป็นสถานะ false. |
| [getActualLabelText()](#getActualLabelText--) | ส่งกลับข้อความป้ายกำกับจริงตามการตั้งค่า DataLabelFormat หรือค่า TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | สามารถบรรจุข้อความที่มีรูปแบบเต็ม. |
| [getTextFormat()](#getTextFormat--) | ส่งกลับรูปแบบข้อความ. |
| [getX()](#getX--) | ส่งกลับหรือกำหนดค่าพิกัด x ของหัวเรื่องเป็นส่วนหนึ่งของความกว้างของแผนภูมิ. |
| [setX(float value)](#setX-float-) | ส่งกลับหรือกำหนดค่าพิกัด x ของหัวเรื่องเป็นส่วนหนึ่งของความกว้างของแผนภูมิ. |
| [getY()](#getY--) | ส่งกลับหรือกำหนดค่าพิกัด y ของหัวเรื่องเป็นส่วนหนึ่งของความสูงของแผนภูมิ. |
| [setY(float value)](#setY-float-) | ส่งกลับหรือกำหนดค่าพิกัด y ของหัวเรื่องเป็นส่วนหนึ่งของความสูงของแผนภูมิ. |
| [getWidth()](#getWidth--) | ส่งกลับหรือกำหนดค่าความกว้างของหัวเรื่องเป็นส่วนหนึ่งของความกว้างของแผนภูมิ. |
| [setWidth(float value)](#setWidth-float-) | ส่งกลับหรือกำหนดค่าความกว้างของหัวเรื่องเป็นส่วนหนึ่งของความกว้างของแผนภูมิ. |
| [getHeight()](#getHeight--) | ส่งกลับหรือกำหนดค่าความสูงของหัวเรื่องเป็นส่วนหนึ่งของความสูงของแผนภูมิ. |
| [setHeight(float value)](#setHeight-float-) | ส่งกลับหรือกำหนดค่าความสูงของหัวเรื่องเป็นส่วนหนึ่งของความสูงของแผนภูมิ. |
| [getRight()](#getRight--) | ด้านขวา. |
| [getBottom()](#getBottom--) | ด้านล่าง. |
| [getDataLabelFormat()](#getDataLabelFormat--) | ส่งกลับรูปแบบป้ายกำกับข้อมูล. |
| [getValueFromCell()](#getValueFromCell--) | รับหรือกำหนดเซลล์ข้อมูลของเวิร์กบุ๊ก. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | รับหรือกำหนดเซลล์ข้อมูลของเวิร์กบุ๊ก. |
| [getActualX()](#getActualX--) | ระบุตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิเกี่ยวกับมุมซ้ายบนของแผนภูมิ. |
| [getActualY()](#getActualY--) | ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิเกี่ยวกับมุมซ้ายบนของแผนภูมิ. |
| [getActualWidth()](#getActualWidth--) | ระบุความกว้างจริงขององค์ประกอบแผนภูมิ. |
| [getActualHeight()](#getActualHeight--) | ระบุความสูงจริงขององค์ประกอบแผนภูมิ. |
| [getSlide()](#getSlide--) | ส่งกลับสไลด์แม่ของ FillFormat. |
| [getPresentation()](#getPresentation--) | ส่งกลับการนำเสนอแม่ของ FillFormat. |

### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

สร้างอินสแตนซ์ใหม่ของคลาส DataLabel.

**Parameters:**  
พารามิเตอร์:  
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ChartDataPoint พาเรนท์. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งกลับวัตถุ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**Returns:**  
ส่งกลับ:  
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

ส่งกลับแผนภูมิเพียวพัน. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**Returns:**  
ส่งกลับ:  
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False หมายความว่าป้ายกำกับข้อมูลไม่ปรากฏ (และดังนั้นทุกแฟล็ก Show*-flags (ShowValue, ...) จะเป็น false). อ่านอย่างเดียว boolean.

--------------------

หากป้ายกำกับข้อมูลปรากฏคุณสามารถทำให้ซ่อนด้วยเมธอด hide() แต่หากป้ายกำกับข้อมูลไม่ปรากฏ (IsVisible เป็น false) คุณสามารถทำให้ปรากฏได้โดยตั้งค่าแฟล็ก Show*-flags (ShowValue, ...) ให้เป็นสถานะ true.

**Returns:**  
ส่งกลับ:  
boolean

### hide() {#hide--}
```
public final void hide()
```

ทำให้ป้ายกำกับข้อมูลซ่อนโดยตั้งค่าแฟล็ก Show*-flags (ShowValue, ...) ให้เป็นสถานะ false. IsVisible จะเป็น false หลังจากนี้.

--------------------

หากป้ายกำกับข้อมูลไม่ปรากฏ (IsVisible เป็น false) คุณสามารถทำให้ปรากฏได้โดยตั้งค่าแฟล็ก Show*-flags (ShowValue, ...) ให้เป็นสถานะ true.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

ส่งกลับข้อความป้ายกำกับจริงตามการตั้งค่า DataLabelFormat หรือค่า TextFrameForOverriding.Text.

**Returns:**  
ส่งกลับ:  
java.lang.String - วัตถุ java.lang.String.

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ "text". หาก TextFrameForOverriding ถูกเริ่มต้นไว้แล้วก็จะเปลี่ยนข้อความเพียงอย่างเดียว.

**Parameters:**  
พารามิเตอร์:  
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ข้อความสำหรับ TextFrameForOverriding ใหม่. |

**Returns:**  
ส่งกลับ:  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

สามารถบรรจุข้อความที่มีรูปแบบเต็ม. หากคุณสมบัตินี้ไม่เป็น null ข้อความที่มีรูปแบบนี้จะทับข้อความที่สร้างอัตโนมัติของป้ายกำกับข้อมูล. ข้อความที่สร้างอัตโนมัติหมายถึงข้อความที่จัดการโดยคุณสมบัติ ShowSeriesName, ShowValue, ... และถูกจัดรูปแบบด้วย TextFormatManager.TextFormat. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**  
ส่งกลับ:  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

ส่งกลับรูปแบบข้อความ. อ่านอย่างเดียว [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returns:**  
ส่งกลับ:  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getX() {#getX--}
```
public final float getX()
```

ส่งกลับหรือกำหนดค่าพิกัด x ของหัวเรื่องเป็นส่วนหนึ่งของความกว้างของแผนภูมิ. อ่าน/เขียน float.

**Returns:**  
ส่งกลับ:  
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

ส่งกลับหรือกำหนดค่าพิกัด x ของหัวเรื่องเป็นส่วนหนึ่งของความกว้างของแผนภูมิ. อ่าน/เขียน float.

**Parameters:**  
พารามิเตอร์:  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

ส่งกลับหรือกำหนดค่าพิกัด y ของหัวเรื่องเป็นส่วนหนึ่งของความสูงของแผนภูมิ. อ่าน/เขียน float.

**Returns:**  
ส่งกลับ:  
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

ส่งกลับหรือกำหนดค่าพิกัด y ของหัวเรื่องเป็นส่วนหนึ่งของความสูงของแผนภูมิ. อ่าน/เขียน float.

**Parameters:**  
พารามิเตอร์:  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

ส่งกลับหรือกำหนดค่าความกว้างของหัวเรื่องเป็นส่วนหนึ่งของความกว้างของแผนภูมิ. อ่าน/เขียน float.

**Returns:**  
ส่งกลับ:  
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

ส่งกลับหรือกำหนดค่าความกว้างของหัวเรื่องเป็นส่วนหนึ่งของความกว้างของแผนภูมิ. อ่าน/เขียน float.

**Parameters:**  
พารามิเตอร์:  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

ส่งกลับหรือกำหนดค่าความสูงของหัวเรื่องเป็นส่วนหนึ่งของความสูงของแผนภูมิ. อ่าน/เขียน float.

**Returns:**  
ส่งกลับ:  
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

ส่งกลับหรือกำหนดค่าความสูงของหัวเรื่องเป็นส่วนหนึ่งของความสูงของแผนภูมิ. อ่าน/เขียน float.

**Parameters:**  
พารามิเตอร์:  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

ด้านขวา. อ่านอย่างเดียว float.

**Returns:**  
ส่งกลับ:  
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

ด้านล่าง. อ่านอย่างเดียว float.

**Returns:**  
ส่งกลับ:  
float

### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

ส่งกลับรูปแบบป้ายกำกับข้อมูล. อ่านอย่างเดียว [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returns:**  
ส่งกลับ:  
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

รับหรือกำหนดเซลล์ข้อมูลของเวิร์กบุ๊ก. ใช้เมื่อคุณสมบัติ IDataLabelFormat.ShowLabelValueFromCell มีค่าเป็น true.

**Returns:**  
ส่งกลับ:  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

รับหรือกำหนดเซลล์ข้อมูลของเวิร์กบุ๊ก. ใช้เมื่อคุณสมบัติ IDataLabelFormat.ShowLabelValueFromCell มีค่าเป็น true.

**Parameters:**  
พารามิเตอร์:  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

ระบุตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิเกี่ยวกับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**Returns:**  
ส่งกลับ:  
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิเกี่ยวกับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**Returns:**  
ส่งกลับ:  
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

ระบุความกว้างจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**Returns:**  
ส่งกลับ:  
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

ระบุความสูงจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**Returns:**  
ส่งกลับ:  
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

ส่งกลับสไลด์แม่ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**  
ส่งกลับ:  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ส่งกลับการนำเสนอแม่ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**  
ส่งกลับ:  
[IPresentation](../../com.aspose.slides/ipresentation)