---
title: IPictureFrame
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một khung chứa hình ảnh bên trong.
type: docs
url: /vi/com.aspose.slides/ipictureframe/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

Biểu diễn một khung chứa hình ảnh bên trong.
## Methods

| Phương thức | Mô tả |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Trả về các khóa của PictureFrame. |
| [getPictureFormat()](#getPictureFormat--) | Trả về đối tượng PictureFillFormat cho một khung hình. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Trả về hoặc đặt tỷ lệ chiều cao (so với kích thước hình gốc) của khung hình. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Trả về hoặc đặt tỷ lệ chiều cao (so với kích thước hình gốc) của khung hình. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Trả về hoặc đặt tỷ lệ chiều rộng (so với kích thước hình gốc) của khung hình. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Trả về hoặc đặt tỷ lệ chiều rộng (so với kích thước hình gốc) của khung hình. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

Trả về các khóa của PictureFrame. Chỉ đọc [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Trả về:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

Trả về đối tượng PictureFillFormat cho một khung hình. Chỉ đọc [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Trả về:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

Trả về hoặc đặt tỷ lệ chiều cao (so với kích thước hình gốc) của khung hình. Giá trị 1.0 tương ứng với 100%. Đọc/ghi float.

**Trả về:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

Trả về hoặc đặt tỷ lệ chiều cao (so với kích thước hình gốc) của khung hình. Giá trị 1.0 tương ứng với 100%. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

Trả về hoặc đặt tỷ lệ chiều rộng (so với kích thước hình gốc) của khung hình. Giá trị 1.0 tương ứng với 100%. Đọc/ghi float.

**Trả về:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

Trả về hoặc đặt tỷ lệ chiều rộng (so với kích thước hình gốc) của khung hình. Giá trị 1.0 tương ứng với 100%. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |