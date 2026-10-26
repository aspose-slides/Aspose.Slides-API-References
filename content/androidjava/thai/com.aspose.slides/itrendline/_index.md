---
title: ITrendline
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: คลาสที่แสดงเส้นแนวโน้มของชุดข้อมูลในแผนภูมิ
type: docs
url: /th/com.aspose.slides/itrendline/
---
**ส่วนติดต่อที่ทำงานทั้งหมด:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Class represents trend line of chart series
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | รับหรือกำหนดชื่อของเส้นแนวโน้ม. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | รับหรือกำหนดชื่อของเส้นแนวโน้ม. |
| [getTrendlineType()](#getTrendlineType--) | รับหรือกำหนดประเภทของเส้นแนวโน้ม. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | รับหรือกำหนดประเภทของเส้นแนวโน้ม. |
| [getFormat()](#getFormat--) | แสดงรูปแบบของเส้นแนวโน้ม. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | แสดงรูปแบบของเส้นแนวโน้ม. |
| [getBackward()](#getBackward--) | ระบุตัวเลขของประเภท (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายออกไปก่อนข้อมูลของซีรีส์ที่กำลังเทรนด์. |
| [setBackward(double value)](#setBackward-double-) | ระบุตัวเลขของประเภท (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายออกไปก่อนข้อมูลของซีรีส์ที่กำลังเทรนด์. |
| [getForward()](#getForward--) | ระบุตัวเลขของประเภท (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายออกไปหลังข้อมูลของซีรีส์ที่กำลังเทรนด์. |
| [setForward(double value)](#setForward-double-) | ระบุตัวเลขของประเภท (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายออกไปหลังข้อมูลของซีรีส์ที่กำลังเทรนด์. |
| [getIntercept()](#getIntercept--) | ระบุค่าที่เส้นแนวโน้มจะตัดแกน y. |
| [setIntercept(double value)](#setIntercept-double-) | ระบุค่าที่เส้นแนวโน้มจะตัดแกน y. |
| [getDisplayEquation()](#getDisplayEquation--) | ระบุว่าสมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายชื่อเดียวกับค่า Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | ระบุว่าสมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายชื่อเดียวกับค่า Rsquaredvalue). |
| [getOrder()](#getOrder--) | ระบุลำดับของเส้นแนวโน้มพหุนาม. |
| [setOrder(byte value)](#setOrder-byte-) | ระบุลำดับของเส้นแนวโน้มพหุนาม. |
| [getPeriod()](#getPeriod--) | ระบุระยะเวลาของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. |
| [setPeriod(byte value)](#setPeriod-byte-) | ระบุระยะเวลาของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายชื่อเดียวกับสมการ). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายชื่อเดียวกับสมการ). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | แสดงรายการคำอธิบายที่เกี่ยวข้องกับเส้นแนวโน้มนี้ อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |

### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

รับหรือกำหนดชื่อของเส้นแนวโน้ม อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

รับหรือกำหนดชื่อของเส้นแนวโน้ม อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

รับหรือกำหนดประเภทของเส้นแนวโน้ม อ่าน/เขียน [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**คืนค่า:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

รับหรือกำหนดประเภทของเส้นแนวโน้ม อ่าน/เขียน [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

แสดงรูปแบบของเส้นแนวโน้ม อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

แสดงรูปแบบของเส้นแนวโน้ม อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

ระบุตัวเลขของประเภท (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายออกไปก่อนข้อมูลของซีรีส์ที่กำลังเทรนด์. บนแผนภูมิกระจายและแผนภูมิอื่นๆ ค่าต้องเป็นค่าที่ไม่เป็นลบ. อ่าน/เขียน double.

**คืนค่า:**
double

### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

ระบุตัวเลขของประเภท (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายออกไปก่อนข้อมูลของซีรีส์ที่กำลังเทรนด์. บนแผนภูมิกระจายและแผนภูมิอื่นๆ ค่าต้องเป็นค่าที่ไม่เป็นลบ. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public abstract double getForward()
```

ระบุตัวเลขของประเภท (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายออกไปหลังข้อมูลของซีรีส์ที่กำลังเทรนด์. บนแผนภูมิกระจายและแผนภูมิอื่นๆ ค่าต้องเป็นค่าที่ไม่เป็นลบ. อ่าน/เขียน double.

**คืนค่า:**
double

### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

ระบุตัวเลขของประเภท (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายออกไปหลังข้อมูลของซีรีส์ที่กำลังเทรนด์. บนแผนภูมิกระจายและแผนภูมิอื่นๆ ค่าต้องเป็นค่าที่ไม่เป็นลบ. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

ระบุค่าที่เส้นแนวโน้มจะตัดแกน y. คุณสมบัตินี้สนับสนุนเฉพาะเมื่อประเภทเส้นแนวโน้มเป็น exp, linear หรือ poly. อ่าน/เขียน double.

**คืนค่า:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

ระบุค่าที่เส้นแนวโน้มจะตัดแกน y. คุณสมบัตินี้สนับสนุนเฉพาะเมื่อประเภทเส้นแนวโน้มเป็น exp, linear หรือ poly. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

ระบุว่าสมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายชื่อเดียวกับค่า Rsquaredvalue). อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

ระบุว่าสมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายชื่อเดียวกับค่า Rsquaredvalue). อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

ระบุลำดับของเส้นแนวโน้มพหุนาม. จะถูกละเว้นสำหรับประเภทเส้นแนวโน้มอื่น. ค่าต้องอยู่ระหว่าง 2 ถึง 6. อ่าน/เขียน byte.

**คืนค่า:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

ระบุลำดับของเส้นแนวโน้มพหุนาม. จะถูกละเว้นสำหรับประเภทเส้นแนวโน้มอื่น. ค่าต้องอยู่ระหว่าง 2 ถึง 6. อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

ระบุระยะเวลาของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. จะถูกละเว้นสำหรับรูปแบบเส้นแนวโน้มอื่น. ค่าต้องอยู่ระหว่าง 2 ถึง 255. อ่าน/เขียน byte.

**คืนค่า:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

ระบุระยะเวลาของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. จะถูกละเว้นสำหรับรูปแบบเส้นแนวโน้มอื่น. ค่าต้องอยู่ระหว่าง 2 ถึง 255. อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายชื่อเดียวกับสมการ). อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายชื่อเดียวกับสมการ). อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

แสดงรายการคำอธิบายที่เกี่ยวข้องกับเส้นแนวโน้มนี้ อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**คืนค่า:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)