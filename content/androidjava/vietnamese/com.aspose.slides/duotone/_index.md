---
title: Duotone
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Mô tả một hiệu ứng Duotone.
type: docs
url: /vi/com.aspose.slides/duotone/
---
**Kế thừa:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tất cả giao diện được triển khai:**  
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect  
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Mô tả một hiệu ứng Duotone. Đối với mỗi pixel, kết hợp Color1 và Color2 thông qua nội suy tuyến tính để xác định màu mới cho pixel đó.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getColor1()](#getColor1--) | Trả về định dạng màu mục tiêu cho các pixel tối. |
| [getColor2()](#getColor2--) | Trả về định dạng màu mục tiêu cho các pixel sáng. |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng Duotone đã áp dụng kế thừa. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem [Duotone](../../com.aspose.slides/duotone) được chỉ định có bằng với [Duotone](../../com.aspose.slides/duotone) hiện tại hay không. |
| [hashCode()](#hashCode--) | Đóng vai trò như một hàm băm cho một kiểu cụ thể. |

### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

Trả về định dạng màu mục tiêu cho các pixel tối. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

Trả về định dạng màu mục tiêu cho các pixel sáng. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

Lấy dữ liệu hiệu ứng Duotone đã áp dụng kế thừa.

**Trả về:**  
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - Một [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Chỉ đọc long.

**Trả về:**  
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Xác định xem [Duotone](../../com.aspose.slides/duotone) được chỉ định có bằng với [Duotone](../../com.aspose.slides/duotone) hiện tại hay không.

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | [Duotone](../../com.aspose.slides/duotone) để so sánh. |

**Trả về:**  
boolean - true nếu các đối tượng bằng nhau; ngược lại, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Đóng vai trò như một hàm băm cho một kiểu cụ thể.

**Trả về:**  
int - Một mã băm cho đối tượng hiện tại.