---
title: IBaseChartValue
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงค่าของแผนภูมิ
type: docs
url: /th/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

แสดงค่าของแผนภูมิ
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริง |
| [setDataSourceType(int value)](#setDataSourceType-int-) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริง |
| [getData()](#getData--) | อ่าน/เขียน Object |
| [setData(Object value)](#setData-java.lang.Object-) | อ่าน/เขียน Object |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริง ในอีกแง่หนึ่งระบุประเภทของค่าที่ property Data มีอยู่ property นี้เป็นแบบอ่านอย่างเดียว สำหรับการเปลี่ยนค่าของ property นี้คุณสามารถใช้หนึ่งใน property ChartDataPointCollection.DataSourceTypeFor<...> ได้ อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int))

**ส่งคืน:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริง ในอีกแง่หนึ่งระบุประเภทของค่าที่ property Data มีอยู่ property นี้เป็นแบบอ่านอย่างเดียว สำหรับการเปลี่ยนค่าของ property นี้คุณสามารถใช้หนึ่งใน property ChartDataPointCollection.DataSourceTypeFor<...> ได้ อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int))

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

อ่าน/เขียน Object

**ส่งคืน:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

อ่าน/เขียน Object

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |