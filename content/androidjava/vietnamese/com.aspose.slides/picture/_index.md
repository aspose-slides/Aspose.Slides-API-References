---
title: Picture
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một hình ảnh trong bản trình bày.
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

Biểu diễn một hình ảnh trong bài thuyết trình.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Trả về hoặc đặt hình ảnh được nhúng. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Trả về hoặc đặt hình ảnh được nhúng. |
| [getLinkPathLong()](#getLinkPathLong--) | Trả về hoặc đặt URL của hình ảnh được liên kết. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Trả về hoặc đặt URL của hình ảnh được liên kết. |
| [getImageTransform()](#getImageTransform--) | Trả về bộ sưu tập các hiệu ứng biến đổi hình ảnh. |
| [getPresentation()](#getPresentation--) | Trả về bài thuyết trình. |
| [equals(Object obj)](#equals-java.lang.Object-) | So sánh với đối tượng đã chỉ định. |
| [hashCode()](#hashCode--) | Trả về hash. |
| [getSlide()](#getSlide--) | Trả về slide cha của một hình ảnh. |
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

Trả về hoặc đặt hình ảnh được nhúng. Đọc/ghi [IPPImage](../../com.aspose.slides/ippimage).

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

Trả về hoặc đặt hình ảnh được nhúng. Đọc/ghi [IPPImage](../../com.aspose.slides/ippimage).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Trả về hoặc đặt URL của hình ảnh được liên kết. Đọc/ghi String.

**Trả về:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Trả về hoặc đặt URL của hình ảnh được liên kết. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

Trả về bộ sưu tập các hiệu ứng biến đổi hình ảnh. Chỉ đọc [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Trả về:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bài thuyết trình. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

So sánh với đối tượng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | Đối tượng để so sánh. |

**Trả về:**
boolean - Đúng nếu các đối tượng bằng nhau, ngược lại sai.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Trả về hash.

**Trả về:**
int - Hash.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Trả về slide cha của một hình ảnh. Chỉ đọc [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)