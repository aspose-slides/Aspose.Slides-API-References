---
title: IFillOverlay
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một hiệu ứng Fill Overlay.
type: docs
url: /vi/com.aspose.slides/ifilloverlay/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Đại diện cho một hiệu ứng Fill Overlay. Fill overlay có thể được sử dụng để chỉ định một lớp đổ màu bổ sung cho một đối tượng và pha trộn hai lớp đổ màu lại với nhau.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Định dạng tô. |
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

Định dạng tô. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)