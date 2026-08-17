---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java APIリファレンス
description: 有効なテキストスタイルプロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

有効なテキストスタイルプロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは [ITextStyle](../../com.aspose.slides/itextstyle) インターフェイスと組み合わせて使用され、継承が適用された有効な書式設定値を返します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Returns level of effective style. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Returns effective default paragraph properties. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```


有効なスタイルのレベルを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | ゼロベースインデックスのレベル。0..8 の範囲内である必要があります。 |

**戻り値:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - レベル [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) の有効な書式設定
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```


有効なデフォルト段落プロパティを返します。読み取り専用 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)。

**戻り値:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)