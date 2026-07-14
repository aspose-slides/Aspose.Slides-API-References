---
title: IBaseChartValue
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงค่าหนึ่งของแผนภูมิ
type: docs
url: /th/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

แสดงค่าหนึ่งของแผนภูมิ
## Methods

| Method | Description |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าที่ใช้งานจริงหรือไม่ |
| [setDataSourceType(int value)](#setDataSourceType-int-) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าที่ใช้งานจริงหรือไม่ |
| [getData()](#getData--) | อ่าน/เขียน Object. |
| [setData(Object value)](#setData-java.lang.Object-) | อ่าน/เขียน Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าที่ใช้งานจริงหรือไม่. กล่าวคือ มันระบุประเภทของค่าของ property Data. property นี้อ่านอย่างเดียว. เพื่อเปลี่ยนค่าของ property นี้ คุณสามารถใช้หนึ่งใน property ของ ChartDataPointCollection.DataSourceTypeFor<...> ได้. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**คืนค่า:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าที่ใช้งานจริงหรือไม่. กล่าวคือ มันระบุประเภทของค่าของ property Data. property นี้อ่านอย่างเดียว. เพื่อเปลี่ยนค่าของ property นี้ คุณสามารถใช้หนึ่งใน property ของ ChartDataPointCollection.DataSourceTypeFor<...> ได้. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

อ่าน/เขียน Object.

**คืนค่า:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

อ่าน/เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |