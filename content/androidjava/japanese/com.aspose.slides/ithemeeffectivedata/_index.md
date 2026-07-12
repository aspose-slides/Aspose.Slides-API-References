---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 効果的なテーマプロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

効果的なテーマプロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは [ITheme](../../com.aspose.slides/itheme) インターフェイスと組み合わせて使用し、継承が適用された効果的な書式設定値を返します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | カラースキームを返します。 |
| [getFontScheme()](#getFontScheme--) | フォントスキームを返します。 |
| [getFormatScheme()](#getFormatScheme--) | シェイプ書式スキームを返します。 |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```


カラースキームを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| styleColor | java.lang.Integer | カラー java.lang.Integer |

**戻り値:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - カラースキーム [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
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


シェイプ書式スキームを返します。 読み取り専用 [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)。

**戻り値:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)