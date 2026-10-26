---
title: IBaseChartValue
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a value of a chart.
type: docs
url: /vi/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Biểu diễn một giá trị của biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Xác định xem thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble là thực tế hay không. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Xác định xem thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble là thực tế hay không. |
| [getData()](#getData--) | Đọc/ghi Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Đọc/ghi Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Xác định xem thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble là thực tế hay không. Nói cách khác nó xác định loại giá trị của thuộc tính Data. Thuộc tính này chỉ đọc. Để thay đổi giá trị của thuộc tính này, bạn có thể sử dụng một trong các thuộc tính ChartDataPointCollection.DataSourceTypeFor<...>. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Trả về:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

Xác định xem thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble là thực tế hay không. Nói cách khác nó xác định loại giá trị của thuộc tính Data. Thuộc tính này chỉ đọc. Để thay đổi giá trị của thuộc tính này, bạn có thể sử dụng một trong các thuộc tính ChartDataPointCollection.DataSourceTypeFor<...>. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Đọc/ghi Object.

**Trả về:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Đọc/ghi Object.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.Object |  |