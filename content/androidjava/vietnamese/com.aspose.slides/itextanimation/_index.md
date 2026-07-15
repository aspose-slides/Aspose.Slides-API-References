---
title: ITextAnimation
second_title: Aspose.Slides for Android via Java API Reference
description: Represent text animation.
type: docs
url: /vi/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Biểu diễn hoạt ảnh văn bản.

## Phương thức

| Method | Description |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Thêm hiệu ứng mới vào cuối chuỗi hiện tại đến cuối các hoạt ảnh văn bản nhóm. |
| [getBuildType()](#getBuildType--) | Danh sách loại xây dựng (ví dụ |
| [setBuildType(int value)](#setBuildType-int-) | Danh sách loại xây dựng (ví dụ |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Hiệu ứng hình dạng liên kết có nhóm hay không (null) Đọc/ghi [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Hiệu ứng hình dạng liên kết có nhóm hay không (null) Đọc/ghi [IEffect](../../com.aspose.slides/ieffect). |

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

Thêm hiệu ứng mới vào cuối chuỗi hiện tại đến cuối các hoạt ảnh văn bản nhóm. Chỉ hợp lệ nếu số đoạn văn bản bằng hoặc lớn hơn số hiệu ứng của nhóm này!

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| effectType | int | Kiểu của hiệu ứng hoạt ảnh [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Các kiểu phụ của hiệu ứng hoạt ảnh [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Kiểu kích hoạt của hiệu ứng [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Giá trị trả về:**
[IEffect](../../com.aspose.slides/ieffect) - đối tượng hiệu ứng mới [IEffect](../../com.aspose.slides/ieffect)

### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

Danh sách loại xây dựng (ví dụ Đoạn 1,2,3, Tất cả cùng lúc) của hoạt ảnh văn bản. Đọc/ghi \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Giá trị trả về:**
int

### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

Danh sách loại xây dựng (ví dụ Đoạn 1,2,3, Tất cả cùng lúc) của hoạt ảnh văn bản. Đọc/ghi \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

Hiệu ứng hình dạng liên kết có nhóm hay không (null) Đọc/ghi [IEffect](../../com.aspose.slides/ieffect).

**Giá trị trả về:**
[IEffect](../../com.aspose.slides/ieffect)

### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

Hiệu ứng hình dạng liên kết có nhóm hay không (null) Đọc/ghi [IEffect](../../com.aspose.slides/ieffect).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |