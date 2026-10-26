---
title: SoftEdge
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một hiệu ứng cạnh mềm.
type: docs
url: /vi/com.aspose.slides/softedge/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Biểu diễn một hiệu ứng cạnh mềm. Các cạnh của hình được làm mờ, trong khi phần nền không bị ảnh hưởng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRadius()](#getRadius--) | Xác định bán kính làm mờ sẽ áp dụng cho các cạnh. |
| [setRadius(double value)](#setRadius-double-) | Xác định bán kính làm mờ sẽ áp dụng cho các cạnh. |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng Soft Edge thực tế với tính kế thừa đã được áp dụng. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem [SoftEdge](../../com.aspose.slides/softedge) đã chỉ định có bằng với [SoftEdge](../../com.aspose.slides/softedge) hiện tại hay không. |
| [hashCode()](#hashCode--) | Đóng vai trò là hàm băm cho một kiểu cụ thể. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Xác định bán kính làm mờ sẽ áp dụng cho các cạnh. Đọc/ghi double.

**Trả về:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Xác định bán kính làm mờ sẽ áp dụng cho các cạnh. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

Lấy dữ liệu hiệu ứng Soft Edge thực tế với tính kế thừa đã được áp dụng.

**Trả về:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - A [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
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

Xác định xem [SoftEdge](../../com.aspose.slides/softedge) đã chỉ định có bằng với [SoftEdge](../../com.aspose.slides/softedge) hiện tại hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | [SoftEdge](../../com.aspose.slides/softedge) để so sánh. |

**Trả về:**
boolean - true nếu các đối tượng bằng nhau; nếu không, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Đóng vai trò là hàm băm cho một kiểu cụ thể.

**Trả về:**
int - Mã băm cho đối tượng hiện tại.