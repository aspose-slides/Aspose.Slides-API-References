---
title: Background
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện nền của một slide.
type: docs
url: /vi/com.aspose.slides/background/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Biểu diễn nền của một slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getType()](#getType--) | Trả về một kiểu tô nền. |
| [setType(byte value)](#setType-byte-) | Trả về một kiểu tô nền. |
| [getFillFormat()](#getFillFormat--) | Trả về một FillFormat cho nền BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Trả về một EffectFormat cho nền BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Trả về một ColorFormat cho nền BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Trả về chỉ số của nền BackgroundType.Themed trong bộ sưu tập chủ đề nền. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Trả về chỉ số của nền BackgroundType.Themed trong bộ sưu tập chủ đề nền. |
| [getEffective()](#getEffective--) | Lấy dữ liệu nền hiệu quả với kế thừa đã được áp dụng. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Trả về slide cha của một shape. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của một slide. |
### getType() {#getType--}
```
public final byte getType()
```

Trả về một kiểu nền được tô đầy. Đọc/ghi [BackgroundType](../../com.aspose.slides/backgroundtype).

**Trả về:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Trả về một kiểu nền được tô đầy. Đọc/ghi [BackgroundType](../../com.aspose.slides/backgroundtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Trả về một FillFormat cho nền BackgroundType.OwnBackground. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Trả về một EffectFormat cho nền BackgroundType.OwnBackground. Chỉ đọc [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Trả về:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

Trả về một ColorFormat cho nền BackgroundType.Themed. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

Trả về chỉ số của nền BackgroundType.Themed trong bộ sưu tập chủ đề nền. 0 có nghĩa là không có nền. 1..999 - chỉ số. Đọc/ghi int.

**Trả về:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

Trả về chỉ số của nền BackgroundType.Themed trong bộ sưu tập chủ đề nền. 0 có nghĩa là không có nền. 1..999 - chỉ số. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

Lấy dữ liệu nền hiệu quả với kế thừa đã được áp dụng.

--------------------

> ```
> This example demonstrates getting effective background properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IBackgroundEffectiveData effectiveBackground = pres.getSlides().get_Item(0).getBackground().getEffective();
>  	System.out.println("Background fill type: " + effectiveBackground.getFillFormat().getFillType());
>  	System.out.println("Any effects applied: " + !effectiveBackground.getEffectFormat().isNoEffects());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - Một [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Chỉ đọc long.

**Trả về:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

Trả về slide cha của một shape. Chỉ đọc [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Trả về:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

Trả về bản trình bày cha của một slide. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[Presentation](../../com.aspose.slides/presentation)