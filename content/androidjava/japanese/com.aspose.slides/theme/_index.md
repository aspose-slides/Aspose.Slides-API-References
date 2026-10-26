---
title: Theme
second_title: Java API リファレンスを使用した Android 向け Aspose.Slides
description: テーマを表します。
type: docs
url: /ja/com.aspose.slides/theme/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject  
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

テーマを表します。

## メソッド

| Method | Description |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | カラースキームを返します。 |
| [getFontScheme()](#getFontScheme--) | フォントスキームを返します。 |
| [getFormatScheme()](#getFormatScheme--) | シェイプフォーマットスキームを返します。 |
| [getPresentation()](#getPresentation--) | 親プレゼンテーションを返します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効なテーマ データを取得します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |

### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

カラースキームを返します。読み取り専用 [IColorScheme](../../com.aspose.slides/icolorscheme)。

**返り値:**  
[IColorScheme](../../com.aspose.slides/icolorscheme)

### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

フォントスキームを返します。読み取り専用 [IFontScheme](../../com.aspose.slides/ifontscheme)。

**返り値:**  
[IFontScheme](../../com.aspose.slides/ifontscheme)

### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

シェイプフォーマットスキームを返します。読み取り専用 [IFormatScheme](../../com.aspose.slides/iformatscheme)。

**返り値:**  
[IFormatScheme](../../com.aspose.slides/iformatscheme)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

親プレゼンテーションを返します。読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**返り値:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

継承が適用された有効なテーマ データを取得します。

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


**返り値:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**返り値:**  
com.aspose.slides.IDOMObject

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

親 IPresentationComponent を返します。読み取り専用 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**返り値:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

バージョン。読み取り専用 long。

**返り値:**  
long