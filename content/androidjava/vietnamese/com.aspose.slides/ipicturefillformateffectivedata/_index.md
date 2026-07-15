---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đối tượng bất biến chứa các thuộc tính của việc lấp đầy ảnh.
type: docs
url: /vi/com.aspose.slides/ipicturefillformateffectivedata/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

Đối tượng bất biến chứa các thuộc tính của việc lấp đầy ảnh.

--------------------

Giao diện này được sử dụng như một phần của [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getDpi()](#getDpi--) | Trả về dpi được sử dụng để lấp đầy ảnh. |
| [getPictureFillMode()](#getPictureFillMode--) | Trả về chế độ lấp đầy ảnh. |
| [getPicture()](#getPicture--) | Trả về ảnh. |
| [getCropLeft()](#getCropLeft--) | Trả về số phần trăm của chiều rộng ảnh thực tế bị cắt bỏ phía trái của ảnh. |
| [getCropTop()](#getCropTop--) | Trả về số phần trăm của chiều cao ảnh thực tế bị cắt bỏ phía trên của ảnh. |
| [getCropRight()](#getCropRight--) | Trả về số phần trăm của chiều rộng ảnh thực tế bị cắt bỏ phía phải của ảnh. |
| [getCropBottom()](#getCropBottom--) | Trả về số phần trăm của chiều cao ảnh thực tế bị cắt bỏ phía dưới của ảnh. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```


Trả về dpi được sử dụng để lấp đầy ảnh. Chỉ đọc int.

**Trả về:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```


Trả về chế độ lấp đầy ảnh. Chỉ đọc [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Trả về:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Trả về ảnh. Chỉ đọc [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Trả về:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```


Trả về số phần trăm của chiều rộng ảnh thực tế bị cắt bỏ phía trái của ảnh. Chỉ đọc float.

**Trả về:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```


Trả về số phần trăm của chiều cao ảnh thực tế bị cắt bỏ phía trên của ảnh. Chỉ đọc float.

**Trả về:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```


Trả về số phần trăm của chiều rộng ảnh thực tế bị cắt bỏ phía phải của ảnh. Chỉ đọc float.

**Trả về:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```


Trả về số phần trăm của chiều cao ảnh thực tế bị cắt bỏ phía dưới của ảnh. Chỉ đọc float.

**Trả về:**
float