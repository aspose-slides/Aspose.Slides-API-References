---
title: IBulletFormat
second_title: Aspose.Slides for Java API Reference
description: Represents paragraph bullet formatting properties.
type: docs
url: /zh-hant/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

表示段落項目符號格式屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getType()](#getType--) | 返回或設定段落的項目類型（不使用繼承）。 |
| [setType(byte value)](#setType-byte-) | 返回或設定段落的項目類型（不使用繼承）。 |
| [getChar()](#getChar--) | 返回或設定段落的項目字元（不使用繼承）。 |
| [setChar(char value)](#setChar-char-) | 返回或設定段落的項目字元（不使用繼承）。 |
| [getFont()](#getFont--) | 返回或設定段落的項目字型（不使用繼承）。 |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | 返回或設定段落的項目字型（不使用繼承）。 |
| [getHeight()](#getHeight--) | 返回或設定段落的項目高度（不使用繼承）。 |
| [setHeight(float value)](#setHeight-float-) | 返回或設定段落的項目高度（不使用繼承）。 |
| [getColor()](#getColor--) | 返回段落項目符號的顏色格式（不使用繼承）。 |
| [getPicture()](#getPicture--) | 返回段落中用作項目符號的圖片（不使用繼承）。 |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | 返回或設定用於編號項目群組的起始號碼（不使用繼承）。 |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | 返回或設定用於編號項目群組的起始號碼（不使用繼承）。 |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | 返回或設定編號項目的樣式（不使用繼承）。 |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | 返回或設定編號項目的樣式（不使用繼承）。 |
| [isBulletHardColor()](#isBulletHardColor--) | 判斷項目是否具有自訂顏色或從段落的第一段落繼承顏色。 |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | 判斷項目是否具有自訂顏色或從段落的第一段落繼承顏色。 |
| [isBulletHardFont()](#isBulletHardFont--) | 判斷項目是否具有自訂字型或從段落的第一段落繼承字型。 |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | 判斷項目是否具有自訂字型或從段落的第一段落繼承字型。 |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | 在啟用項目符號時，設定有效段落 Indent 與 MarginLeft 的預設非零偏移（如 PowerPoint 在啟用段落項目符號/編號時的行為）。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效項目格式資料。 |
### getType() {#getType--}
```
public abstract byte getType()
```

返回或設定段落的項目類型（不使用繼承）。可讀寫 [BulletType](../../com.aspose.slides/bullettype)。

**返回：**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

返回或設定段落的項目類型（不使用繼承）。可讀寫 [BulletType](../../com.aspose.slides/bullettype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```

返回或設定段落的項目字元（不使用繼承）。可讀寫 char。

**返回：**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

返回或設定段落的項目字元（不使用繼承）。可讀寫 char。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

返回或設定段落的項目字型（不使用繼承）。可讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

返回或設定段落的項目字型（不使用繼承）。可讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

返回或設定段落的項目高度（不使用繼承）。值 Float.NaN 表示項目從段落的第一段落繼承高度。可讀寫 float。

**返回：**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

返回或設定段落的項目高度（不使用繼承）。值 Float.NaN 表示項目從段落的第一段落繼承高度。可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

返回段落項目符號的顏色格式（不使用繼承）。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

返回段落中用作項目符號的圖片（不使用繼承）。唯讀 [ISlidesPicture](../../com.aspose.slides/islidespicture)。

**返回：**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

返回或設定用於編號項目群組的起始號碼（不使用繼承）。可讀寫 short。

**返回：**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

返回或設定用於編號項目群組的起始號碼（不使用繼承）。可讀寫 short。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

返回或設定編號項目的樣式（不使用繼承）。可讀寫 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte))。

**返回：**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

返回或設定編號項目的樣式（不使用繼承）。可讀寫 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte))。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

判斷項目是否具有自訂顏色或從段落的第一段落繼承顏色。若項目具有自訂顏色則 **NullableBool#True**，若從段落的第一段落繼承顏色則 **NullableBool#False**。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

判斷項目是否具有自訂顏色或從段落的第一段落繼承顏色。若項目具有自訂顏色則 **NullableBool#True**，若從段落的第一段落繼承顏色則 **NullableBool#False**。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

判斷項目是否具有自訂字型或從段落的第一段落繼承字型。若項目具有自訂字型則 **NullableBool#True**，若從段落的第一段落繼承字型則 **NullableBool#False**。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

判斷項目是否具有自訂字型或從段落的第一段落繼承字型。若項目具有自訂字型則 **NullableBool#True**，若從段落的第一段落繼承字型則 **NullableBool#False**。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

在啟用項目符號時，設定有效段落 Indent 與 MarginLeft 的預設非零偏移（如 PowerPoint 在啟用段落項目符號/編號時的行為）。若項目符號被停用，則僅重設段落 Indent 與 MarginLeft（如 PowerPoint 在停用段落項目符號/編號時的行為）。縮排偏移依據當前項目上下文 - IBulletFormat.Type、.NumberedBulletStyle 與第一段落的 FontHeight 來應用。非零縮排偏移會套用到當前段落的有效 Indent 與 MarginLeft（使結果值為本地值）。
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


**返回：**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - 一個 [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)。