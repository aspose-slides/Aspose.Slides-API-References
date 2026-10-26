---
title: IChartParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: チャートの段落書式プロパティを表します。
type: docs
url: /ja/com.aspose.slides/ichartparagraphformat/
---```
public interface IChartParagraphFormat
```

チャートの段落書式プロパティを表します。
## メソッド

| Method | Description |
| --- | --- |
| [getAlignment()](#getAlignment--) | 段落のテキスト配置を取得または設定します。 |
| [setAlignment(int value)](#setAlignment-int-) | 段落のテキスト配置を取得または設定します。 |
| [getSpaceWithin()](#getSpaceWithin--) | 段落のベースライン間のスペース量を取得または設定します。 |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | 段落のベースライン間のスペース量を取得または設定します。 |
| [getSpaceBefore()](#getSpaceBefore--) | 段落の最初の行の前のスペース量を取得または設定します。 |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | 段落の最初の行の前のスペース量を取得または設定します。 |
| [getSpaceAfter()](#getSpaceAfter--) | 段落の最後の行の後のスペース量を取得または設定します。 |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | 段落の最後の行の後のスペース量を取得または設定します。 |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | 段落で東アジアの改行が使用されているかどうかを判定します。 |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | 段落で東アジアの改行が使用されているかどうかを判定します。 |
| [getRightToLeft()](#getRightToLeft--) | 段落で右から左への書き方向が使用されているかどうかを判定します。 |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | 段落で右から左への書き方向が使用されているかどうかを判定します。 |
| [getLatinLineBreak()](#getLatinLineBreak--) | 段落でラテン文字の改行が使用されているかどうかを判定します。 |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | 段落でラテン文字の改行が使用されているかどうかを判定します。 |
| [getHangingPunctuation()](#getHangingPunctuation--) | 段落でハンギング句読点が使用されているかどうかを判定します。 |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | 段落でハンギング句読点が使用されているかどうかを判定します。 |
| [getMarginLeft()](#getMarginLeft--) | 段落の左余白を取得または設定します。 |
| [setMarginLeft(float value)](#setMarginLeft-float-) | 段落の左余白を取得または設定します。 |
| [getMarginRight()](#getMarginRight--) | 段落の右余白を取得または設定します。 |
| [setMarginRight(float value)](#setMarginRight-float-) | 段落の右余白を取得または設定します。 |
| [getIndent()](#getIndent--) | 段落の最初の行インデント/ハンギングインデントを取得または設定します。 |
| [setIndent(float value)](#setIndent-float-) | 段落の最初の行インデント/ハンギングインデントを取得または設定します。 |
| [getDefaultTabSize()](#getDefaultTabSize--) | デフォルトのタブ幅を取得または設定します。 |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | デフォルトのタブ幅を取得または設定します。 |
| [getTabs()](#getTabs--) | 段落のタブ設定を取得します。 |
| [getFontAlignment()](#getFontAlignment--) | 段落のフォント配置を取得または設定します。 |
| [setFontAlignment(int value)](#setFontAlignment-int-) | 段落のフォント配置を取得または設定します。 |
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

段落のテキスト配置を取得または設定します。読み書き [TextAlignment](../../com.aspose.slides/textalignment).

**戻り値:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

段落のテキスト配置を取得または設定します。読み書き [TextAlignment](../../com.aspose.slides/textalignment).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

段落のベースライン間のスペース量を取得または設定します。読み書き float.

**戻り値:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

段落のベースライン間のスペース量を取得または設定します。読み書き float.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

段落の最初の行の前のスペース量を取得または設定します。読み書き float.

**戻り値:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

段落の最初の行の前のスペース量を取得または設定します。読み書き float.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

段落の最後の行の後のスペース量を取得または設定します。読み書き float.

**戻り値:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

段落の最後の行の後のスペース量を取得または設定します。読み書き float.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

段落で東アジアの改行が使用されているかどうかを判定します。読み書き [NullableBool](../../com.aspose.slides/nullablebool).

**戻り値:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

段落で東アジアの改行が使用されているかどうかを判定します。読み書き [NullableBool](../../com.aspose.slides/nullablebool).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

段落で右から左への書き方向が使用されているかどうかを判定します。読み書き [NullableBool](../../com.aspose.slides/nullablebool).

**戻り値:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

段落で右から左への書き方向が使用されているかどうかを判定します。読み書き [NullableBool](../../com.aspose.slides/nullablebool).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

段落でラテン文字の改行が使用されているかどうかを判定します。読み書き [NullableBool](../../com.aspose.slides/nullablebool).

**戻り値:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

段落でラテン文字の改行が使用されているかどうかを判定します。読み書き [NullableBool](../../com.aspose.slides/nullablebool).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

段落でハンギング句読点が使用されているかどうかを判定します。読み書き [NullableBool](../../com.aspose.slides/nullablebool).

**戻り値:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

段落でハンギング句読点が使用されているかどうかを判定します。読み書き [NullableBool](../../com.aspose.slides/nullablebool).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

段落の左余白を取得または設定します。読み書き float.

**戻り値:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

段落の左余白を取得または設定します。読み書き float.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

段落の右余白を取得または設定します。読み書き float.

**戻り値:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

段落の右余白を取得または設定します。読み書き float.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

段落の最初の行インデント/ハンギングインデントを取得または設定します。ハンギングインデントは負の値で定義できます。読み書き float.

**戻り値:**
float
### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

段落の最初の行インデント/ハンギングインデントを取得または設定します。ハンギングインデントは負の値で定義できます。読み書き float.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

デフォルトのタブ幅を取得または設定します。読み書き float.

**戻り値:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

デフォルトのタブ幅を取得または設定します。読み書き float.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

段落のタブ設定を取得します。読み取り専用 [ITabCollection](../../com.aspose.slides/itabcollection).

**戻り値:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

段落のフォント配置を取得または設定します。読み書き [FontAlignment](../../com.aspose.slides/fontalignment).

**戻り値:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

段落のフォント配置を取得または設定します。読み書き [FontAlignment](../../com.aspose.slides/fontalignment).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |