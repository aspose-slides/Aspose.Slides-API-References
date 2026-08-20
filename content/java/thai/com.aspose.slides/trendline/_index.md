---
title: Trendline
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: คลาสแสดงเส้นแนวโน้มของชุดข้อมูลแผนภูมิ
type: docs
url: /th/com.aspose.slides/trendline/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)  
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

คลาสแสดงเส้นแนวโน้มของชุดข้อมูลแผนภูมิ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | รับหรือกำหนดชื่อของเส้นแนวโน้ม. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | รับหรือกำหนดชื่อของเส้นแนวโน้ม. |
| [getTrendlineType()](#getTrendlineType--) | รับหรือกำหนดประเภทของเส้นแนวโน้ม. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | รับหรือกำหนดประเภทของเส้นแนวโน้ม. |
| [getFormat()](#getFormat--) | แสดงรูปแบบของเส้นแนวโน้ม. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | แสดงรูปแบบของเส้นแนวโน้ม. |
| [getBackward()](#getBackward--) | ระบุจำนวนหมวดหมู่ (หรือหน่วยในแผนภูมิแบบกระจาย) ที่เส้นแนวโน้มขยายก่อนข้อมูลของชุดข้อมูลที่กำลังทำแนวโน้ม. |
| [setBackward(double value)](#setBackward-double-) | ระบุจำนวนหมวดหมู่ (หรือหน่วยในแผนภูมิแบบกระจาย) ที่เส้นแนวโน้มขยายก่อนข้อมูลของชุดข้อมูลที่กำลังทำแนวโน้ม. |
| [getForward()](#getForward--) | ระบุจำนวนหมวดหมู่ (หรือหน่วยในแผนภูมิแบบกระจาย) ที่เส้นแนวโน้มขยายหลังข้อมูลของชุดข้อมูลที่กำลังทำแนวโน้ม. |
| [setForward(double value)](#setForward-double-) | ระบุจำนวนหมวดหมู่ (หรือหน่วยในแผนภูมิแบบกระจาย) ที่เส้นแนวโน้มขยายหลังข้อมูลของชุดข้อมูลที่กำลังทำแนวโน้ม. |
| [getIntercept()](#getIntercept--) | ระบุค่าที่เส้นแนวโน้มจะตัดแกน Y. |
| [setIntercept(double value)](#setIntercept-double-) | ระบุค่าที่เส้นแนวโน้มจะตัดแกน Y. |
| [getDisplayEquation()](#getDisplayEquation--) | ระบุว่สมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายเดียวกับ Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | ระบุว่สมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายเดียวกับ Rsquaredvalue). |
| [getOrder()](#getOrder--) | ระบุลำดับของเส้นแนวโน้มพหุนาม. |
| [setOrder(byte value)](#setOrder-byte-) | ระบุลำดับของเส้นแนวโน้มพหุนาม. |
| [getPeriod()](#getPeriod--) | ระบุช่วงเวลาของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. |
| [setPeriod(byte value)](#setPeriod-byte-) | ระบุช่วงเวลาของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายเดียวกับสมการ). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายเดียวกับสมการ). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | แสดงรายการคำอธิบายสีที่เกี่ยวข้องกับเส้นแนวโน้มนี้ อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | สามารถบรรจุข้อความที่มีรูปแบบ Rich. |
| [getTextFormat()](#getTextFormat--) | คืนค่ารูปแบบข้อความ. |
| [getChart()](#getChart--) | คืนค่าแผนภูมิก่อนหน้า. |
| [getSlide()](#getSlide--) | คืนค่าสไลด์พาเรนท์ของ FillFormat. |
| [getPresentation()](#getPresentation--) | คืนค่าการนำเสนอพาเรนท์ของ FillFormat. |
### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

รับหรือกำหนดชื่อของเส้นแนวโน้ม. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

รับหรือกำหนดชื่อของเส้นแนวโน้ม. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

รับหรือกำหนดประเภทของเส้นแนวโน้ม. อ่าน/เขียน [TrendlineType](../../com.aspose.slides/trendlinetype).

**คืนค่า:**  
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

รับหรือกำหนดประเภทของเส้นแนวโน้ม. อ่าน/เขียน [TrendlineType](../../com.aspose.slides/trendlinetype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

แสดงรูปแบบของเส้นแนวโน้ม. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**  
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

แสดงรูปแบบของเส้นแนวโน้ม. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public final double getBackward()
```

ระบุจำนวนหมวดหมู่ (หรือหน่วยในแผนภูมิแบบกระจาย) ที่เส้นแนวโน้มขยายก่อนข้อมูลของชุดข้อมูลที่กำลังทำแนวโน้ม. บนแผนภูมิแบบกระจายและไม่กระจาย ค่าจะต้องเป็นค่าที่ไม่เป็นลบ. อ่าน/เขียน double.

**คืนค่า:**  
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

ระบุจำนวนหมวดหมู่ (หรือหน่วยในแผนภูมิแบบกระจาย) ที่เส้นแนวโน้มขยายก่อนข้อมูลของชุดข้อมูลที่กำลังทำแนวโน้ม. บนแผนภูมิแบบกระจายและไม่กระจาย ค่าจะต้องเป็นค่าที่ไม่เป็นลบ. อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```

ระบุจำนวนหมวดหมู่ (หรือหน่วยในแผนภูมิแบบกระจาย) ที่เส้นแนวโน้มขยายหลังข้อมูลของชุดข้อมูลที่กำลังทำแนวโน้ม. บนแผนภูมิแบบกระจายและไม่กระจาย ค่าจะต้องเป็นค่าที่ไม่เป็นลบ. อ่าน/เขียน double.

**คืนค่า:**  
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

ระบุจำนวนหมวดหมู่ (หรือหน่วยในแผนภูมิแบบกระจาย) ที่เส้นแนวโน้มขยายหลังข้อมูลของชุดข้อมูลที่กำลังทำแนวโน้ม. บนแผนภูมิแบบกระจายและไม่กระจาย ค่าจะต้องเป็นค่าที่ไม่เป็นลบ. อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

ระบุค่าที่เส้นแนวโน้มจะตัดแกน Y. คุณสมบัตินี้จะรองรับเฉพาะเมื่อประเภทเส้นแนวโน้มเป็น exp, linear หรือ poly. อ่าน/เขียน double.

**คืนค่า:**  
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

ระบุค่าที่เส้นแนวโน้มจะตัดแกน Y. คุณสมบัตินี้จะรองรับเฉพาะเมื่อประเภทเส้นแนวโน้มเป็น exp, linear หรือ poly. อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

ระบุว่สมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายเดียวกับ Rsquaredvalue). อ่าน/เขียน boolean.

**คืนค่า:**  
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

ระบุว่สมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายเดียวกับ Rsquaredvalue). อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```

ระบุลำดับของเส้นแนวโน้มพหุนาม. จะถูกละเลยสำหรับประเภทเส้นแนวโน้มอื่น. ค่าต้องอยู่ระหว่าง 2 ถึง 6. อ่าน/เขียน byte.

**คืนค่า:**  
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

ระบุลำดับของเส้นแนวโน้มพหุนาม. จะถูกละเลยสำหรับประเภทเส้นแนวโน้มอื่น. ค่าต้องอยู่ระหว่าง 2 ถึง 6. อ่าน/เขียน byte.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

ระบุช่วงเวลาของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. จะถูกละเลยสำหรับประเภทเส้นแนวโน้มอื่น. ค่าต้องอยู่ระหว่าง 2 ถึง 255. อ่าน/เขียน byte.

**คืนค่า:**  
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

ระบุช่วงเวลาของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. จะถูกละเลยสำหรับประเภทเส้นแนวโน้มอื่น. ค่าต้องอยู่ระหว่าง 2 ถึง 255. อ่าน/เขียน byte.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายเดียวกับสมการ). อ่าน/เขียน boolean.

**คืนค่า:**  
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายเดียวกับสมการ). อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

แสดงรายการคำอธิบายสีที่เกี่ยวข้องกับเส้นแนวโน้มนี้ อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**คืนค่า:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ "text". หาก TextFrameForOverriding ถูกเริ่มต้นแล้วก็จะเปลี่ยนข้อความของมันเท่านั้น.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความสำหรับ TextFrameForOverriding ใหม่. |

**คืนค่า:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

สามารถบรรจุข้อความที่มีรูปแบบ Rich. หากค่าที่นี่ไม่เป็น null ข้อความที่จัดรูปแบบนี้จะทับข้อความที่สร้างโดยอัตโนมัติของป้ายข้อมูล. ข้อความที่สร้างโดยอัตโนมัติของป้ายข้อมูลหมายถึงข้อความที่จัดการโดยคุณสมบัติ ShowSeriesName, ShowValue, ... และจัดรูปแบบด้วยคุณสมบัติ TextFormatManager.TextFormat. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**คืนค่า:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

คืนค่ารูปแบบข้อความ. อ่านอย่างเดียว [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**คืนค่า:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

คืนค่าแผนภูมิก่อนหน้า. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**คืนค่า:**  
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนค่าสไลด์พาเรนท์ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**คืนค่า:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนค่าการนำเสนอพาเรนท์ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation)