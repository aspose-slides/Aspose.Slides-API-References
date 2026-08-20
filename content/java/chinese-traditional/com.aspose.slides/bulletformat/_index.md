---
title: BulletFormat
second_title: Aspose.Slides for Java API 參考
description: 表示段落項目符號格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/bulletformat/
---
**繼承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已實作的介面:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

表示段落項目符號格式屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getType()](#getType--) | 取得或設定段落的項目符號類型（不繼承）。 |
| [setType(byte value)](#setType-byte-) | 取得或設定段落的項目符號類型（不繼承）。 |
| [getChar()](#getChar--) | 取得或設定段落的項目符號 char（不繼承）。 |
| [setChar(char value)](#setChar-char-) | 取得或設定段落的項目符號 char（不繼承）。 |
| [getFont()](#getFont--) | 取得或設定段落的項目符號字型（不繼承）。 |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | 取得或設定段落的項目符號字型（不繼承）。 |
| [getHeight()](#getHeight--) | 取得或設定段落的項目符號高度（不繼承）。 |
| [setHeight(float value)](#setHeight-float-) | 取得或設定段落的項目符號高度（不繼承）。 |
| [getColor()](#getColor--) | 取得段落的項目符號顏色格式（不繼承）。 |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | 取得或設定用於編號項目符號群組的第一個數字（不繼承）。 |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | 取得或設定用於編號項目符號群組的第一個數字（不繼承）。 |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | 取得或設定編號項目符號的樣式（不繼承）。 |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | 取得或設定編號項目符號的樣式（不繼承）。 |
| [isBulletHardColor()](#isBulletHardColor--) | 判斷項目符號是否擁有自己的顏色，或從段落的第一部分繼承顏色。 |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | 判斷項目符號是否擁有自己的顏色，或從段落的第一部分繼承顏色。 |
| [isBulletHardFont()](#isBulletHardFont--) | 判斷項目符號是否擁有自己的字型，或從段落的第一部分繼承字型。 |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | 判斷項目符號是否擁有自己的字型，或從段落的第一部分繼承字型。 |
| [getPicture()](#getPicture--) | 取得在段落中使用的項目符號圖片（不繼承）。 |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | 設定當啟用項目符號時，有效段落 Indent 和 MarginLeft 的預設非零位移（如 PowerPoint 在啟用段落項目符號/編號時的行為）。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效項目符號格式資料。 |
| [getVersion()](#getVersion--) |  |

### getType() {#getType--}
```
public final byte getType()
```


取得或設定段落的項目符號類型（不繼承）。可讀寫 [BulletType](../../com.aspose.slides/bullettype).

**返回值:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


取得或設定段落的項目符號類型（不繼承）。可讀寫 [BulletType](../../com.aspose.slides/bullettype).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```


取得或設定段落的項目符號 char（不繼承）。可讀寫  char .

**返回值:**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```


取得或設定段落的項目符號 char（不繼承）。可讀寫  char .

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```


取得或設定段落的項目符號字型（不繼承）。可讀寫 [IFontData](../../com.aspose.slides/ifontdata).

**返回值:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```


取得或設定段落的項目符號字型（不繼承）。可讀寫 [IFontData](../../com.aspose.slides/ifontdata).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


取得或設定段落的項目符號高度（不繼承）。值 Float.NaN 表示項目符號從段落的第一部分繼承高度。可讀寫  float .

--------------------

負的高度值表示以點數為單位給定高度，正的高度值表示以周圍文字的百分比為單位。

**返回值:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


取得或設定段落的項目符號高度（不繼承）。值 Float.NaN 表示項目符號從段落的第一部分繼承高度。可讀寫  float .

--------------------

負的高度值表示以點數為單位給定高度，正的高度值表示以周圍文字的百分比為單位。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


取得段落的項目符號顏色格式（不繼承）。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat).

**返回值:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```


取得或設定用於編號項目符號群組的第一個數字（不繼承）。可讀寫  short .

**返回值:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```


取得或設定用於編號項目符號群組的第一個數字（不繼承）。可讀寫  short .

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```


取得或設定編號項目符號的樣式（不繼承）。可讀寫 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**返回值:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```


取得或設定編號項目符號的樣式（不繼承）。可讀寫 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```


判斷項目符號是否擁有自己的顏色，或從段落的第一部分繼承顏色。**NullableBool.True** 表示項目符號有自己的顏色，**NullableBool.False** 表示項目符號從段落的第一部分繼承顏色。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool).

**返回值:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```


判斷項目符號是否擁有自己的顏色，或從段落的第一部分繼承顏色。**NullableBool.True** 表示項目符號有自己的顏色，**NullableBool.False** 表示項目符號從段落的第一部分繼承顏色。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```


判斷項目符號是否擁有自己的字型，或從段落的第一部分繼承字型。**NullableBool.True** 表示項目符號有自己的字型，**NullableBool.False** 表示項目符號從段落的第一部分繼承字型。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool).

**返回值:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```


判斷項目符號是否擁有自己的字型，或從段落的第一部分繼承字型。**NullableBool.True** 表示項目符號有自己的字型，**NullableBool.False** 表示項目符號從段落的第一部分繼承字型。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```


取得在段落中使用的項目符號圖片（不繼承）。唯讀 [ISlidesPicture](../../com.aspose.slides/islidespicture).

**返回值:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```


設定當啟用項目符號時，有效段落 Indent 和 MarginLeft 的預設非零位移（如 PowerPoint 在啟用段落項目符號/編號時的行為）。如果停用項目符號，則僅重設段落 Indent 和 MarginLeft（如 PowerPoint 在停用段落項目符號/編號時的行為）。縮排位移會根據當前項目符號上下文 — IBulletFormat.Type、.NumberedBulletStyle 和第一部分的 FontHeight — 進行套用。非零縮排位移會套用到當前段落的有效 Indent 和 MarginLeft（使結果值成為局部值）。

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```


取得套用繼承後的有效項目符號格式資料。

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
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - 一個 [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


版本。唯讀 long。

**返回值:**
long