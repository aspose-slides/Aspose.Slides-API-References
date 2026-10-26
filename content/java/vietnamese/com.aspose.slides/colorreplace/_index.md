---
title: ColorReplace
second_title: Tham khảo API Aspose.Slides cho Java
description: Đại diện cho một hiệu ứng Thay thế màu.
type: docs
url: /vi/com.aspose.slides/colorreplace/
---
**Inheritance:**  
Kế thừa: java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**  
Tất cả các giao diện đã triển khai: [com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Đại diện cho một hiệu ứng Color Replacement. Tất cả màu của hiệu ứng được thay đổi thành một màu cố định. Giá trị Alpha không bị ảnh hưởng.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getColor()](#getColor--) | Trả về định dạng màu sẽ thay thế màu của mỗi pixel. |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng Color Replacement thực tế với tính kế thừa đã được áp dụng. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem [ColorReplace](../../com.aspose.slides/colorreplace) được chỉ định có bằng với [ColorReplace](../../com.aspose.slides/colorreplace) hiện tại hay không. |
| [hashCode()](#hashCode--) | Được sử dụng như một hàm băm cho một kiểu cụ thể. |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Trả về định dạng màu sẽ thay thế màu của mỗi pixel. **Chỉ đọc** [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

Lấy dữ liệu hiệu ứng Color Replacement thực tế với tính kế thừa đã được áp dụng.

**Trả về:**  
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - A [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. **Chỉ đọc** long.

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
boolean - true nếu các đối tượng bằng nhau; ngược lại, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Được sử dụng như một hàm băm cho một kiểu cụ thể.

**Trả về:**  
int - Mã băm cho đối tượng hiện tại.