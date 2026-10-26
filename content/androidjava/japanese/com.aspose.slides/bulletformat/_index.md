---
title: BulletFormat
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 段落の箇条書き書式プロパティを表します。
type: docs
url: /ja/com.aspose.slides/bulletformat/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)  
```
public final class BulletFormat extends PVIObject implements IBulletFormat
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
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | 継承なしで番号付き箇条書きグループに使用される最初の番号を取得または設定します。 |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | 継承なしで番号付き箇条書きグループに使用される最初の番号を取得または設定します。 |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | 継承なしで番号付き箇条書きのスタイルを取得または設定します。 |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | 継承なしで番号付き箇条書きのスタイルを取得または設定します。 |
| [isBulletHardColor()](#isBulletHardColor--) | 箇条書きが独自の色を持つか、段落の最初の部分から継承するかを判断します。 |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | 箇条書きが独自の色を持つか、段落の最初の部分から継承するかを判断します。 |
| [isBulletHardFont()](#isBulletHardFont--) | 箇条書きが独自のフォントを持つか、段落の最初の部分から継承するかを判断します。 |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | 箇条書きが独自のフォントを持つか、段落の最初の部分から継承するかを判断します。 |
| [getPicture()](#getPicture--) | 継承なしで段落の箇条書きとして使用される画像を取得します。 |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | 箇条書きが有効なとき（PowerPoint で段落の箇条書き/番号付けを有効にした場合と同様）、有効な段落インデントと左余白に対してデフォルトの非ゼロシフトを設定します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な箇条書き書式データを取得します。 |
| [getVersion()](#getVersion--) |  |

### getType() {#getType--}
```
public final byte getType()
```

継承なしで段落の箇条書きタイプを取得または設定します。 読み書き [BulletType](../../com.aspose.slides/bullettype)。

**戻り値:**
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

継承なしで段落の箇条書きタイプを取得または設定します。 読み書き [BulletType](../../com.aspose.slides/bullettype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```

継承なしで段落の箇条書き文字を取得または設定します。 読み書き char 。

**戻り値:**
char

### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

継承なしで段落の箇条書き文字を取得または設定します。 読み書き char 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```

継承なしで段落の箇条書きフォントを取得または設定します。 読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

継承なしで段落の箇条書きフォントを取得または設定します。 読み書き [IFontData](../../com.aspose.slides/ifontdata)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

継承なしで段落の箇条書き高さを取得または設定します。 値 Float.NaN は箇条書きが段落の最初の部分から高さを継承することを示します。 読み書き float 。

--------------------

負の高さ値は高さがポイントで指定されることを意味し、正の値は周囲のテキストのパーセンテージで高さが指定されることを意味します。

**戻り値:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

継承なしで段落の箇条書き高さを取得または設定します。 値 Float.NaN は箇条書きが段落の最初の部分から高さを継承することを示します。 読み書き float 。

--------------------

負の高さ値は高さがポイントで指定されることを意味し、正の値は周囲のテキストのパーセンテージで高さが指定されることを意味します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

継承なしで段落の箇条書きのカラー形式を取得します。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

継承なしで番号付き箇条書きグループに使用される最初の番号を取得または設定します。 読み書き short 。

**戻り値:**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

継承なしで番号付き箇条書きグループに使用される最初の番号を取得または設定します。 読み書き short 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

継承なしで番号付き箇条書きのスタイルを取得または設定します。 読み書き [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)。

**戻り値:**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

継承なしで番号付き箇条書きのスタイルを取得または設定します。 読み書き [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

箇条書きが独自の色を持つか、段落の最初の部分から継承するかを判断します。 **NullableBool.True** は箇条書きが独自の色を持つことを示し、**NullableBool.False** は段落の最初の部分から色を継承することを示します。 読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

箇条書きが独自の色を持つか、段落の最初の部分から継承するかを判断します。 **NullableBool.True** は箇条書きが独自の色を持つことを示し、**NullableBool.False** は段落の最初の部分から色を継承することを示します。 読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

箇条書きが独自のフォントを持つか、段落の最初の部分から継承するかを判断します。 **NullableBool.True** は箇条書きが独自のフォントを持つことを示し、**NullableBool.False** は段落の最初の部分からフォントを継承することを示します。 読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

箇条書きが独自のフォントを持つか、段落の最初の部分から継承するかを判断します。 **NullableBool.True** は箇条書きが独自のフォントを持つことを示し、**NullableBool.False** は段落の最初の部分からフォントを継承することを示します。 読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

継承なしで段落の箇条書きとして使用される画像を取得します。 読み取り専用 [ISlidesPicture](../../com.aspose.slides/islidespicture)。

**戻り値:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

箇条書きが有効なとき（PowerPoint で段落の箇条書き/番号付けを有効にした場合と同様）、有効な段落インデントと左余白に対してデフォルトの非ゼロシフトを設定します。箇条書きが無効な場合は段落インデントと左余白をリセットします（PowerPoint で段落の箇条書き/番号付けを無効にした場合と同様）。インデントシフトは現在の箇条書きコンテキスト（IBulletFormat.Type、.NumberedBulletStyle、最初の部分の FontHeight）に基づいて適用されます。非ゼロのインデントシフトは現在の段落の有効な Indent と MarginLeft に適用され、結果の値はローカル値となります。

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

継承が適用された有効な箇条書き書式データを取得します。

--------------------

> ```
> この例は、いくつかの有効な箇条書き書式プロパティの取得を示しています。
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
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - 1つの [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)。

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。 読み取り専用 long。

**戻り値:**
long