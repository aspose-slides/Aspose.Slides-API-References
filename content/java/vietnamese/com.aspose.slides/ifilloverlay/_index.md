---
title: IFillOverlay
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một hiệu ứng Fill Overlay.
type: docs
url: /vi/com.aspose.slides/ifilloverlay/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Biểu diễn hiệu ứng Fill Overlay. Fill overlay có thể được sử dụng để chỉ định một màu nền bổ sung cho một đối tượng và trộn hai màu nền lại với nhau.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Định dạng Fill. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```

FillBlendMode. Đọc/ghi [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Trả về:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```

FillBlendMode. Đọc/ghi [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Định dạng Fill. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)