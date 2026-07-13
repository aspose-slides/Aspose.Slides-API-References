---
title: Theme
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili tema.
type: docs
url: /id/com.aspose.slides/theme/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

Mewakili tema.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Mengembalikan skema warna. |
| [getFontScheme()](#getFontScheme--) | Mengembalikan skema font. |
| [getFormatScheme()](#getFormatScheme--) | Mengembalikan skema format shape. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk. |
| [getEffective()](#getEffective--) | Mendapatkan data tema yang efektif dengan pewarisan yang diterapkan. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

Mengembalikan skema warna. Hanya-baca [IColorScheme](../../com.aspose.slides/icolorscheme).

**Mengembalikan:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

Mengembalikan skema font. Hanya-baca [IFontScheme](../../com.aspose.slides/ifontscheme).

**Mengembalikan:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Mengembalikan skema format shape. Hanya-baca [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Mengembalikan:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk. Hanya-baca [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

Mendapatkan data tema yang efektif dengan pewarisan yang diterapkan.

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


**Mengembalikan:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Sebuah [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Mengembalikan IPresentationComponent induk. Hanya-baca [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Mengembalikan:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

Versi. Hanya-baca long.

**Mengembalikan:**
long