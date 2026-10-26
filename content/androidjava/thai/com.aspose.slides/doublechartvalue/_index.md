---
title: DoubleChartValue
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API Java
description: แสดงค่าชนิด double ซึ่งสามารถจัดเก็บในเอกสารพรีเซนเทชัน pptx ได้สองวิธี 1) ในเซล/เซลของเวิร์กบุ๊กที่เกี่ยวข้องกับแผนภูมิ 2) เป็นค่าตัวอักษรโดยตรง.
type: docs
url: /th/com.aspose.slides/doublechartvalue/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**อินเทอร์เฟซที่ทำการนำไปใช้ทั้งหมด:**  
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)  
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

เป็นค่าชนิด double ที่สามารถจัดเก็บในเอกสารพรีเซนเทชัน pptx ได้สองวิธี: 1) ในเซล/เซลของเวิร์กบุ๊กที่เกี่ยวข้องกับแผนภูมิ; 2) เป็นค่าตัวอักษรโดยตรง.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAsCell()](#getAsCell--) | คืนค่า หรือ กำหนดเซลข้อมูลแผนภูมิ |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | คืนค่า หรือ กำหนดเซลข้อมูลแผนภูมิ |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | คืนค่า หรือ กำหนดค่าเป็น literal double |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | คืนค่า หรือ กำหนดค่าเป็น literal double |
| [getData()](#getData--) | คืนค่า หรือ กำหนด Data object |
| [setData(Object value)](#setData-java.lang.Object-) | คืนค่า หรือ กำหนด Data object |
| [toDouble()](#toDouble--) | แปลงเป็น double |

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

คืนค่า หรือ กำหนดเซลข้อมูลแผนภูมิ. อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**คืนค่า:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

คืนค่า หรือ กำหนดเซลข้อมูลแผนภูมิ. อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

คืนค่า หรือ กำหนดค่าเป็น literal double. อ่าน/เขียน double.

**คืนค่า:**
double

### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

คืนค่า หรือ กำหนดค่าเป็น literal double. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

คืนค่า หรือ กำหนด Data object. อ่าน/เขียน Object.

**คืนค่า:**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

คืนค่า หรือ กำหนด Data object. อ่าน/เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```

แปลงเป็น double.

**คืนค่า:**
double - คืนค่า LiteralDouble หาก DataSourceType เท่ากับ DoubleLiterals. หาก DataSourceType เท่ากับ Worksheet จะคืนค่าที่แปลงเป็น double จากค่าเซลสำเร็จ, มิฉะนั้นจะคืนค่า NaN.