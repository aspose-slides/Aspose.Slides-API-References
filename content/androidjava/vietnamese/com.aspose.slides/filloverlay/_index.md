---
title: FillOverlay
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một hiệu ứng Fill Overlay.
type: docs
url: /vi/com.aspose.slides/filloverlay/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Đại diện cho một hiệu ứng Fill Overlay. Một fill overlay có thể được sử dụng để chỉ định một lớp phủ bổ sung cho một đối tượng và pha trộn hai lớp phủ lại với nhau.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Định dạng Fill. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng Fill Overlay có hiệu lực với tính kế thừa đã được áp dụng. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem [FillOverlay](../../com.aspose.slides/filloverlay) được chỉ định có bằng với [FillOverlay](../../com.aspose.slides/filloverlay) hiện tại hay không. |
| [hashCode()](#hashCode--) | Đóng vai trò như một hàm băm cho một kiểu cụ thể. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Fill format. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. Đọc/ghi [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Trả về:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. Đọc/ghi [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

Lấy dữ liệu hiệu ứng Fill Overlay có hiệu lực với tính kế thừa đã được áp dụng.

**Trả về:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - A [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Chỉ đọc long.

**Trả về:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Xác định xem [FillOverlay](../../com.aspose.slides/filloverlay) được chỉ định có bằng với [FillOverlay](../../com.aspose.slides/filloverlay) hiện tại hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | [FillOverlay](../../com.aspose.slides/filloverlay) để so sánh. |

**Trả về:**
boolean - true nếu các đối tượng bằng nhau; ngược lại, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Đóng vai trò như một hàm băm cho một kiểu cụ thể.

**Trả về:**
int - Một mã băm cho đối tượng hiện tại.