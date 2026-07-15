---
title: BulletFormat
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 代表段落項目符號格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/bulletformat/
---
**繼承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**已實作的介面:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

代表段落項目符號格式屬性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 返回或設定段落的項目類型，且不從上層繼承。 |
| [setType(byte value)](#setType-byte-) | 返回或設定段落的項目類型，且不從上層繼承。 |
| [getChar()](#getChar--) | 返回或設定段落的項目字元，且不從上層繼承。 |
| [setChar(char value)](#setChar-char-) | 返回或設定段落的項目字元，且不從上層繼承。 |
| [getFont()](#getFont--) | 返回或設定段落的項目字型，且不從上層繼承。 |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | 返回或設定段落的項目字型，且不從上層繼承。 |
| [getHeight()](#getHeight--) | 返回或設定段落的項目高度，且不從上層繼承。 |
| [setHeight(float value)](#setHeight-float-) | 返回或設定段落的項目高度，且不從上層繼承。 |
| [getColor()](#getColor--) | 返回段落項目的顏色格式，且不從上層繼承。 |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | 返回或設定編號項目群組的起始編號，且不從上層繼承。 |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | 返回或設定編號項目群組的起始編號，且不從上層繼承。 |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | 返回或設定編號項目的樣式，且不從上層繼承。 |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | 返回或設定編號項目的樣式，且不從上層繼承。 |
| [isBulletHardColor()](#isBulletHardColor--) | 判斷項目是否具有自行顏色，或繼承自段落的第一個部分。 |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | 判斷項目是否具有自行顏色，或繼承自段落的第一個部分。 |
| [isBulletHardFont()](#isBulletHardFont--) | 判斷項目是否具有自行字型，或繼承自段落的第一個部分。 |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | 判斷項目是否具有自行字型，或繼承自段落的第一個部分。 |
| [getPicture()](#getPicture--) | 返回段落中作為項目的圖片，且不從上層繼承。 |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | 設定當啟用項目時，實際段落縮排與左邊距的預設非零位移（類似 PowerPoint 在啟用段落項目/編號時的行為）。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的實際項目格式資料。 |
| [getVersion()](#getVersion--) |  |

### getType() {#getType--}
```
public final byte getType()
```

返回或設定段落的項目類型，且不從上層繼承。可讀寫 [BulletType](../../com.aspose.slides/bullettype)。

**返回值:**
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

返回或設定段落的項目類型，且不從上層繼承。可讀寫 [BulletType](../../com.aspose.slides/bullettype)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```

返回或設定段落的項目字元，且不從上層繼承。可讀寫 char 。

**返回值:**
char

### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

返回或設定段落的項目字元，且不從上層繼承。可讀寫 char 。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```

返回或設定段落的項目字型，且不從上層繼承。可讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**返回值:**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

返回或設定段落的項目字型，且不從上層繼承。可讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

返回或設定段落的項目高度，且不從上層繼承。值 Float.NaN 表示項目繼承段落第一個部分的高度。可讀寫 float 。

--------------------

負值表示高度以點 (pt) 為單位，正值表示高度為周圍文字的百分比。

**返回值:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

返回或設定段落的項目高度，且不從上層繼承。值 Float.NaN 表示項目繼承段落第一個部分的高度。可讀寫 float 。

--------------------

負值表示高度以點 (pt) 為單位，正值表示高度為周圍文字的百分比。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

返回段落項目的顏色格式，且不從上層繼承。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

返回或設定編號項目群組的起始編號，且不從上層繼承。可讀寫 short 。

**返回值:**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

返回或設定編號項目群組的起始編號，且不從上層繼承。可讀寫 short 。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

返回或設定編號項目的樣式，且不從上層繼承。可讀寫 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)。

**返回值:**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

返回或設定編號項目的樣式，且不從上層繼承。可讀寫 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

判斷項目是否具有自行顏色，或繼承自段落的第一個部分。若項目具有自行顏色則為 **NullableBool.True**，若繼承則為 **NullableBool.False**。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回值:**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

判斷項目是否具有自行顏色，或繼承自段落的第一個部分。若項目具有自行顏色則為 **NullableBool.True**，若繼承則為 **NullableBool.False**。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

判斷項目是否具有自行字型，或繼承自段落的第一個部分。若項目具有自行字型則為 **NullableBool.True**，若繼承則為 **NullableBool.False**。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回值:**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

判斷項目是否具有自行字型，或繼承自段落的第一個部分。若項目具有自行字型則為 **NullableBool.True**，若繼承則為 **NullableBool.False**。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

返回段落中作為項目的圖片，且不從上層繼承。唯讀 [ISlidesPicture](../../com.aspose.slides/islidespicture)。

**返回值:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

設定當啟用項目時，實際段落縮排與左邊距的預設非零位移（類似 PowerPoint 在啟用段落項目/編號時的行為）。若停用項目則僅重設段落縮排與左邊距（類似 PowerPoint 在停用段落項目/編號時的行為）。位移會根據目前的項目環境（IBulletFormat.Type、.NumberedBulletStyle 與第一個部分的 FontHeight）套用。非零的位移會應用於目前段落的實際縮排與左邊距（使結果值成為區域值）。

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

取得套用繼承後的實際項目格式資料。

--------------------

> ```
> This example demonstrates getting some effective bullet format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - 一個 [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)。

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**返回值:**
long