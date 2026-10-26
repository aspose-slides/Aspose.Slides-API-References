---
title: ISlidesPicture
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một hình ảnh trong bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/islidespicture/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Biểu diễn một hình ảnh trong bản trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getImage()](#getImage--) | Trả về hoặc thiết lập hình ảnh được nhúng. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Trả về hoặc thiết lập hình ảnh được nhúng. |
| [getLinkPathLong()](#getLinkPathLong--) | Trả về hoặc thiết lập URL của hình ảnh được liên kết. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Trả về hoặc thiết lập URL của hình ảnh được liên kết. |
| [getImageTransform()](#getImageTransform--) | Trả về bộ sưu tập các hiệu ứng biến đổi hình ảnh. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

Trả về hoặc thiết lập hình ảnh được nhúng. Đọc/ghi [IPPImage](../../com.aspose.slides/ippimage).

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

Trả về hoặc thiết lập hình ảnh được nhúng. Đọc/ghi [IPPImage](../../com.aspose.slides/ippimage).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Trả về hoặc thiết lập URL của hình ảnh được liên kết. Đọc/ghi String.

**Trả về:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Trả về hoặc thiết lập URL của hình ảnh được liên kết. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

Trả về bộ sưu tập các hiệu ứng biến đổi hình ảnh. Chỉ đọc [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Trả về:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)