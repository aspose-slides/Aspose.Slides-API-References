---
title: ColorChange
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu thị một hiệu ứng Color Change.
type: docs
url: /vi/com.aspose.slides/colorchange/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Biểu thị một hiệu ứng Color Change. Các thể hiện của FromColor được thay thế bằng các thể hiện của ToColor.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFromColor()](#getFromColor--) | Màu sẽ được thay thế. |
| [getToColor()](#getToColor--) | Màu sẽ thay thế. |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng Color Change hiệu quả với việc kế thừa đã được áp dụng. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem [ColorChange](../../com.aspose.slides/colorchange) được chỉ định có bằng với [ColorChange](../../com.aspose.slides/colorchange) hiện tại hay không. |
| [hashCode()](#hashCode--) | Phục vụ như một hàm băm cho một kiểu cụ thể. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```


Màu sẽ được thay thế. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```


Màu sẽ thay thế. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```


Lấy dữ liệu hiệu ứng Color Change hiệu quả với việc kế thừa đã được áp dụng.

**Trả về:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - Một [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
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


Xác định xem [ColorChange](../../com.aspose.slides/colorchange) được chỉ định có bằng với [ColorChange](../../com.aspose.slides/colorchange) hiện tại hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | [ColorChange](../../com.aspose.slides/colorchange) để so sánh. |

**Trả về:**
boolean - true nếu các đối tượng bằng nhau; nếu không, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Phục vụ như một hàm băm cho một kiểu cụ thể.

**Trả về:**
int - Một mã băm cho đối tượng hiện tại.