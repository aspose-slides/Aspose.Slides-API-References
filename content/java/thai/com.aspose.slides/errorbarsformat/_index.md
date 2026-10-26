---
title: ErrorBarsFormat
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงแท่งข้อผิดพลาดของชุดข้อมูลแผนภูมิ.
type: docs
url: /th/com.aspose.slides/errorbarsformat/
---
**สืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)  
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

แสดงแถบข้อผิดพลาดของชุดข้อมูลแผนภูมิ. ค่าที่กำหนดเองของ ErrorBars อยู่ใน IChartDataPointCollection (ในคุณสมบัติ ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getType()](#getType--) | รับหรือกำหนดประเภทของแถบข้อผิดพลาด. |
| [setType(int value)](#setType-int-) | รับหรือกำหนดประเภทของแถบข้อผิดพลาด. |
| [getValueType()](#getValueType--) | แสดงวิธีที่เป็นไปได้ในการกำหนดความยาวของแถบข้อผิดพลาด. |
| [setValueType(int value)](#setValueType-int-) | แสดงวิธีที่เป็นไปได้ในการกำหนดความยาวของแถบข้อผิดพลาด. |
| [hasEndCap()](#hasEndCap--) | ระบุว่าปลายแคปจะไม่ถูกวาดบนแถบข้อผิดพลาด. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | ระบุว่าปลายแคปจะไม่ถูกวาดบนแถบข้อผิดพลาด. |
| [getValue()](#getValue--) | รับหรือกำหนดค่าที่ใช้ร่วมกับประเภทค่า Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของแถบข้อผิดพลาด. |
| [setValue(float value)](#setValue-float-) | รับหรือกำหนดค่าที่ใช้ร่วมกับประเภทค่า Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของแถบข้อผิดพลาด. |
| [getFormat()](#getFormat--) | แสดงรูปแบบของแถบข้อผิดพลาด. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | แสดงรูปแบบของแถบข้อผิดพลาด. |
| [getChart()](#getChart--) | ส่งคืนแผนภูมิแม่. |
| [isVisible()](#isVisible--) | รับหรือกำหนดการมองเห็นของแถบข้อผิดพลาด. |
| [setVisible(boolean value)](#setVisible-boolean-) | รับหรือกำหนดการมองเห็นของแถบข้อผิดพลาด. |
| [getSlide()](#getSlide--) | ส่งคืนสไลด์แม่ของ FillFormat. |
| [getPresentation()](#getPresentation--) | ส่งคืนงานนำเสนอแม่ของ FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

รับหรือกำหนดประเภทของแถบข้อผิดพลาด. อ่าน/เขียน [ErrorBarType](../../com.aspose.slides/errorbartype).

**คืนค่า:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

รับหรือกำหนดประเภทของแถบข้อผิดพลาด. อ่าน/เขียน [ErrorBarType](../../com.aspose.slides/errorbartype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

แสดงวิธีที่เป็นไปได้ในการกำหนดความยาวของแถบข้อผิดพลาด. ในกรณีของประเภทค่าที่กำหนดเองเพื่อระบุค่าให้ใช้คุณสมบัติ ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) ของจุดข้อมูลเฉพาะในคอลเลกชัน DataPoints ของชุดข้อมูล. ในกรณีของประเภทค่า Fixed, Percentage หรือ StandardDeviation ให้ใช้คุณสมบัติ Value เพื่อระบุค่า. อ่าน/เขียน [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**คืนค่า:**  
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

แสดงวิธีที่เป็นไปได้ในการกำหนดความยาวของแถบข้อผิดพลาด. ในกรณีของประเภทค่าที่กำหนดเองเพื่อระบุค่าให้ใช้คุณสมบัติ ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) ของจุดข้อมูลเฉพาะในคอลเลกชัน DataPoints ของชุดข้อมูล. ในกรณีของประเภทค่า Fixed, Percentage หรือ StandardDeviation ให้ใช้คุณสมบัติ Value เพื่อระบุค่า. อ่าน/เขียน [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

ระบุว่าปลายแคปจะไม่ถูกวาดบนแถบข้อผิดพลาด. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

ระบุว่าปลายแคปจะไม่ถูกวาดบนแถบข้อผิดพลาด. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

รับหรือกำหนดค่าที่ใช้ร่วมกับประเภทค่า Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของแถบข้อผิดพลาด. ในกรณีอื่นๆ จะคืนค่า NaN. อ่าน/เขียน float.

**คืนค่า:**  
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

รับหรือกำหนดค่าที่ใช้ร่วมกับประเภทค่า Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของแถบข้อผิดพลาด. ในกรณีอื่นๆ จะคืนค่า NaN. อ่าน/เขียน float.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

แสดงรูปแบบของแถบข้อผิดพลาด. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

แสดงรูปแบบของแถบข้อผิดพลาด. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

ส่งคืนแผนภูมิแม่. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**คืนค่า:**  
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

รับหรือกำหนดการมองเห็นของแถบข้อผิดพลาด. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

รับหรือกำหนดการมองเห็นของแถบข้อผิดพลาด. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

ส่งคืนสไลด์แม่ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**คืนค่า:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ส่งคืนงานนำเสนอแม่ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation)