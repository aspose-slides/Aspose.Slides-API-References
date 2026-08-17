---
title: ITheme
second_title: Aspose.Slides for Java API リファレンス
description: テーマを表します。
type: docs
url: /ja/com.aspose.slides/itheme/
---
**実装されたすべてのインターフェース:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

テーマを表します。
## メソッド

| Method | Description |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | 色スキームを返します。 |
| [getFontScheme()](#getFontScheme--) | フォントスキームを返します。 |
| [getFormatScheme()](#getFormatScheme--) | シェイプフォーマットスキームを返します。 |
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

シェイプフォーマットスキームを返します。読み取り専用 [IFormatScheme](../../com.aspose.slides/iformatscheme)。

**戻り値:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```

継承が適用された有効なテーマデータを取得します。

**戻り値:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - ある [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).