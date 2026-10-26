---
title: BiLevel
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một hiệu ứng đen/trắng cấp độ đôi.
type: docs
url: /vi/com.aspose.slides/bilevel/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Represents a Bi-Level (black/white) effect. Input colors whose luminance is less than the specified threshold value are changed to black. Input colors whose luminance are greater than or equal the specified value are set to white. The alpha effect values are unaffected by this effect.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng Bi-Level đã áp dụng kế thừa. |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem [BiLevel](../../com.aspose.slides/bilevel) được chỉ định có bằng với [BiLevel](../../com.aspose.slides/bilevel) hiện tại hay không. |
| [hashCode()](#hashCode--) | Đóng vai trò như một hàm băm cho một kiểu nhất định. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```


Lấy dữ liệu hiệu ứng Bi-Level đã áp dụng kế thừa.

**Trả về:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - Một [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Xác định xem [BiLevel](../../com.aspose.slides/bilevel) được chỉ định có bằng với [BiLevel](../../com.aspose.slides/bilevel) hiện tại hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | Đối tượng [BiLevel](../../com.aspose.slides/bilevel) để so sánh. |

**Trả về:**
boolean - true nếu các đối tượng bằng nhau; ngược lại, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Đóng vai trò như một hàm băm cho một kiểu nhất định.

**Trả về:**
int - Một mã băm cho đối tượng hiện tại.