---
title: Trendline
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: คลาสแสดงเส้นแนวโน้มของชุดข้อมูลในแผนภูมิ
type: docs
url: /th/com.aspose.slides/trendline/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**ส่วนต่อประสานที่ทำงานทั้งหมด:**  
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)  
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

คลาสแสดงเส้นแนวโน้มของชุดข้อมูลในแผนภูมิ
## Methods

| Method | Description |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | รับหรือกำหนดชื่อของเส้นแนวโน้ม อ่าน/เขียน String. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | รับหรือกำหนดชื่อของเส้นแนวโน้ม อ่าน/เขียน String. |
| [getTrendlineType()](#getTrendlineType--) | รับหรือกำหนดประเภทของเส้นแนวโน้ม. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | รับหรือกำหนดประเภทของเส้นแนวโน้ม. |
| [getFormat()](#getFormat--) | แสดงรูปแบบของเส้นแนวโน้ม. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | แสดงรูปแบบของเส้นแนวโน้ม. |
| [getBackward()](#getBackward--) | ระบุจำนวนของหมวดหมู่ (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายไปก่อนข้อมูลของชุดข้อมูลที่กำลังทำแนวโน้ม. |
| [setBackward(double value)](#setBackward-double-) | ระบุจำนวนของหมวดหมู่ (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายไปก่อนข้อมูลของชุดข้อมูลที่กำลังทำแนวโน้ม. |
| [getForward()](#getForward--) | ระบุจำนวนของหมวดหมู่ (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายหลังข้อมูลของชุดข้อมูลที่กำลังทำแนวโน้ม. |
| [setForward(double value)](#setForward-double-) | ระบุจำนวนของหมวดหมู่ (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายหลังข้อมูลของชุดข้อมูลที่กำลังทำแนวโน้ม. |
| [getIntercept()](#getIntercept--) | ระบุค่าที่เส้นแนวโน้มกว่าจะตัดแกน y. |
| [setIntercept(double value)](#setIntercept-double-) | ระบุค่าที่เส้นแนวโน้มกว่าจะตัดแกน y. |
| [getDisplayEquation()](#getDisplayEquation--) | ระบุว่าสมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายเดียวกับ Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | ระบุว่าสมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายเดียวกับ Rsquaredvalue). |
| [getOrder()](#getOrder--) | ระบุลำดับของเส้นแนวโน้มแบบพหุนาม. |
| [setOrder(byte value)](#setOrder-byte-) | ระบุลำดับของเส้นแนวโน้มแบบพหุนาม. |
| [getPeriod()](#getPeriod--) | ระบุรอบของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. |
| [setPeriod(byte value)](#setPeriod-byte-) | ระบุรอบของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายเดียวกับสมการ). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายเดียวกับสมการ). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | แสดงรายการสัญลักษณ์ที่เกี่ยวข้องกับเส้นแนวโน้มนี้ อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | สามารถบรรจุข้อความรูปแบบเต็มได้. |
| [getTextFormat()](#getTextFormat--) | คืนรูปแบบข้อความ. |
| [getChart()](#getChart--) | คืนแผนภูมแม่. |
| [getSlide()](#getSlide--) | คืนสไลด์แม่ของ FillFormat. |
| [getPresentation()](#getPresentation--) | คืนการนำเสนอแม่ของ FillFormat. |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

รับหรือกำหนดชื่อของเส้นแนวโน้ม อ่าน/เขียน String.

**ผลลัพธ์:**  
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

รับหรือกำหนดชื่อของเส้นแนวโน้ม อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

รับหรือกำหนดประเภทของเส้นแนวโน้ม อ่าน/เขียน [TrendlineType](../../com.aspose.slides/trendlinetype).

**ผลลัพธ์:**  
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

รับหรือกำหนดประเภทของเส้นแนวโน้ม อ่าน/เขียน [TrendlineType](../../com.aspose.slides/trendlinetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

แสดงรูปแบบของเส้นแนวโน้ม อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**ผลลัพธ์:**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

แสดงรูปแบบของเส้นแนวโน้ม อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public final double getBackward()
```

ระบุจำนวนของหมวดหมู่ (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายไปก่อนข้อมูลของชุดข้อมูลที่กำลังทำแนวโน้ม. บนแผนภูมิกระจายและแผนภูมิที่ไม่ใช่กระจาย ค่าอาจเป็นค่าไม่เป็นลบใดๆ. อ่าน/เขียน double.

**ผลลัพธ์:**  
double

### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

ระบุจำนวนของหมวดหมู่ (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายไปก่อนข้อมูลของชุดข้อมูลที่กำลังทำแนวโน้ม. บนแผนภูมิกระจายและแผนภูมิที่ไม่ใช่กระจาย ค่าอาจเป็นค่าไม่เป็นลบใดๆ. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

ระบุจำนวนของหมวดหมู่ (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายหลังข้อมูลของชุดข้อมูลที่กำลังทำแนวโน้ม. บนแผนภูมิกระจายและแผนภูมิที่ไม่ใช่กระจาย ค่าอาจเป็นค่าไม่เป็นลบใดๆ. อ่าน/เขียน double.

**ผลลัพธ์:**  
double

### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

ระบุจำนวนของหมวดหมู่ (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายหลังข้อมูลของชุดข้อมูลที่กำลังทำแนวโน้ม. บนแผนภูมิกระจายและแผนภูมิที่ไม่ใช่กระจาย ค่าอาจเป็นค่าไม่เป็นลบใดๆ. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

ระบุค่าที่เส้นแนวโน้มกว่าจะตัดแกน y. คุณสมบัตินี้สนับสนุนเฉพาะเมื่อประเภทเส้นแนวโน้มเป็น exp, linear หรือ poly. อ่าน/เขียน double.

**ผลลัพธ์:**  
double

### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

ระบุค่าที่เส้นแนวโน้มกว่าจะตัดแกน y. คุณสมบัตินี้สนับสนุนเฉพาะเมื่อประเภทเส้นแนวโน้มเป็น exp, linear หรือ poly. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

ระบุว่าสมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายเดียวกับ Rsquaredvalue). อ่าน/เขียน boolean.

**ผลลัพธ์:**  
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

ระบุว่าสมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายเดียวกับ Rsquaredvalue). อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public final byte getOrder()
```

ระบุลำดับของเส้นแนวโน้มแบบพหุนาม. จะถูกละเลยสำหรับประเภทเส้นแนวโน้มอื่น. ค่าต้องอยู่ระหว่าง 2 ถึง 6. อ่าน/เขียน byte.

**ผลลัพธ์:**  
byte

### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

ระบุลำดับของเส้นแนวโน้มแบบพหุนาม. จะถูกละเลยสำหรับประเภทเส้นแนวโน้มอื่น. ค่าต้องอยู่ระหว่าง 2 ถึง 6. อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

ระบุรอบของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. จะถูกละเลยสำหรับรูปแบบเส้นแนวโน้มอื่น. ค่าต้องอยู่ระหว่าง 2 ถึง 255. อ่าน/เขียน byte.

**ผลลัพธ์:**  
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

ระบุรอบของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. จะถูกละเลยสำหรับรูปแบบเส้นแนวโน้มอื่น. ค่าต้องอยู่ระหว่าง 2 ถึง 255. อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายเดียวกับสมการ). อ่าน/เขียน boolean.

**ผลลัพธ์:**  
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายเดียวกับสมการ). อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

แสดงรายการสัญลักษณ์ที่เกี่ยวข้องกับเส้นแนวโน้มนี้ อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**ผลลัพธ์:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ "text". หาก TextFrameForOverriding ถูกเริ่มต้นแล้วจะเปลี่ยนข้อความของมันทันที.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความสำหรับ TextFrameForOverriding ใหม่. |

**ผลลัพธ์:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

สามารถบรรจุข้อความรูปแบบเต็มได้. หากคุณสมบัตินี้ไม่เป็น null ข้อความรูปแบบเต็มนี้จะทับข้อความที่สร้างอัตโนมัติของป้ายข้อมูล. ข้อความที่สร้างอัตโนมัติหมายถึงข้อความที่จัดการโดยคุณสมบัติ ShowSeriesName, ShowValue, ... และจัดรูปแบบด้วยคุณสมบัติ TextFormatManager.TextFormat. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**ผลลัพธ์:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

คืนรูปแบบข้อความ. อ่านอย่างเดียว [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**ผลลัพธ์:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

คืนแผนภูมแม่. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**ผลลัพธ์:**  
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนสไลด์แม่ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**ผลลัพธ์:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนการนำเสนอแม่ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**ผลลัพธ์:**  
[IPresentation](../../com.aspose.slides/ipresentation)