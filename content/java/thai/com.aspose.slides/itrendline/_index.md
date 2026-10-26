---
title: ITrendline
second_title: Aspose.Slides สำหรับ Java API เอกสารอ้างอิง
description: คลาสที่แสดงถึงเส้นแนวโน้มของชุดข้อมูลแผนภูมิ
type: docs
url: /th/com.aspose.slides/itrendline/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

คลาสแสดงถึงเส้นแนวโน้มของชุดข้อมูลแผนภูมิ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | รับหรือกำหนดชื่อของเส้นแนวโน้ม. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | รับหรือกำหนดชื่อของเส้นแนวโน้ม. |
| [getTrendlineType()](#getTrendlineType--) | รับหรือกำหนดประเภทของเส้นแนวโน้ม. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | รับหรือกำหนดประเภทของเส้นแนวโน้ม. |
| [getFormat()](#getFormat--) | แสดงรูปแบบของเส้นแนวโน้ม. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | แสดงรูปแบบของเส้นแนวโน้ม. |
| [getBackward()](#getBackward--) | ระบุจำนวนหมวดหมู่ (หรือหน่วยบนแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายไปก่อนข้อมูลของชุดที่กำลังทำแนวโน้ม. |
| [setBackward(double value)](#setBackward-double-) | ระบุจำนวนหมวดหมู่ (หรือหน่วยบนแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายไปก่อนข้อมูลของชุดที่กำลังทำแนวโน้ม. |
| [getForward()](#getForward--) | ระบุจำนวนหมวดหมู่ (หรือหน่วยบนแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายไปหลังข้อมูลของชุดที่กำลังทำแนวโน้ม. |
| [setForward(double value)](#setForward-double-) | ระบุจำนวนหมวดหมู่ (หรือหน่วยบนแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายไปหลังข้อมูลของชุดที่กำลังทำแนวโน้ม. |
| [getIntercept()](#getIntercept--) | ระบุค่าที่เส้นแนวโน้มตัดแกน y. |
| [setIntercept(double value)](#setIntercept-double-) | ระบุค่าที่เส้นแนวโน้มตัดแกน y. |
| [getDisplayEquation()](#getDisplayEquation--) | ระบุว่าคสมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายกำกับเดียวกับค่า Rsquared). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | ระบุว่าคสมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายกำกับเดียวกับค่า Rsquared). |
| [getOrder()](#getOrder--) | ระบุลำดับของเส้นแนวโน้มพหุนาม. |
| [setOrder(byte value)](#setOrder-byte-) | ระบุลำดับของเส้นแนวโน้มพหุนาม. |
| [getPeriod()](#getPeriod--) | ระบุช่วงเวลาของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. |
| [setPeriod(byte value)](#setPeriod-byte-) | ระบุช่วงเวลาของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายกำกับเดียวกับสมการ). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายกำกับเดียวกับสมการ). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | แสดงรายการคำอธิบายในตำนานที่เกี่ยวข้องกับเส้นแนวโน้มนี้ อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |

### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

รับหรือกำหนดชื่อของเส้นแนวโน้ม. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

รับหรือกำหนดชื่อของเส้นแนวโน้ม. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

รับหรือกำหนดประเภทของเส้นแนวโน้ม. อ่าน/เขียน [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**คืนค่า:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

รับหรือกำหนดประเภทของเส้นแนวโน้ม. อ่าน/เขียน [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

แสดงรูปแบบของเส้นแนวโน้ม. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

แสดงรูปแบบของเส้นแนวโน้ม. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

ระบุจำนวนหมวดหมู่ (หรือหน่วยบนแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายไปก่อนข้อมูลของชุดที่กำลังทำแนวโน้ม. บนแผนภูมิกระจายและแผนภูมิที่ไม่ใช่การกระจาย, ค่าจะต้องเป็นค่าที่ไม่เป็นลบ. อ่าน/เขียน double.

**คืนค่า:**
double

### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

ระบุจำนวนหมวดหมู่ (หรือหน่วยบนแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายไปก่อนข้อมูลของชุดที่กำลังทำแนวโน้ม. บนแผนภูมิกระจายและแผนภูมิที่ไม่ใช่การกระจาย, ค่าจะต้องเป็นค่าที่ไม่เป็นลบ. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public abstract double getForward()
```

ระบุจำนวนหมวดหมู่ (หรือหน่วยบนแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายไปหลังข้อมูลของชุดที่กำลังทำแนวโน้ม. บนแผนภูมิกระจายและแผนภูมิที่ไม่ใช่การกระจาย, ค่าจะต้องเป็นค่าที่ไม่เป็นลบ. อ่าน/เขียน double.

**คืนค่า:**
double

### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

ระบุจำนวนหมวดหมู่ (หรือหน่วยบนแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายไปหลังข้อมูลของชุดที่กำลังทำแนวโน้ม. บนแผนภูมิกระจายและแผนภูมิที่ไม่ใช่การกระจาย, ค่าจะต้องเป็นค่าที่ไม่เป็นลบ. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

ระบุค่าที่เส้นแนวโน้มตัดแกน y. คุณสมบัตินี้จะสนับสนุนเฉพาะเมื่อประเภทเส้นแนวโน้มเป็น exp, linear หรือ poly. อ่าน/เขียน double.

**คืนค่า:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

ระบุค่าที่เส้นแนวโน้มตัดแกน y. คุณสมบัตินี้จะสนับสนุนเฉพาะเมื่อประเภทเส้นแนวโน้มเป็น exp, linear หรือ poly. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

ระบุว่าคสมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายกำกับเดียวกับค่า Rsquaredvalue). อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

ระบุว่าคสมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายกำกับเดียวกับค่า Rsquaredvalue). อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

ระบุลำดับของเส้นแนวโน้มพหุนาม. จะถูกละเลยสำหรับประเภทเส้นแนวโน้มอื่น. ค่าต้องอยู่ระหว่าง 2 ถึง 6. อ่าน/เขียน byte.

**คืนค่า:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

ระบุลำดับของเส้นแนวโน้มพหุนาม. จะถูกละเลยสำหรับประเภทเส้นแนวโน้มอื่น. ค่าต้องอยู่ระหว่าง 2 ถึง 6. อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

ระบุช่วงเวลาของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. จะถูกละเลยสำหรับประเภทเส้นแนวโน้มอื่น. ค่าต้องอยู่ระหว่าง 2 ถึง 255. อ่าน/เขียน byte.

**คืนค่า:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

ระบุช่วงเวลาของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. จะถูกละเลยสำหรับประเภทเส้นแนวโน้มอื่น. ค่าต้องอยู่ระหว่าง 2 ถึง 255. อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายกำกับเดียวกับสมการ). อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายกำกับเดียวกับสมการ). อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

แสดงรายการคำอธิบายในตำนานที่เกี่ยวข้องกับเส้นแนวโน้มนี้ อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**คืนค่า:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)