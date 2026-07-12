---
title: MasterTheme
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: マスターテーマを表します。
type: docs
url: /ja/com.aspose.slides/mastertheme/
---
**継承:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

マスターテーマを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | カラースキームを返します。 |
| [getFontScheme()](#getFontScheme--) | フォントスキームを返します。 |
| [getFormatScheme()](#getFormatScheme--) | シェイプフォーマットスキームを返します。 |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | 追加のカラースキームのコレクションを返します。 |
| [getName()](#getName--) | テーマの名前を返します。 |
| [setName(String value)](#setName-java.lang.String-) | テーマの名前を返します。 |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```


カラースキームを返します。読み取り専用 [IColorScheme](../../com.aspose.slides/icolorscheme)。

**戻り値:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```


フォントスキームを返します。読み取り専用 [IFontScheme](../../com.aspose.slides/ifontscheme)。

**戻り値:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```


シェイプフォーマットスキームを返します。読み取り専用 [IFormatScheme](../../com.aspose.slides/iformatscheme)。

**戻り値:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```


追加のカラースキームのコレクションを返します。これらのスキームはプレゼンテーションの外観に影響せず、スライドのメインカラースキームとして選択できます。読み取り専用 [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)。

**戻り値:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```


テーマの名前を返します。読み書き可能 String.

**戻り値:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


テーマの名前を返します。読み書き可能 String.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```


バージョンです。読み取り専用 long.

**戻り値:**
long