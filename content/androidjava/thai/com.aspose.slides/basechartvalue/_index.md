---
title: BaseChartValue
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของค่าของแผนภูมิ.
type: docs
url: /th/com.aspose.slides/basechartvalue/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

เป็นตัวแทนของค่าของแผนภูมิ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | ระบุว่าคุณสมบัติ AsCell, AsCells, AsLiteralString หรือ AsLiteralDouble มีอยู่ในคลาสลูกหรือไม่. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | ระบุว่าคุณสมบัติ AsCell, AsCells, AsLiteralString หรือ AsLiteralDouble มีอยู่ในคลาสลูกหรือไม่. |
| [getData()](#getData--) | Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Data. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

ระบุว่าคุณสมบัติ AsCell, AsCells, AsLiteralString หรือ AsLiteralDouble มีอยู่ในคลาสลูกหรือไม่ ในทางอื่นหมายความว่ากำหนดประเภทของค่าของคุณสมบัติ Data. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

สำหรับจุดใน ChartDataPointCollection คุณสมบัตินี้เป็นอ่านอย่างเดียว ในกรณีนี้เพื่อเปลี่ยนค่าของคุณสมบัตินี้คุณสามารถใช้หนึ่งในคุณสมบัติ ChartDataPointCollection.DataSourceTypeFor<...>.

**คืนค่า:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

ระบุว่าคุณสมบัติ AsCell, AsCells, AsLiteralString หรือ AsLiteralDouble มีอยู่ในคลาสลูกหรือไม่ ในทางอื่นหมายความว่ากำหนดประเภทของค่าของคุณสมบัติ Data. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

สำหรับจุดใน ChartDataPointCollection คุณสมบัตินี้เป็นอ่านอย่างเดียว ในกรณีนี้เพื่อเปลี่ยนค่าของคุณสมบัตินี้คุณสามารถใช้หนึ่งในคุณสมบัติ ChartDataPointCollection.DataSourceTypeFor<...>.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Data. อ่าน/เขียน Object.

**คืนค่า:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Data. อ่าน/เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject