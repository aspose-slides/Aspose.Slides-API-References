---
title: FormatScheme
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: シェイプのテーマ定義形式を格納します。
type: docs
url: /ja/com.aspose.slides/formatscheme/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFormatScheme](../../com.aspose.slides/iformatscheme), com.aspose.slides.IDOMObject
```
public class FormatScheme implements IFormatScheme, IDOMObject
```

シェイプのテーマ定義形式を格納します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFillStyles()](#getFillStyles--) | テーマで定義された塗りつぶしスタイルのコレクションを返します。 |
| [getLineStyles()](#getLineStyles--) | テーマで定義された線スタイルのコレクションを返します。 |
| [getEffectStyles()](#getEffectStyles--) | テーマで定義された効果スタイルのコレクションを返します。 |
| [getBackgroundFillStyles()](#getBackgroundFillStyles--) | テーマで定義された背景塗りつぶしスタイルのコレクションを返します。 |
| [getSlide()](#getSlide--) | 親スライドを返します。 |
| [getPresentation()](#getPresentation--) | 親プレゼンテーションを返します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getFillStyles() {#getFillStyles--}
```
public final IFillFormatCollection getFillStyles()
```

テーマで定義された塗りつぶしスタイルのコレクションを返します。 読み取り専用 [IFillFormatCollection](../../com.aspose.slides/ifillformatcollection).

**戻り値:**
[IFillFormatCollection](../../com.aspose.slides/ifillformatcollection)
### getLineStyles() {#getLineStyles--}
```
public final ILineFormatCollection getLineStyles()
```

テーマで定義された線スタイルのコレクションを返します。 読み取り専用 [ILineFormatCollection](../../com.aspose.slides/ilineformatcollection).

**戻り値:**
[ILineFormatCollection](../../com.aspose.slides/ilineformatcollection)
### getEffectStyles() {#getEffectStyles--}
```
public final IEffectStyleCollection getEffectStyles()
```

テーマで定義された効果スタイルのコレクションを返します。 読み取り専用 [IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection).

**戻り値:**
[IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)
### getBackgroundFillStyles() {#getBackgroundFillStyles--}
```
public final IFillFormatCollection getBackgroundFillStyles()
```

テーマで定義された背景塗りつぶしスタイルのコレクションを返します。 読み取り専用 [IFillFormatCollection](../../com.aspose.slides/ifillformatcollection).

**戻り値:**
[IFillFormatCollection](../../com.aspose.slides/ifillformatcollection)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

親スライドを返します。 読み取り専用 [IBaseSlide](../../com.aspose.slides/ibaseslide).

**戻り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

親プレゼンテーションを返します。 読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation).

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。 読み取り専用 IDOMObject.

**戻り値:**
com.aspose.slides.IDOMObject