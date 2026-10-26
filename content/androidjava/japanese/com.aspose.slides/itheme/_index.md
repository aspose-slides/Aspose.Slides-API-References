---
title: ITheme
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: テーマを表します。
type: docs
url: /ja/com.aspose.slides/itheme/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

テーマを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | 色スキームを返します。 |
| [getFontScheme()](#getFontScheme--) | フォントスキームを返します。 |
| [getFormatScheme()](#getFormatScheme--) | シェイプ形式スキームを返します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効なテーマデータを取得します。 |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


色スキームを返します。読み取り専用 [IColorScheme](../../com.aspose.slides/icolorscheme)。

**戻り値:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


フォントスキームを返します。読み取り専用 [IFontScheme](../../com.aspose.slides/ifontscheme)。

**戻り値:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


シェイプ形式スキームを返します。読み取り専用 [IFormatScheme](../../com.aspose.slides/iformatscheme)。

**戻り値:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```


継承が適用された有効なテーマデータを取得します。

**戻り値:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).