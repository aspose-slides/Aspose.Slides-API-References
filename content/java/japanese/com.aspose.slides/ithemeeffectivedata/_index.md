---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective theme properties.
type: docs
url: /ja/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

効果的なテーマプロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは [ITheme](../../com.aspose.slides/itheme) インターフェイスと共に使用され、継承が適用された効果的な書式設定値を返します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | 色スキームを返します。 |
| [getFontScheme()](#getFontScheme--) | フォントスキームを返します。 |
| [getFormatScheme()](#getFormatScheme--) | 図形書式スキームを返します。 |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```

色スキームを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**戻り値:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - カラー スキーム [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

フォントスキームを返します。 読み取り専用 [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)。

**戻り値:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

図形書式スキームを返します。 読み取り専用 [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)。

**戻り値:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)