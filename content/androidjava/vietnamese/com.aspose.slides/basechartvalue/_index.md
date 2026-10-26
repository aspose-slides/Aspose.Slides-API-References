---
title: BaseChartValue
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu thị một giá trị của biểu đồ.
type: docs
url: /vi/com.aspose.slides/basechartvalue/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Biểu thị một giá trị của biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Xác định xem thuộc tính AsCell, AsCells, AsLiteralString hoặc AsLiteralDouble có thực tế trong các lớp con hay không. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Xác định xem thuộc tính AsCell, AsCells, AsLiteralString hoặc AsLiteralDouble có thực tế trong các lớp con hay không. |
| [getData()](#getData--) | Dữ liệu. |
| [setData(Object value)](#setData-java.lang.Object-) | Dữ liệu. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```


Xác định xem thuộc tính AsCell, AsCells, AsLiteralString hoặc AsLiteralDouble có thực tế trong các lớp con hay không. Nói cách khác, nó chỉ định loại giá trị của thuộc tính Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Đối với các điểm trong ChartDataPointCollection, thuộc tính này chỉ đọc. Trong trường hợp này, để thay đổi giá trị của thuộc tính này, bạn có thể sử dụng một trong các thuộc tính ChartDataPointCollection.DataSourceTypeFor<...>.

**Giá trị trả về:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```


Xác định xem thuộc tính AsCell, AsCells, AsLiteralString hoặc AsLiteralDouble có thực tế trong các lớp con hay không. Nói cách khác, nó chỉ định loại giá trị của thuộc tính Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Đối với các điểm trong ChartDataPointCollection, thuộc tính này chỉ đọc. Trong trường hợp này, để thay đổi giá trị của thuộc tính này, bạn có thể sử dụng một trong các thuộc tính ChartDataPointCollection.DataSourceTypeFor<...>.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getData() {#getData--}
```
public abstract Object getData()
```


Dữ liệu. Đọc/ghi Object.

**Giá trị trả về:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Dữ liệu. Đọc/ghi Object.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.Object |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Giá trị trả về:**
com.aspose.slides.IDOMObject