---
title: Glow
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một hiệu ứng Glow, trong đó một đường viền màu mờ được thêm vào bên ngoài các cạnh của đối tượng.
type: docs
url: /vi/com.aspose.slides/glow/
---
**Kế thừa:**
java.lang.Object

**Tất cả giao diện được thực thi:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Biểu diễn một hiệu ứng Glow, trong đó một đường viền màu mờ được thêm vào bên ngoài các cạnh của đối tượng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRadius()](#getRadius--) | Bán kính. |
| [setRadius(double value)](#setRadius-double-) | Bán kính. |
| [getColor()](#getColor--) | Định dạng màu. |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng Glow đã áp dụng kế thừa. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem [Glow](../../com.aspose.slides/glow) được chỉ định có bằng với [Glow](../../com.aspose.slides/glow) hiện tại hay không. |
| [hashCode()](#hashCode--) | Đóng vai trò như hàm băm cho một kiểu nhất định. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Bán kính. Đọc/ghi  double .

**Trả về:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Bán kính. Đọc/ghi  double .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Định dạng màu. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```


Lấy dữ liệu hiệu ứng Glow đã áp dụng kế thừa.

**Trả về:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - một [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Phiên bản. Chỉ đọc long.

**Trả về:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Trả về IPresentationComponent cha. Chỉ đọc [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Trả về:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Xác định xem [Glow](../../com.aspose.slides/glow) được chỉ định có bằng với [Glow](../../com.aspose.slides/glow) hiện tại hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | [Glow](../../com.aspose.slides/glow) để so sánh. |

**Trả về:**
boolean - true nếu các đối tượng bằng nhau; ngược lại, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Đóng vai trò như hàm băm cho một kiểu nhất định.

**Trả về:**
int - Một mã băm cho đối tượng hiện tại.