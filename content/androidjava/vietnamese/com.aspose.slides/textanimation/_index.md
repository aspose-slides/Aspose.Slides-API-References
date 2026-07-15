---
title: TextAnimation
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho hoạt ảnh văn bản.
type: docs
url: /vi/com.aspose.slides/textanimation/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Biểu diễn hoạt ảnh văn bản.
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Thêm hiệu ứng mới vào cuối chuỗi hiện tại của các hoạt ảnh văn bản nhóm. |
| [getBuildType()](#getBuildType--) | Danh sách kiểu xây dựng (ví dụ |
| [setBuildType(int value)](#setBuildType-int-) | Danh sách kiểu xây dựng (ví dụ |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Hiệu ứng hình dạng liên kết có nhóm hay không (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Hiệu ứng hình dạng liên kết có nhóm hay không (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```

Thêm hiệu ứng mới vào cuối chuỗi hiện tại của các hoạt ảnh văn bản nhóm. Chỉ hợp lệ nếu số đoạn văn bản bằng hoặc lớn hơn số hiệu ứng của nhóm này!

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| effectType | int | Loại hiệu ứng hoạt ảnh [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Các kiểu phụ của hiệu ứng hoạt ảnh [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Kiểu kích hoạt của hiệu ứng [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Giá trị trả về:**
[IEffect](../../com.aspose.slides/ieffect) - Đối tượng hiệu ứng mới [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```

Danh sách kiểu xây dựng (ví dụ Đoạn văn 1,2,3, Tất cả cùng lúc) của hoạt ảnh văn bản. Đọc/ghi [BuildType](../../com.aspose.slides/buildtype).

**Giá trị trả về:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```

Danh sách kiểu xây dựng (ví dụ Đoạn văn 1,2,3, Tất cả cùng lúc) của hoạt ảnh văn bản. Đọc/ghi [BuildType](../../com.aspose.slides/buildtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```

Hiệu ứng hình dạng liên kết có nhóm hay không (null). Đọc/ghi [IEffect](../../com.aspose.slides/ieffect).

**Giá trị trả về:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```

Hiệu ứng hình dạng liên kết có nhóm hay không (null). Đọc/ghi [IEffect](../../com.aspose.slides/ieffect).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |