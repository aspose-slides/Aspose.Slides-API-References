---
title: BaseChartValue
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นค่าของแผนภูมิ.
type: docs
url: /th/com.aspose.slides/basechartvalue/
---
**Inheritance:**  
การสืบทอด:

**All Implemented Interfaces:**  
อินเทอร์เฟซที่ถูกนำไปใช้ทั้งหมด:  
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject  
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Represents a value of a chart.  
เป็นค่าของแผนภูมิ

## Methods  
## เมธอด

| Method | Description |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | ระบุว่า property AsCell, AsCells, AsLiteralString หรือ AsLiteralDouble เป็น property ที่ใช้งานได้ในคลาสสืบทอดหรือไม่. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | ระบุว่า property AsCell, AsCells, AsLiteralString หรือ AsLiteralDouble เป็น property ที่ใช้งานได้ในคลาสสืบทอดหรือไม่. |
| [getData()](#getData--) | ข้อมูล. |
| [setData(Object value)](#setData-java.lang.Object-) | ข้อมูล. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

ระบุว่า property AsCell, AsCells, AsLiteralString หรือ AsLiteralDouble เป็น property ที่ใช้งานได้ในคลาสสืบทอดหรือไม่. ในคำอื่น ๆ มันระบุประเภทของค่าของ property Data. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

สำหรับจุดใน ChartDataPointCollection property นี้เป็นอ่านอย่างเดียว. ในกรณีนี้หากต้องการเปลี่ยนค่าของ property นี้คุณสามารถใช้หนึ่งใน property ChartDataPointCollection.DataSourceTypeFor<...> ได้.

**Returns:**  
คืนค่า:  
int

### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

ระบุว่า property AsCell, AsCells, AsLiteralString หรือ AsLiteralDouble เป็น property ที่ใช้งานได้ในคลาสสืบทอดหรือไม่. ในคำอื่น ๆ มันระบุประเภทของค่าของ property Data. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

สำหรับจุดใน ChartDataPointCollection property นี้เป็นอ่านอย่างเดียว. ในกรณีนี้หากต้องการเปลี่ยนค่าของ property นี้คุณสามารถใช้หนึ่งใน property ChartDataPointCollection.DataSourceTypeFor<...> ได้.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

ข้อมูล. อ่าน/เขียน Object.

**Returns:**  
คืนค่า:  
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

ข้อมูล. อ่าน/เขียน Object.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่า Parent_Immediate object. อ่านอย่างเดียว IDOMObject.

**Returns:**  
คืนค่า:  
com.aspose.slides.IDOMObject