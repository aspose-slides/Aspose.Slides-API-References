---
title: ColorOperation
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Biểu diễn các thao tác màu khác nhau được sử dụng cho các phép biến đổi màu.
type: docs
url: /vi/com.aspose.slides/coloroperation/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Biểu diễn các thao tác màu khác nhau được sử dụng cho các phép biến đổi màu. Đối tượng bất biến.
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Tạo một thao tác biến đổi màu mới. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Tạo một thao tác biến đổi màu mới. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getOperationType()](#getOperationType--) | Trả về hoặc đặt kiểu của một thao tác. |
| [getParameter()](#getParameter--) | Trả về một tham số của một thao tác. |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem hai thể hiện ColorOperation có bằng nhau không. |
| [hashCode()](#hashCode--) | Đóng vai trò như một hàm băm cho một kiểu cụ thể, phù hợp để sử dụng trong các thuật toán băm và cấu trúc dữ liệu như bảng băm. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```


Tạo một thao tác biến đổi màu mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| op | int | Kiểu thao tác. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```


Tạo một thao tác biến đổi màu mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| op | int | Kiểu thao tác. |
| parameter | float | Tham số của thao tác. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```


Trả về hoặc đặt kiểu của một thao tác. Chỉ đọc [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Trả về:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```


Trả về một tham số của một thao tác. Chỉ đọc float.

**Trả về:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Xác định xem hai thể hiện ColorOperation có bằng nhau không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | ColorOperation để so sánh với ColorOperation hiện tại. |

**Trả về:**
boolean - **true** nếu ColorOperation được chỉ định bằng với ColorOperation hiện tại; nếu không, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Đóng vai trò như một hàm băm cho một kiểu cụ thể, phù hợp để sử dụng trong các thuật toán băm và cấu trúc dữ liệu như bảng băm.

**Trả về:**
int