---
title: TextAnimation
second_title: Tham chiếu API Aspose.Slides cho Java
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

Đại diện cho hoạt ảnh văn bản.
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Thêm hiệu ứng mới vào cuối chuỗi hiện tại để cuối các hoạt ảnh văn bản nhóm. |
| [getBuildType()](#getBuildType--) | Danh sách loại xây dựng (cho ví dụ. |
| [setBuildType(int value)](#setBuildType-int-) | Danh sách loại xây dựng (cho ví dụ. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Hiệu ứng hình dạng liên kết với nhóm hoặc không (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Hiệu ứng hình dạng liên kết với nhóm hoặc không (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


Thêm hiệu ứng mới vào cuối chuỗi hiện tại để cuối các hoạt ảnh văn bản nhóm. Chỉ hợp lệ nếu số đoạn văn bản bằng hoặc lớn hơn số hiệu ứng của nhóm này!

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| effectType | int | Loại hiệu ứng hoạt ảnh [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Kiểu phụ của hiệu ứng hoạt ảnh [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Kiểu kích hoạt của hiệu ứng [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Trả về:**
[IEffect](../../com.aspose.slides/ieffect) - Đối tượng hiệu ứng mới [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


Danh sách loại xây dựng (ví dụ: Đoạn 1,2,3, Tất cả cùng lúc) của hoạt ảnh văn bản. Đọc/ghi [BuildType](../../com.aspose.slides/buildtype).

**Trả về:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


Danh sách loại xây dựng (ví dụ: Đoạn 1,2,3, Tất cả cùng lúc) của hoạt ảnh văn bản. Đọc/ghi [BuildType](../../com.aspose.slides/buildtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```


Hiệu ứng hình dạng liên kết với nhóm hoặc không (null). Đọc/ghi [IEffect](../../com.aspose.slides/ieffect).

**Trả về:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


Hiệu ứng hình dạng liên kết với nhóm hoặc không (null). Đọc/ghi [IEffect](../../com.aspose.slides/ieffect).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |