---
title: Picture
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một ảnh trong bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/picture/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Đại diện cho một ảnh trong bản trình chiếu.
## Phương thức

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Trả về hoặc thiết lập hình ảnh được nhúng. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Trả về hoặc thiết lập hình ảnh được nhúng. |
| [getLinkPathLong()](#getLinkPathLong--) | Trả về hoặc thiết lập URL của ảnh liên kết. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Trả về hoặc thiết lập URL của ảnh liên kết. |
| [getImageTransform()](#getImageTransform--) | Trả về tập hợp các hiệu ứng biến đổi ảnh. |
| [getPresentation()](#getPresentation--) | Trả về bản trình chiếu. |
| [equals(Object obj)](#equals-java.lang.Object-) | So sánh với đối tượng được chỉ định. |
| [hashCode()](#hashCode--) | Trả về giá trị băm. |
| [getSlide()](#getSlide--) | Trả về slide cha của ảnh. |
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


Trả về cha IPresentationComponent. Chỉ đọc [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Trả về:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```


Trả về hoặc thiết lập hình ảnh được nhúng. Đọc/ghi [IPPImage](../../com.aspose.slides/ippimage).

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```


Trả về hoặc thiết lập hình ảnh được nhúng. Đọc/ghi [IPPImage](../../com.aspose.slides/ippimage).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Trả về hoặc thiết lập URL của ảnh liên kết. Đọc/ghi String.

**Trả về:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Trả về hoặc thiết lập URL của ảnh liên kết. Đọc/ghi String.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```


Trả về tập hợp các hiệu ứng biến đổi ảnh. Chỉ đọc [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Trả về:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Trả về bản trình chiếu. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


So sánh với đối tượng được chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | |
| obj | java.lang.Object | Object to compare. |

**Trả về:**
boolean - Đúng nếu các đối tượng bằng nhau, ngược lại sai.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Trả về giá trị băm.

**Trả về:**
int - Giá trị băm.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Trả về slide cha của ảnh. Chỉ đọc [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)