---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: 効果的な段落書式設定プロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

効果的な段落書式設定プロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは [IParagraphFormat](../../com.aspose.slides/iparagraphformat) インターフェイスと共に使用され、継承が適用された効果的な書式設定値を返します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBullet()](#getBullet--) | 段落の箇条書き形式を返します。 |
| [getDepth()](#getDepth--) | 段落の深さを返します。 |
| [getAlignment()](#getAlignment--) | 段落のテキスト配置を返します。 |
| [getSpaceWithin()](#getSpaceWithin--) | 段落の基準線間のスペース量を返します。 |
| [getSpaceBefore()](#getSpaceBefore--) | 段落の最初の行の前のスペース量を返します。 |
| [getSpaceAfter()](#getSpaceAfter--) | 段落の最後の行の後のスペース量を返します。 |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | 段落で東アジアの改行が使用されているかどうかを判定します。 |
| [getRightToLeft()](#getRightToLeft--) | 段落で右から左への書き込みが使用されているかどうかを判定します。 |
| [getLatinLineBreak()](#getLatinLineBreak--) | 段落でラテン文字の改行が使用されているかどうかを判定します。 |
| [getHangingPunctuation()](#getHangingPunctuation--) | 段落でハンギング句読点が使用されているかどうかを判定します。 |
| [getMarginLeft()](#getMarginLeft--) | 段落の左余白を返します。 |
| [getMarginRight()](#getMarginRight--) | 段落の右余白を返します。 |
| [getIndent()](#getIndent--) | 段落の先頭行インデント/ハンギングインデントを返します。 |
| [getDefaultTabSize()](#getDefaultTabSize--) | デフォルトのタブ幅を返します。 |
| [getTabs()](#getTabs--) | 段落のタブ設定を返します。 |
| [getFontAlignment()](#getFontAlignment--) | 段落のフォント配置を返します。 |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | 段落のデフォルトの部分書式を返します。 |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

段落の箇条書き形式を返します。読み取り専用 [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)。

**返り値:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

段落の深さを返します。読み取り専用 short。

**返り値:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

段落のテキスト配置を返します。読み取り専用 [TextAlignment](../../com.aspose.slides/textalignment)。

**返り値:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

段落の基準線間のスペース量を返します。読み取り専用 float。

**返り値:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

段落の最初の行の前のスペース量を返します。読み取り専用 float。

**返り値:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

段落の最後の行の後のスペース量を返します。読み取り専用 float。

**返り値:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

段落で東アジアの改行が使用されているかどうかを判定します。読み取り専用 boolean。

**返り値:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

段落で右から左への書き込みが使用されているかどうかを判定します。読み取り専用 boolean。

**返り値:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

段落でラテン文字の改行が使用されているかどうかを判定します。読み取り専用 boolean。

**返り値:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

段落でハンギング句読点が使用されているかどうかを判定します。読み取り専用 boolean。

**返り値:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

段落の左余白を返します。読み取り専用 float。

**返り値:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

段落の右余白を返します。読み取り専用 float。

**返り値:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

段落の先頭行インデント/ハンギングインデントを返します。ハンギングインデントは負の値で定義できます。読み取り専用 float。

**返り値:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

デフォルトのタブ幅を返します。読み取り専用 float。

**返り値:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

段落のタブ設定を返します。読み取り専用 ITabEffectiveData[]。

**返り値:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

段落のフォント配置を返します。読み取り専用 [FontAlignment](../../com.aspose.slides/fontalignment)。

**返り値:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

段落のデフォルトの部分書式を返します。読み取り専用 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)。

**返り値:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)