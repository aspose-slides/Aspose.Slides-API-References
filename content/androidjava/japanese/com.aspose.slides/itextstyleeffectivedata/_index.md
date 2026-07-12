---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Android の Java API リファレンス
description: 効果的なテキストスタイルのプロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

効果的なテキストスタイルのプロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは [ITextStyle](../../com.aspose.slides/itextstyle) インターフェイスと併せて使用され、継承が適用された効果的な書式設定値を返します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | 効果的なスタイルのレベルを返します。 |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | 効果的なデフォルト段落プロパティを返します。 |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```


効果的なスタイルのレベルを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | レベルのゼロベースインデックス。0..8 の範囲である必要があります。 |

**戻り値:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - レベル [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) の効果的な書式設定。
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```


効果的なデフォルト段落プロパティを返します。読み取り専用 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)。

**戻り値:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)