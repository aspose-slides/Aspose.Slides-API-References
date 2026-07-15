---
title: IBulletFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents paragraph bullet formatting properties.
type: docs
url: /zh-hant/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

表示段落項目格式屬性。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 取得或設定段落的項目類型，且不繼承。 |
| [setType(byte value)](#setType-byte-) | 取得或設定段落的項目類型，且不繼承。 |
| [getChar()](#getChar--) | 取得或設定段落的項目字元，且不繼承。 |
| [setChar(char value)](#setChar-char-) | 取得或設定段落的項目字元，且不繼承。 |
| [getFont()](#getFont--) | 取得或設定段落的項目字型，且不繼承。 |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | 取得或設定段落的項目字型，且不繼承。 |
| [getHeight()](#getHeight--) | 取得或設定段落的項目高度，且不繼承。 |
| [setHeight(float value)](#setHeight-float-) | 取得或設定段落的項目高度，且不繼承。 |
| [getColor()](#getColor--) | 取得段落項目的顏色格式，且不繼承。 |
| [getPicture()](#getPicture--) | 取得段落中用作項目的圖片，且不繼承。 |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | 取得或設定編號項目組使用的起始編號，且不繼承。 |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | 取得或設定編號項目組使用的起始編號，且不繼承。 |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | 取得或設定編號項目的樣式，且不繼承。 |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | 取得或設定編號項目的樣式，且不繼承。 |
| [isBulletHardColor()](#isBulletHardColor--) | 判斷項目是否擁有自訂顏色，或從段落的第一個部分繼承。 |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | 判斷項目是否擁有自訂顏色，或從段落的第一個部分繼承。 |
| [isBulletHardFont()](#isBulletHardFont--) | 判斷項目是否擁有自訂字型，或從段落的第一個部分繼承。 |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | 判斷項目是否擁有自訂字型，或從段落的第一個部分繼承。 |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | 在啟用項目時，為有效段落的縮排和左外距設定預設非零位移（如 PowerPoint 在啟用段落項目/編號時的行為）。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效項目格式資料。 |

### getType() {#getType--}
```
public abstract byte getType()
```

取得或設定段落的項目類型，且不繼承。讀寫 [BulletType](../../com.aspose.slides/bullettype)。

**返回:**  
byte

### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

取得或設定段落的項目類型，且不繼承。讀寫 [BulletType](../../com.aspose.slides/bullettype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```

取得或設定段落的項目字元，且不繼承。讀寫 char。

**返回:**  
char

### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

取得或設定段落的項目字元，且不繼承。讀寫 char。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

取得或設定段落的項目字型，且不繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**返回:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

取得或設定段落的項目字型，且不繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

取得或設定段落的項目高度，且不繼承。值 Float.NaN 表示項目從段落的第一個部分繼承高度。讀寫 float。

**返回:**  
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

取得或設定段落的項目高度，且不繼承。值 Float.NaN 表示項目從段落的第一個部分繼承高度。讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

取得段落項目的顏色格式，且不繼承。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

取得段落中用作項目的圖片，且不繼承。唯讀 [ISlidesPicture](../../com.aspose.slides/islidespicture)。

**返回:**  
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

取得或設定編號項目組使用的起始編號，且不繼承。讀寫 short。

**返回:**  
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

取得或設定編號項目組使用的起始編號，且不繼承。讀寫 short。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

取得或設定編號項目的樣式，且不繼承。讀寫 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte))。

**返回:**  
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

取得或設定編號項目的樣式，且不繼承。讀寫 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte))。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

判斷項目是否擁有自訂顏色，或從段落的第一個部分繼承。**NullableBool#True** 表示項目有自訂顏色，**NullableBool#False** 表示項目從段落的第一個部分繼承顏色。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**  
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

判斷項目是否擁有自訂顏色，或從段落的第一個部分繼承。**NullableBool#True** 表示項目有自訂顏色，**NullableBool#False** 表示項目從段落的第一個部分繼承顏色。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

判斷項目是否擁有自訂字型，或從段落的第一個部分繼承。**NullableBool#True** 表示項目有自訂字型，**NullableBool#False** 表示項目從段落的第一個部分繼承字型。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**  
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

判斷項目是否擁有自訂字型，或從段落的第一個部分繼承。**NullableBool#True** 表示項目有自訂字型，**NullableBool#False** 表示項目從段落的第一個部分繼承字型。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

在啟用項目時，為有效段落的縮排和左外距設定預設非零位移（如 PowerPoint 在啟用段落項目/編號時的行為）。如果項目被停用，則僅重設段落的縮排和左外距（如 PowerPoint 在停用段落項目/編號時的行為）。縮排位移會根據目前的項目上下文（IBulletFormat.Type、.NumberedBulletStyle 以及第一個部分的 FontHeight）套用。非零的縮排位移會套用至目前段落的有效 Indent 和 MarginLeft（使結果值為局部值）。

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

取得套用繼承後的有效項目格式資料。

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


**返回:**  
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).