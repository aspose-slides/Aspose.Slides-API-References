---
title: ColorReplace
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đại diện cho một hiệu ứng Thay thế màu.
type: docs
url: /vi/com.aspose.slides/colorreplace/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Đại diện cho một hiệu ứng Color Replacement. Tất cả các màu của hiệu ứng được chuyển thành một màu cố định. Các giá trị Alpha không bị ảnh hưởng.
## Phương thức

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Trả về định dạng màu sẽ thay thế màu của mỗi pixel. |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng Color Replacement hiệu lực với tính kế thừa đã được áp dụng. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem [ColorReplace](../../com.aspose.slides/colorreplace) được chỉ định có bằng với [ColorReplace](../../com.aspose.slides/colorreplace) hiện tại hay không. |
| [hashCode()](#hashCode--) | Đóng vai trò như một hàm băm cho một kiểu cụ thể. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Trả về định dạng màu sẽ thay thế màu của mỗi pixel. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

Lấy dữ liệu hiệu ứng Color Replacement hiệu lực với tính kế thừa đã được áp dụng.

**Trả về:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - Một [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Long chỉ đọc.

**Trả về:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Xác định xem [ColorReplace](../../com.aspose.slides/colorreplace) được chỉ định có bằng với [ColorReplace](../../com.aspose.slides/colorreplace) hiện tại hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | Đối tượng [ColorReplace](../../com.aspose.slides/colorreplace) để so sánh. |

**Trả về:**
boolean - true nếu các đối tượng bằng nhau; nếu không, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Đóng vai trò như một hàm băm cho một kiểu cụ thể.

**Trả về:**
int - Một mã băm cho đối tượng hiện tại.