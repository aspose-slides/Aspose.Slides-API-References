---
title: IParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: 此類別包含段落格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

此類別包含段落格式屬性。與 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 不同，此類別的所有屬性皆可寫入。

--------------------

此類別用於返回和操作針對特定段落定義的段落格式屬性。這表示在取得值時不會套用繼承，因此在大多數情況下您會取得「未定義」的值。

若要取得包括繼承在內的有效格式參數值，您需要使用 [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) 方法，該方法會返回一個 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 實例。
## 方法

| Method | Description |
| --- | --- |
| [getBullet()](#getBullet--) | 返回段落的項目符號格式。 |
| [getDepth()](#getDepth--) | 返回或設定段落的深度。 |
| [setDepth(short value)](#setDepth-short-) | 返回或設定段落的深度。 |
| [getAlignment()](#getAlignment--) | 返回或設定段落的文字對齊（無繼承）。 |
| [setAlignment(int value)](#setAlignment-int-) | 返回或設定段落的文字對齊（無繼承）。 |
| [getSpaceWithin()](#getSpaceWithin--) | 返回或設定段落基線之間的間距。 |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | 返回或設定段落基線之間的間距。 |
| [getSpaceBefore()](#getSpaceBefore--) | 返回或設定段落首行前的間距（無繼承）。 |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | 返回或設定段落首行前的間距（無繼承）。 |
| [getSpaceAfter()](#getSpaceAfter--) | 返回或設定段落末行後的間距（無繼承）。 |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | 返回或設定段落末行後的間距（無繼承）。 |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | 判斷段落是否使用東亞換行。 |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | 判斷段落是否使用東亞換行。 |
| [getRightToLeft()](#getRightToLeft--) | 判斷段落是否使用從右至左書寫。 |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | 判斷段落是否使用從右至左書寫。 |
| [getLatinLineBreak()](#getLatinLineBreak--) | 判斷段落是否使用拉丁換行。 |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | 判斷段落是否使用拉丁換行。 |
| [getHangingPunctuation()](#getHangingPunctuation--) | 判斷段落是否使用懸掛標點。 |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | 判斷段落是否使用懸掛標點。 |
| [getMarginLeft()](#getMarginLeft--) | 返回或設定段落左邊距（無繼承）。 |
| [setMarginLeft(float value)](#setMarginLeft-float-) | 返回或設定段落左邊距（無繼承）。 |
| [getMarginRight()](#getMarginRight--) | 返回或設定段落右邊距（無繼承）。 |
| [setMarginRight(float value)](#setMarginRight-float-) | 返回或設定段落右邊距（無繼承）。 |
| [getIndent()](#getIndent--) | 返回或設定段落首行縮排/懸掛縮排（無繼承）。 |
| [setIndent(float value)](#setIndent-float-) | 返回或設定段落首行縮排/懸掛縮排（無繼承）。 |
| [getDefaultTabSize()](#getDefaultTabSize--) | 返回或設定預設製表位大小（無繼承）。 |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | 返回或設定預設製表位大小（無繼承）。 |
| [getTabs()](#getTabs--) | 返回段落的製表位。 |
| [getFontAlignment()](#getFontAlignment--) | 返回或設定段落的字型對齊（無繼承）。 |
| [setFontAlignment(int value)](#setFontAlignment-int-) | 返回或設定段落的字型對齊（無繼承）。 |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | 返回段落的預設文字段格式。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效段落格式資料。 |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

返回段落的項目符號格式。唯讀 [IBulletFormat](../../com.aspose.slides/ibulletformat)。

**返回:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

返回或設定段落的深度。值 0 表示未定義的值。可讀寫 short。

**返回:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

返回或設定段落的深度。值 0 表示未定義的值。可讀寫 short。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

返回或設定段落的文字對齊（無繼承）。可讀寫 [TextAlignment](../../com.aspose.slides/textalignment)。

**返回:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

返回或設定段落的文字對齊（無繼承）。可讀寫 [TextAlignment](../../com.aspose.slides/textalignment)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

返回或設定段落基線之間的間距。正值表示百分比，負值表示點數大小。未套用繼承。可讀寫 float。

**返回:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

返回或設定段落基線之間的間距。正值表示百分比，負值表示點數大小。未套用繼承。可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

返回或設定段落首行前的間距（無繼承）。正值表示字型大小的百分比，負值表示點數大小。可讀寫 float。

**返回:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

返回或設定段落首行前的間距（無繼承）。正值表示字型大小的百分比，負值表示點數大小。可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

返回或設定段落末行後的間距（無繼承）。正值表示字型大小的百分比，負值表示點數大小。可讀寫 float。

**返回:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

返回或設定段落末行後的間距（無繼承）。正值表示字型大小的百分比，負值表示點數大小。可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

判斷段落是否使用東亞換行。未套用繼承。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

判斷段落是否使用東亞換行。未套用繼承。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

判斷段落是否使用從右至左書寫。未套用繼承。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

判斷段落是否使用從右至左書寫。未套用繼承。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

判斷段落是否使用拉丁換行。未套用繼承。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

判斷段落是否使用拉丁換行。未套用繼承。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

判斷段落是否使用懸掛標點。未套用繼承。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

判斷段落是否使用懸掛標點。未套用繼承。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

返回或設定段落左邊距（無繼承）。可讀寫 float。

**返回:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

返回或設定段落左邊距（無繼承）。可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

返回或設定段落右邊距（無繼承）。可讀寫 float。

**返回:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

返回或設定段落右邊距（無繼承）。可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

返回或設定段落首行縮排/懸掛縮排（無繼承）。懸掛縮排可使用負值。可讀寫 float。

**返回:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

返回或設定段落首行縮排/懸掛縮排（無繼承）。懸掛縮排可使用負值。可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

返回或設定預設製表位大小（無繼承）。可讀寫 float。

**返回:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

返回或設定預設製表位大小（無繼承）。可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

返回段落的製表位。未套用繼承。唯讀 [ITabCollection](../../com.aspose.slides/itabcollection)。

**返回:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

返回或設定段落的字型對齊（無繼承）。可讀寫 [FontAlignment](../../com.aspose.slides/fontalignment)。

**返回:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

返回或設定段落的字型對齊（無繼承）。可讀寫 [FontAlignment](../../com.aspose.slides/fontalignment)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

返回段落的預設文字段格式。未套用繼承。唯讀 [IPortionFormat](../../com.aspose.slides/iportionformat)。

**返回:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

取得套用繼承後的有效段落格式資料。

**返回:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).