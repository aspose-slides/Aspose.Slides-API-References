---
title: ColorOperation
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho các thao tác màu khác nhau được sử dụng cho việc biến đổi màu.
type: docs
url: /vi/com.aspose.slides/coloroperation/
---
**Kế thừa:**
java.lang.Object

**Tất cả Các Giao Diện Được Triển Khai:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Đại diện cho các thao tác màu khác nhau được sử dụng cho việc biến đổi màu. Đối tượng bất biến.

## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Tạo một thao tác biến đổi màu mới. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Tạo một thao tác biến đổi màu mới. |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getOperationType()](#getOperationType--) | Trả về hoặc thiết lập loại của một thao tác. |
| [getParameter()](#getParameter--) | Trả về một tham số của một thao tác. |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem hai thể hiện ColorOperation có bằng nhau hay không. |
| [hashCode()](#hashCode--) | Đóng vai trò là hàm băm cho một kiểu cụ thể, thích hợp để sử dụng trong các thuật toán băm và cấu trúc dữ liệu như bảng băm. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

Tạo một thao tác biến đổi màu mới.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| op | int | Kiểu thao tác. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

Tạo một thao tác biến đổi màu mới.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| op | int | Kiểu thao tác. |
| parameter | float | Tham số thao tác. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

Trả về hoặc thiết lập loại của một thao tác. Chỉ đọc [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Returns:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

Trả về một tham số của một thao tác. Chỉ đọc float.

**Returns:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Xác định xem hai thể hiện ColorOperation có bằng nhau hay không.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | ColorOperation để so sánh với ColorOperation hiện tại. |

**Returns:**
boolean - **true** nếu ColorOperation được chỉ định bằng với ColorOperation hiện tại; nếu không, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Đóng vai trò là hàm băm cho một kiểu cụ thể, thích hợp để sử dụng trong các thuật toán băm và cấu trúc dữ liệu như bảng băm.

**Returns:**
int