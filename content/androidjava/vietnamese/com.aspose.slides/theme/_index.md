---
title: Theme
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu thị một chủ đề.
type: docs
url: /vi/com.aspose.slides/theme/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

Biểu diễn một chủ đề.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Trả về bảng màu. |
| [getFontScheme()](#getFontScheme--) | Trả về bảng phông chữ. |
| [getFormatScheme()](#getFormatScheme--) | Trả về lược đồ định dạng hình dạng. |
| [getPresentation()](#getPresentation--) | Trả về bản trình chiếu cha. |
| [getEffective()](#getEffective--) | Lấy dữ liệu chủ đề hiệu quả với kế thừa đã được áp dụng. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

Trả về bảng màu. Chỉ đọc [IColorScheme](../../com.aspose.slides/icolorscheme).

**Trả về:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

Trả về bảng phông chữ. Chỉ đọc [IFontScheme](../../com.aspose.slides/ifontscheme).

**Trả về:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Trả về lược đồ định dạng hình dạng. Chỉ đọc [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Trả về:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bản trình chiếu cha. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

Lấy dữ liệu chủ đề hiệu quả với kế thừa đã được áp dụng.

--------------------

> ```
> This example demonstrates getting effective theme properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IThemeEffectiveData effectiveTheme  = pres.getSlides().get_Item(0).getThemeManager().getOverrideTheme().getEffective();
>  	System.out.println("Font scheme name: " + effectiveTheme.getFontScheme().getName());
>  	System.out.println("Major latin font: " + effectiveTheme.getFontScheme().getMajor().getLatinFont().getFontName());
>  	System.out.println("Minor latin font: " + effectiveTheme.getFontScheme().getMinor().getLatinFont().getFontName());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Trả về IPresentationComponent cha. Chỉ đọc [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Trả về:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

Phiên bản. Chỉ đọc long.

**Trả về:**
long