---
title: MasterTheme
second_title: Aspose.Slides for Java API リファレンス
description: マスターテーマを表します。
type: docs
url: /ja/com.aspose.slides/mastertheme/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**All Implemented Interfaces:**  
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)  
```
public final class MasterTheme extends Theme implements IMasterTheme
```

マスターテーマを表します。
## Methods

| Method | Description |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | カラースキームを返します。 |
| [getFontScheme()](#getFontScheme--) | フォントスキームを返します。 |
| [getFormatScheme()](#getFormatScheme--) | シェイプ形式スキームを返します。 |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | 追加のカラースキームのコレクションを返します。 |
| [getName()](#getName--) | テーマの名前を返します。 |
| [setName(String value)](#setName-java.lang.String-) | テーマの名前を返します。 |
| [getVersion()](#getVersion--) |  |

### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

カラースキームを返します。 読み取り専用 [IColorScheme](../../com.aspose.slides/icolorscheme)。

**Returns:**  
[IColorScheme](../../com.aspose.slides/icolorscheme)

### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

フォントスキームを返します。 読み取り専用 [IFontScheme](../../com.aspose.slides/ifontscheme)。

**Returns:**  
[IFontScheme](../../com.aspose.slides/ifontscheme)

### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

シェイプ形式スキームを返します。 読み取り専用 [IFormatScheme](../../com.aspose.slides/iformatscheme)。

**Returns:**  
[IFormatScheme](../../com.aspose.slides/iformatscheme)

### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

追加のカラースキームのコレクションを返します。 これらのスキームはプレゼンテーションの外観に影響せず、スライドのメインカラースキームとして選択できます。 読み取り専用 [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)。

**Returns:**  
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)

### getName() {#getName--}
```
public final String getName()
```

テーマの名前を返します。 読み書き String。

**Returns:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

テーマの名前を返します。 読み書き String。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。 読み取り専用 long。

**Returns:**  
long