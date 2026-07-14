---
title: ErrorBarsFormat
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงบาร์ความคลาดเคลื่อนของชุดข้อมูลแผนภูมิ.
type: docs
url: /th/com.aspose.slides/errorbarsformat/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**ทั้งหมดของอินเทอร์เฟซที่ใช้งาน:**  
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)  
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

Represents error bars of chart series. ErrorBars custom values are in IChartDataPointCollection (in ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

## เมธอด

| Method | Description |
| --- | --- |
| [getType()](#getType--) | รับหรือกำหนดประเภทของบาร์ความคลาดเคลื่อน. |
| [setType(int value)](#setType-int-) | รับหรือกำหนดประเภทของบาร์ความคลาดเคลื่อน. |
| [getValueType()](#getValueType--) | แสดงวิธีที่เป็นไปได้ในการกำหนดความยาวของบาร์ความคลาดเคลื่อน. |
| [setValueType(int value)](#setValueType-int-) | แสดงวิธีที่เป็นไปได้ในการกำหนดความยาวของบาร์ความคลาดเคลื่อน. |
| [hasEndCap()](#hasEndCap--) | ระบุว่าหัวปลายไม่ได้ถูกวาดบนบาร์ความคลาดเคลื่อน. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | ระบุว่าหัวปลายไม่ได้ถูกวาดบนบาร์ความคลาดเคลื่อน. |
| [getValue()](#getValue--) | รับหรือกำหนดค่าที่ใช้ร่วมกับ Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของบาร์ความคลาดเคลื่อน. |
| [setValue(float value)](#setValue-float-) | รับหรือกำหนดค่าที่ใช้ร่วมกับ Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของบาร์ความคลาดเคลื่อน. |
| [getFormat()](#getFormat--) | แสดงรูปแบบของบาร์ความคลาดเคลื่อน. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | แสดงรูปแบบของบาร์ความคลาดเคลื่อน. |
| [getChart()](#getChart--) | คืนค่าแผนภูมิกำเนิด. |
| [isVisible()](#isVisible--) | รับหรือกำหนดการมองเห็นของ Error Bars. |
| [setVisible(boolean value)](#setVisible-boolean-) | รับหรือกำหนดการมองเห็นของ Error Bars. |
| [getSlide()](#getSlide--) | คืนค่าสไลด์แม่ของ FillFormat. |
| [getPresentation()](#getPresentation--) | คืนค่าการนำเสนอแม่ของ FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

รับหรือกำหนดประเภทของบาร์ความคลาดเคลื่อน. อ่าน/เขียน [ErrorBarType](../../com.aspose.slides/errorbartype).

**คืนค่า:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

รับหรือกำหนดประเภทของบาร์ความคลาดเคลื่อน. อ่าน/เขียน [ErrorBarType](../../com.aspose.slides/errorbartype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

แสดงวิธีที่เป็นไปได้ในการกำหนดความยาวของบาร์ความคลาดเคลื่อน. ในกรณีของประเภทค่า custom ให้ใช้คุณสมบัติ ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) ของจุดข้อมูลเฉพาะในคอลเลกชัน DataPoints ของชุดข้อมูล. ในกรณีของประเภทค่า Fixed, Percentage หรือ StandardDeviation ให้ใช้คุณสมบัติ Value เพื่อระบุค่า. อ่าน/เขียน [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**คืนค่า:**  
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

แสดงวิธีที่เป็นไปได้ในการกำหนดความยาวของบาร์ความคลาดเคลื่อน. ในกรณีของประเภทค่า custom ให้ใช้คุณสมบัติ ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) ของจุดข้อมูลเฉพาะในคอลเลกชัน DataPoints ของชุดข้อมูล. ในกรณีของประเภทค่า Fixed, Percentage หรือ StandardDeviation ให้ใช้คุณสมบัติ Value เพื่อระบุค่า. อ่าน/เขียน [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

ระบุว่าหัวปลายไม่ได้ถูกวาดบนบาร์ความคลาดเคลื่อน. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

ระบุว่าหัวปลายไม่ได้ถูกวาดบนบาร์ความคลาดเคลื่อน. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

รับหรือกำหนดค่าที่ใช้ร่วมกับ Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของบาร์ความคลาดเคลื่อน. ในกรณีอื่นจะคืนค่า NaN. อ่าน/เขียน float.

**คืนค่า:**  
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

รับหรือกำหนดค่าที่ใช้ร่วมกับ Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของบาร์ความคลาดเคลื่อน. ในกรณีอื่นจะคืนค่า NaN. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

แสดงรูปแบบของบาร์ความคลาดเคลื่อน. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

แสดงรูปแบบของบาร์ความคลาดเคลื่อน. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

คืนค่าแผนภูมิกำเนิด. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**คืนค่า:**  
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

รับหรือกำหนดการมองเห็นของ Error Bars. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

รับหรือกำหนดการมองเห็นของ Error Bars. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนค่าสไลด์แม่ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**คืนค่า:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนค่าการนำเสนอแม่ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation)