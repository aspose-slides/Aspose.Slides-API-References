---
title: ITextStyle
second_title: Aspose.Slides for Java API Reference
description: Text style formatting properties.
type: docs
url: /ja/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

テキストスタイルの書式設定プロパティです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | スタイルのレベルが存在すればそれを返し、存在しなければnullを返します。 |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | デフォルトの段落プロパティです。 |
| [getEffective()](#getEffective--) | 継承が適用された有効なテキストスタイルの書式設定データを取得します。 |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

スタイルのレベルが存在すればそれを返し、存在しなければnullを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | レベルのゼロベースインデックス。0..8 の範囲内である必要があります。 |

**戻り値:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - レベル [IParagraphFormat](../../com.aspose.slides/iparagraphformat) の書式設定。

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

デフォルトの段落プロパティ。読み取り専用 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**戻り値:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

継承が適用された有効なテキストスタイルの書式設定データを取得します。

**戻り値:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) のインスタンス。