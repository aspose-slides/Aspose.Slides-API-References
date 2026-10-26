---
title: IActualLayout
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Xác định vị trí thực tế của một phần tử biểu đồ.
type: docs
url: /vi/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Xác định vị trí thực tế của một phần tử biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getActualX()](#getActualX--) | Xác định vị trí x thực tế (bên trái) của phần tử biểu đồ so với góc trái trên của biểu đồ. |
| [getActualY()](#getActualY--) | Xác định vị trí trên thực tế của phần tử biểu đồ so với góc trái trên của biểu đồ. |
| [getActualWidth()](#getActualWidth--) | Xác định chiều rộng thực tế của phần tử biểu đồ. |
| [getActualHeight()](#getActualHeight--) | Xác định chiều cao thực tế của phần tử biểu đồ. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

Xác định vị trí x thực tế (bên trái) của phần tử biểu đồ so với góc trái trên của biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy các giá trị thực tế. Đọc float.

**Trả về:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

Xác định vị trí trên thực tế của phần tử biểu đồ so với góc trái trên của biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy các giá trị thực tế. Đọc float.

**Trả về:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

Xác định chiều rộng thực tế của phần tử biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy các giá trị thực tế. Đọc float.

**Trả về:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

Xác định chiều cao thực tế của phần tử biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy các giá trị thực tế. Đọc float.

**Trả về:**
float