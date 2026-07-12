---
title: IBulletFormat
second_title: Aspose.Slides for Android via Java API Reference
description: 段落の箇条書き書式プロパティを表します。
type: docs
url: /ja/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

段落の箇条書き書式プロパティを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getType()](#getType--) | 継承なしで段落の箇条書きタイプを取得または設定します。 |
| [setType(byte value)](#setType-byte-) | 継承なしで段落の箇条書きタイプを取得または設定します。 |
| [getChar()](#getChar--) | 継承なしで段落の箇条書き文字を取得または設定します。 |
| [setChar(char value)](#setChar-char-) | 継承なしで段落の箇条書き文字を取得または設定します。 |
| [getFont()](#getFont--) | 継承なしで段落の箇条書きフォントを取得または設定します。 |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | 継承なしで段落の箇条書きフォントを取得または設定します。 |
| [getHeight()](#getHeight--) | 継承なしで段落の箇条書き高さを取得または設定します。 |
| [setHeight(float value)](#setHeight-float-) | 継承なしで段落の箇条書き高さを取得または設定します。 |
| [getColor()](#getColor--) | 継承なしで段落の箇条書きのカラー形式を取得します。 |
| [getPicture()](#getPicture--) | 継承なしで段落の箇条書きとして使用される画像を取得します。 |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | 継承なしで番号付き箇条書きグループの先頭番号を取得または設定します。 |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | 継承なしで番号付き箇条書きグループの先頭番号を取得または設定します。 |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | 継承なしで番号付き箇条書きのスタイルを取得または設定します。 |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | 継承なしで番号付き箇条書きのスタイルを取得または設定します。 |
| [isBulletHardColor()](#isBulletHardColor--) | 箇条書きが独自の色を持つか、段落の最初の部分から継承するかを判断します。 |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | 箇条書きが独自の色を持つか、段落の最初の部分から継承するかを判断します。 |
| [isBulletHardFont()](#isBulletHardFont--) | 箇条書きが独自のフォントを持つか、段落の最初の部分から継承するかを判断します。 |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | 箇条書きが独自のフォントを持つか、段落の最初の部分から継承するかを判断します。 |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | 箇条書きが有効な場合に、効果的な段落インデントと左余白にデフォルトの非ゼロシフトを設定します（PowerPoint が段落箇条書き/番号付けを有効にしたときと同様）。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な箇条書き書式データを取得します。 |
### getType() {#getType--}
```
public abstract byte getType()
```


継承なしで段落の箇条書きタイプを取得または設定します。読み書き [BulletType](../../com.aspose.slides/bullettype)。

**戻り値:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


継承なしで段落の箇条書きタイプを取得または設定します。読み書き [BulletType](../../com.aspose.slides/bullettype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```


継承なしで段落の箇条書き文字を取得または設定します。読み書き char。

**戻り値:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```


継承なしで段落の箇条書き文字を取得または設定します。読み書き char。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


継承なしで段落の箇条書きフォントを取得または設定します。読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```


継承なしで段落の箇条書きフォントを取得または設定します。読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


継承なしで段落の箇条書き高さを取得または設定します。値 Float.NaN は、箇条書きが段落の最初の部分から高さを継承することを示します。読み書き float。

**戻り値:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```


継承なしで段落の箇条書き高さを取得または設定します。値 Float.NaN は、箇条書きが段落の最初の部分から高さを継承することを示します。読み書き float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


継承なしで段落の箇条書きのカラー形式を取得します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```


継承なしで段落の箇条書きとして使用される画像を取得します。読み取り専用 [ISlidesPicture](../../com.aspose.slides/islidespicture)。

**戻り値:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


継承なしで番号付き箇条書きグループの先頭番号を取得または設定します。読み書き short。

**戻り値:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```


継承なしで番号付き箇条書きグループの先頭番号を取得または設定します。読み書き short。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


継承なしで番号付き箇条書きのスタイルを取得または設定します。読み書き [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte))。

**戻り値:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```


継承なしで番号付き箇条書きのスタイルを取得または設定します。読み書き [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte))。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```


箇条書きが独自の色を持つか、段落の最初の部分から継承するかを判定します。箇条書きが独自の色を持つ場合は **NullableBool#True**、段落の最初の部分から色を継承する場合は **NullableBool#False** を返します。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```


箇条書きが独自の色を持つか、段落の最初の部分から継承するかを判定します。箇条書きが独自の色を持つ場合は **NullableBool#True**、段落の最初の部分から色を継承する場合は **NullableBool#False** を返します。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```


箇条書きが独自のフォントを持つか、段落の最初の部分から継承するかを判定します。箇条書きが独自のフォントを持つ場合は **NullableBool#True**、段落の最初の部分からフォントを継承する場合は **NullableBool#False** を返します。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```


箇条書きが独自のフォントを持つか、段落の最初の部分から継承するかを判定します。箇条書きが独自のフォントを持つ場合は **NullableBool#True**、段落の最初の部分からフォントを継承する場合は **NullableBool#False** を返します。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```


箇条書きが有効な場合に、効果的な段落インデントと左余白にデフォルトの非ゼロシフトを設定します（PowerPoint が段落箇条書き/番号付けを有効にしたときと同様）。箇条書きが無効な場合は段落インデントと左余白をリセットします（PowerPoint が段落箇条書き/番号付けを無効にしたときと同様）。インデントシフトは現在の箇条書きコンテキスト（IBulletFormat.Type、.NumberedBulletStyle、最初の部分の FontHeight）に基づいて適用され、非ゼロのインデントシフトは現在の段落の効果的なインデントと左余白に適用されます（結果の値はローカル値になります）。
### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```


継承が適用された有効な箇条書き書式データを取得します。

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


**戻り値:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)。