---
title: IErrorBarsFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นการแทนค่า error bars ของชุดข้อมูลแผนภูมิ
type: docs
url: /th/com.aspose.slides/ierrorbarsformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Represents error bars of chart series. ErrorBars custom values are in IChartDataPointCollection (in [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) property).

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getType()](#getType--) | Gets or sets type of error bars. |
| [setType(int value)](#setType-int-) | Gets or sets type of error bars. |
| [getValueType()](#getValueType--) | Represents possible ways to determine the length of the error bars. |
| [setValueType(int value)](#setValueType-int-) | Represents possible ways to determine the length of the error bars. |
| [hasEndCap()](#hasEndCap--) | Specifies an end cap is not drawn on the error bars. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Specifies an end cap is not drawn on the error bars. |
| [getValue()](#getValue--) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. |
| [setValue(float value)](#setValue-float-) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. |
| [getFormat()](#getFormat--) | Represents the format of the error bars. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Represents the format of the error bars. |
| [isVisible()](#isVisible--) | Gets or sets Error Bars visibility. |
| [setVisible(boolean value)](#setVisible-boolean-) | Gets or sets Error Bars visibility. |
### getType() {#getType--}
```
public abstract int getType()
```

รับหรือกำหนดประเภทของ error bars. อ่าน/เขียน [ErrorBarType](../../com.aspose.slides/errorbartype).

**คืนค่า:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

รับหรือกำหนดประเภทของ error bars. อ่าน/เขียน [ErrorBarType](../../com.aspose.slides/errorbartype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Represents possible ways to determine the length of the error bars. In case of custom value type to specify value use [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) property of specific data point in DataPoints collection of series. อ่าน/เขียน [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**คืนค่า:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Represents possible ways to determine the length of the error bars. In case of custom value type to specify value use [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) property of specific data point in DataPoints collection of series. อ่าน/เขียน [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

ระบุว่าปลายแคปจะไม่ถูกวาดบน error bars. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

ระบุว่าปลายแคปจะไม่ถูกวาดบน error bars. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

รับหรือกำหนดค่า ที่ใช้กับ Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของ error bars. อ่าน/เขียน float.

**คืนค่า:**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

รับหรือกำหนดค่า ที่ใช้กับ Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของ error bars. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Represents the format of the error bars. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Represents the format of the error bars. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

รับหรือกำหนดการมองเห็นของ Error Bars. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

รับหรือกำหนดการมองเห็นของ Error Bars. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |