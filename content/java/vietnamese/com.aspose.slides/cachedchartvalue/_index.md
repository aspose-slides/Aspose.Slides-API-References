---
title: CachedChartValue
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một giá trị biểu đồ được lưu tạm, ví dụ: X, Y, kích thước bong bóng hoặc giá trị chính.
type: docs
url: /vi/com.aspose.slides/cachedchartvalue/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

Biểu diễn một giá trị biểu đồ được lưu trữ tạm thời (ví dụ: X, Y, kích thước bong bóng, hoặc giá trị chính).
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [toString()](#toString--) | Trả về một biểu diễn chuỗi của giá trị đã lưu. |
| [toDouble()](#toDouble--) | Chuyển đổi giá trị đã lưu thành kiểu double. |
| [getData()](#getData--) | Lấy đối tượng dữ liệu đã lưu. |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```


### toString() {#toString--}
```
public String toString()
```


Trả về một biểu diễn chuỗi của giá trị đã lưu.

**Trả về:**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```


Chuyển đổi giá trị đã lưu thành kiểu double.

**Trả về:**
double - Đại diện số học, hoặc Double.NaN nếu Data (\#getData.getData/\#setData(Object).setData(Object)) là null hoặc không thể chuyển đổi sang double.
### getData() {#getData--}
```
public final Object getData()
```


Lấy đối tượng dữ liệu đã lưu. Read-only  Object .

**Trả về:**
java.lang.Object