---
title: ICachedChartValue
second_title: Tài liệu tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một giá trị biểu đồ được lưu trong bộ nhớ cache, ví dụ: X, Y, kích thước bong bóng hoặc giá trị chính.
type: docs
url: /vi/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

Biểu diễn một giá trị biểu đồ được lưu trong bộ nhớ cache (ví dụ: X, Y, kích thước bong bóng, hoặc giá trị chính).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getData()](#getData--) | Lấy đối tượng dữ liệu đã được lưu trong bộ nhớ cache. |
| [toDouble()](#toDouble--) | Chuyển đổi giá trị đã được lưu trong bộ nhớ cache thành kiểu double. |
### getData() {#getData--}
```
public abstract Object getData()
```


Lấy đối tượng dữ liệu đã được lưu trong bộ nhớ cache. Chỉ đọc  Object .

**Trả về:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Chuyển đổi giá trị đã được lưu trong bộ nhớ cache thành kiểu double.

**Trả về:**
double - Đại diện số học, hoặc Double.NaN nếu Data (\#getData.getData) là null hoặc không thể được chuyển đổi thành kiểu double.