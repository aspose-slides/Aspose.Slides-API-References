---
title: IParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: このクラスは段落書式設定プロパティを含みます。
type: docs
url: /ja/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

このクラスは段落書式設定プロパティを含みます。[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)とは異なり、このクラスのすべてのプロパティは書き込み可能です。

--------------------

このクラスは、特定の段落に対して定義された段落書式設定プロパティを取得および操作するために使用されます。これは、値を取得する際に継承が適用されないことを意味し、ほとんどの場合「未定義」の値が取得されます。

継承を含む有効な書式設定パラメータ値を取得するには、[getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) メソッドを使用する必要があります。このメソッドは [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) インスタンスを返します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBullet()](#getBullet--) | 段落の箇条書き形式を返します。 |
| [getDepth()](#getDepth--) | 段落の深さを取得または設定します。 |
| [setDepth(short value)](#setDepth-short-) | 段落の深さを取得または設定します。 |
| [getAlignment()](#getAlignment--) | 継承なしで段落のテキスト配置を取得または設定します。 |
| [setAlignment(int value)](#setAlignment-int-) | 継承なしで段落のテキスト配置を取得または設定します。 |
| [getSpaceWithin()](#getSpaceWithin--) | 段落の基準線間の間隔を取得または設定します。 |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | 段落の基準線間の間隔を取得または設定します。 |
| [getSpaceBefore()](#getSpaceBefore--) | 継承なしで段落の最初の行の前の間隔を取得または設定します。 |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | 継承なしで段落の最初の行の前の間隔を取得または設定します。 |
| [getSpaceAfter()](#getSpaceAfter--) | 継承なしで段落の最後の行の後の間隔を取得または設定します。 |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | 継承なしで段落の最後の行の後の間隔を取得または設定します。 |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | 段落で東アジアの改行が使用されているかどうかを判定します。 |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | 段落で東アジアの改行が使用されているかどうかを判定します。 |
| [getRightToLeft()](#getRightToLeft--) | 段落で右から左への書字が使用されているかどうかを判定します。 |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | 段落で右から左への書字が使用されているかどうかを判定します。 |
| [getLatinLineBreak()](#getLatinLineBreak--) | 段落でラテン文字の改行が使用されているかどうかを判定します。 |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | 段落でラテン文字の改行が使用されているかどうかを判定します。 |
| [getHangingPunctuation()](#getHangingPunctuation--) | 段落でハンギング句読点が使用されているかどうかを判定します。 |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | 段落でハンギング句読点が使用されているかどうかを判定します。 |
| [getMarginLeft()](#getMarginLeft--) | 継承なしで段落の左余白を取得または設定します。 |
| [setMarginLeft(float value)](#setMarginLeft-float-) | 継承なしで段落の左余白を取得または設定します。 |
| [getMarginRight()](#getMarginRight--) | 継承なしで段落の右余白を取得または設定します。 |
| [setMarginRight(float value)](#setMarginRight-float-) | 継承なしで段落の右余白を取得または設定します。 |
| [getIndent()](#getIndent--) | 継承なしで段落の先頭行インデント／ハンギングインデントを取得または設定します。 |
| [setIndent(float value)](#setIndent-float-) | 継承なしで段落の先頭行インデント／ハンギングインデントを取得または設定します。 |
| [getDefaultTabSize()](#getDefaultTabSize--) | 継承なしでデフォルトのタブ幅を取得または設定します。 |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | 継承なしでデフォルトのタブ幅を取得または設定します。 |
| [getTabs()](#getTabs--) | 段落のタブ設定を返します。 |
| [getFontAlignment()](#getFontAlignment--) | 継承なしで段落のフォント配置を取得または設定します。 |
| [setFontAlignment(int value)](#setFontAlignment-int-) | 継承なしで段落のフォント配置を取得または設定します。 |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | 段落のデフォルトの部分フォーマットを返します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な段落書式データを取得します。 |
### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

**段落の箇条書き形式を返します。** 読み取り専用 [IBulletFormat](../../com.aspose.slides/ibulletformat)。

**Returns:**  
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

**段落の深さを取得または設定します。** 値 0 は未定義を意味します。 読み書き short。

**Returns:**  
short
### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

**段落の深さを取得または設定します。** 値 0 は未定義を意味します。 読み書き short。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | short |  |
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

**継承なしで段落のテキスト配置を取得または設定します。** 読み書き [TextAlignment](../../com.aspose.slides/textalignment)。

**Returns:**  
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

**継承なしで段落のテキスト配置を取得または設定します。** 読み書き [TextAlignment](../../com.aspose.slides/textalignment)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

**段落の基準線間の間隔を取得または設定します。** 正の値はパーセンテージ、負の値はポイントサイズです。継承は適用されません。 読み書き float。

**Returns:**  
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

**段落の基準線間の間隔を取得または設定します。** 正の値はパーセンテージ、負の値はポイントサイズです。継承は適用されません。 読み書き float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

**継承なしで段落の最初の行の前の間隔を取得または設定します。** 正の値はフォントサイズのパーセンテージで、負の値はポイントサイズで指定します。 読み書き float。

**Returns:**  
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

**継承なしで段落の最初の行の前の間隔を取得または設定します。** 正の値はフォントサイズのパーセンテージで、負の値はポイントサイズで指定します。 読み書き float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

**継承なしで段落の最後の行の後の間隔を取得または設定します。** 正の値はフォントサイズのパーセンテージで、負の値はポイントサイズで指定します。 読み書き float。

**Returns:**  
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

**継承なしで段落の最後の行の後の間隔を取得または設定します。** 正の値はフォントサイズのパーセンテージで、負の値はポイントサイズで指定します。 読み書き float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

**段落で東アジアの改行が使用されているかどうかを判定します。** 継承は適用されません。 読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**Returns:**  
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

**段落で東アジアの改行が使用されているかどうかを判定します。** 継承は適用されません。 読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

**段落で右から左への書字が使用されているかどうかを判定します。** 継承は適用されません。 読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**Returns:**  
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

**段落で右から左への書字が使用されているかどうかを判定します。** 継承は適用されません。 読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

**段落でラテン文字の改行が使用されているかどうかを判定します。** 継承は適用されません。 読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**Returns:**  
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

**段落でラテン文字の改行が使用されているかどうかを判定します。** 継承は適用されません。 読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

**段落でハンギング句読点が使用されているかどうかを判定します。** 継承は適用されません。 読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**Returns:**  
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

**段落でハンギング句読点が使用されているかどうかを判定します。** 継承は適用されません。 読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

**継承なしで段落の左余白を取得または設定します。** 読み書き float。

**Returns:**  
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

**継承なしで段落の左余白を取得または設定します。** 読み書き float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

**継承なしで段落の右余白を取得または設定します。** 読み書き float。

**Returns:**  
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

**継承なしで段落の右余白を取得または設定します。** 読み書き float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

**継承なしで段落の先頭行インデント／ハンギングインデントを取得または設定します。** ハンギングインデントは負の値で定義できます。 読み書き float。

**Returns:**  
float
### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

**継承なしで段落の先頭行インデント／ハンギングインデントを取得または設定します。** ハンギングインデントは負の値で定義できます。 読み書き float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

**継承なしでデフォルトのタブ幅を取得または設定します。** 読み書き float。

**Returns:**  
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

**継承なしでデフォルトのタブ幅を取得または設定します。** 読み書き float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

**段落のタブ設定を返します。** 継承は適用されません。 読み取り専用 [ITabCollection](../../com.aspose.slides/itabcollection)。

**Returns:**  
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

**継承なしで段落のフォント配置を取得または設定します。** 読み書き [FontAlignment](../../com.aspose.slides/fontalignment)。

**Returns:**  
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

**継承なしで段落のフォント配置を取得または設定します。** 読み書き [FontAlignment](../../com.aspose.slides/fontalignment)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

**段落のデフォルトの部分フォーマットを返します。** 継承は適用されません。 読み取り専用 [IPortionFormat](../../com.aspose.slides/iportionformat)。

**Returns:**  
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

**継承が適用された有効な段落書式データを取得します。**

**Returns:**  
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).