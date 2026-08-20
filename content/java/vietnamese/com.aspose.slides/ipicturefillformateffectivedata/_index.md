---
title: IPictureFillFormatEffectiveData
second_title: Tham khảo API Aspose.Slides cho Java
description: Đối tượng bất biến chứa các thuộc tính của việc lấp đầy bằng hình ảnh.
type: docs
url: /vi/com.aspose.slides/ipicturefillformateffectivedata/
---
**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

Đối tượng bất biến chứa các thuộc tính của việc lấp đầy bằng hình ảnh.

--------------------

Giao diện này được sử dụng như một phần của [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getDpi()](#getDpi--) | Trả về dpi được sử dụng để lấp đầy hình ảnh. |
| [getPictureFillMode()](#getPictureFillMode--) | Trả về chế độ lấp đầy hình ảnh. |
| [getPicture()](#getPicture--) | Trả về hình ảnh. |
| [getCropLeft()](#getCropLeft--) | Trả về số phần trăm của chiều rộng thực của hình ảnh bị cắt bỏ ở phía trái của hình. |
| [getCropTop()](#getCropTop--) | Trả về số phần trăm của chiều cao thực của hình ảnh bị cắt bỏ ở phía trên của hình. |
| [getCropRight()](#getCropRight--) | Trả về số phần trăm của chiều rộng thực của hình ảnh bị cắt bỏ ở phía phải của hình. |
| [getCropBottom()](#getCropBottom--) | Trả về số phần trăm của chiều cao thực của hình ảnh bị cắt bỏ ở phía dưới của hình. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Trả về dpi được sử dụng để lấp đầy hình ảnh. Chỉ đọc int.

**Returns:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Trả về chế độ lấp đầy hình ảnh. Chỉ đọc [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Returns:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

Trả về hình ảnh. Chỉ đọc [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Returns:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Trả về số phần trăm của chiều rộng thực của hình ảnh bị cắt bỏ ở phía trái của hình. Chỉ đọc float.

**Returns:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Trả về số phần trăm của chiều cao thực của hình ảnh bị cắt bỏ ở phía trên của hình. Chỉ đọc float.

**Returns:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Trả về số phần trăm của chiều rộng thực của hình ảnh bị cắt bỏ ở phía phải của hình. Chỉ đọc float.

**Returns:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Trả về số phần trăm của chiều cao thực của hình ảnh bị cắt bỏ ở phía dưới của hình. Chỉ đọc float.

**Returns:**
float