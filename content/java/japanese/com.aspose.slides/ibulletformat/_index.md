---
title: IBulletFormat
second_title: Aspose.Slides for Java API Reference
description: Represents paragraph bullet formatting properties.
type: docs
url: /ja/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

段落の箇条書き書式設定プロパティを表します。

## メソッド

| Method | Description |
| --- | --- |
| [getType()](#getType--) | 継承されない段落の箇条書きタイプを取得または設定します。 |
| [setType(byte value)](#setType-byte-) | 継承されない段落の箇条書きタイプを取得または設定します。 |
| [getChar()](#getChar--) | 継承されない段落の箇条書き文字を取得または設定します。 |
| [setChar(char value)](#setChar-char-) | 継承されない段落の箇条書き文字を取得または設定します。 |
| [getFont()](#getFont--) | 継承されない段落の箇条書きフォントを取得または設定します。 |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | 継承されない段落の箇条書きフォントを取得または設定します。 |
| [getHeight()](#getHeight--) | 継承されない段落の箇条書き高さを取得または設定します。 |
| [setHeight(float value)](#setHeight-float-) | 継承されない段落の箇条書き高さを取得または設定します。 |
| [getColor()](#getColor--) | 継承されない段落の箇条書きのカラー形式を取得します。 |
| [getPicture()](#getPicture--) | 継承されない段落で箇条書きとして使用される画像を取得します。 |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | 継承されない段落の番号付き箇条書きグループに使用される最初の番号を取得または設定します。 |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | 継承されない段落の番号付き箇条書きグループに使用される最初の番号を取得または設定します。 |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | 継承されない番号付き箇条書きのスタイルを取得または設定します。 |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | 継承されない番号付き箇条書きのスタイルを取得または設定します。 |
| [isBulletHardColor()](#isBulletHardColor--) | 段落の最初の部分から色を継承するか、箇条書きが独自の色を持つかを判定します。 |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | 段落の最初の部分から色を継承するか、箇条書きが独自の色を持つかを判定します。 |
| [isBulletHardFont()](#isBulletHardFont--) | 段落の最初の部分からフォントを継承するか、箇条書きが独自のフォントを持つかを判定します。 |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | 段落の最初の部分からフォントを継承するか、箇条書きが独自のフォントを持つかを判定します。 |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | 箇条書きが有効な場合（PowerPoint が段落の箇条書き/番号付けを有効にしたときと同様）に、実効段落インデントと左余白に対するデフォルトの非ゼロシフトを設定します。 |
| [getEffective()](#getEffective--) | 適用された継承を含む実効箇条書き書式設定データを取得します。 |

### getType() {#getType--}
```
public abstract byte getType()
```

継承されない段落の箇条書きタイプを取得または設定します。 読み取り/書き込み [BulletType](../../com.aspose.slides/bullettype)。

**戻り値:**
byte

### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

継承されない段落の箇条書きタイプを取得または設定します。 読み取り/書き込み [BulletType](../../com.aspose.slides/bullettype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```

継承されない段落の箇条書き文字を取得または設定します。 読み取り/書き込み char。

**戻り値:**
char

### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

継承されない段落の箇条書き文字を取得または設定します。 読み取り/書き込み char。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

継承されない段落の箇条書きフォントを取得または設定します。 読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

継承されない段落の箇条書きフォントを取得または設定します。 読み取り/書き込み [IFontData](../../com.aspose.slides/ifontdata)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

継承されない段落の箇条書き高さを取得または設定します。 値 Float.NaN は箇条書きが段落の最初の部分から高さを継承することを示します。 読み取り/書き込み float。

**戻り値:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

継承されない段落の箇条書き高さを取得または設定します。 値 Float.NaN は箇条書きが段落の最初の部分から高さを継承することを示します。 読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

継承されない段落の箇条書きのカラー形式を取得します。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

継承されない段落で箇条書きとして使用される画像を取得します。 読み取り専用 [ISlidesPicture](../../com.aspose.slides/islidespicture)。

**戻り値:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

継承されない段落の番号付き箇条書きグループに使用される最初の番号を取得または設定します。 読み取り/書き込み short。

**戻り値:**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

継承されない段落の番号付き箇条書きグループに使用される最初の番号を取得または設定します。 読み取り/書き込み short。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

継承されない番号付き箇条書きのスタイルを取得または設定します。 読み取り/書き込み [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte))。

**戻り値:**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

継承されない番号付き箇条書きのスタイルを取得または設定します。 読み取り/書き込み [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte))。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

段落の最初の部分から色を継承するか、箇条書きが独自の色を持つかを判定します。 **NullableBool#True** は箇条書きが独自の色を持つことを、**NullableBool#False** は段落の最初の部分から色を継承することを表します。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

段落の最初の部分から色を継承するか、箇条書きが独自の色を持つかを判定します。 **NullableBool#True** は箇条書きが独自の色を持つことを、**NullableBool#False** は段落の最初の部分から色を継承することを表します。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

段落の最初の部分からフォントを継承するか、箇条書きが独自のフォントを持つかを判定します。 **NullableBool#True** は箇条書きが独自のフォントを持つことを、**NullableBool#False** は段落の最初の部分からフォントを継承することを表します。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

段落の最初の部分からフォントを継承するか、箇条書きが独自のフォントを持つかを判定します。 **NullableBool#True** は箇条書きが独自のフォントを持つことを、**NullableBool#False** は段落の最初の部分からフォントを継承することを表します。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

箇条書きが有効な場合（PowerPoint が段落の箇条書き/番号付けを有効にしたときと同様）に、実効段落インデントと左余白に対するデフォルトの非ゼロシフトを設定します。箇条書きが無効な場合は、段落インデントと左余白をリセットします（PowerPoint が段落の箇条書き/番号付けを無効にしたときと同様）。シフトは現在の箇条書きコンテキスト（IBulletFormat.Type、.NumberedBulletStyle、および最初の部分の FontHeight）に基づいて適用されます。非ゼロシフトは現在の段落の実効インデントと左余白に適用され、結果の値はローカル値となります。

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

適用された継承を含む実効箇条書き書式設定データを取得します。

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
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).