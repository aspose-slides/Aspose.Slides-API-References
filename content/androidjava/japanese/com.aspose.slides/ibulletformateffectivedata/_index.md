---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 効果的な段落の箇条書き書式設定プロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

このインターフェイスは [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) の一部として使用されます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getType()](#getType--) | 段落の箇条書きタイプを返します。 |
| [getChar()](#getChar--) | 段落の箇条書き文字を返します。 |
| [getActualBulletValue()](#getActualBulletValue--) | 親段落の実際の箇条書き値を返します。 |
| [getFont()](#getFont--) | 段落の箇条書きフォントを返します。 |
| [getHeight()](#getHeight--) | 段落の箇条書きの高さを返します。 |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | 番号付き箇条書きのグループで使用される最初の番号を返します。 |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | 番号付き箇条書きのスタイルを返します。 |
| [isBulletHardColor()](#isBulletHardColor--) | 箇条書きが独自の色を持つか、段落の最初の部分から継承するかを判定します。 |
| [isBulletHardFont()](#isBulletHardFont--) | 箇条書きが独自のフォントを持つか、段落の最初の部分から継承するかを判定します。 |
| [getPicture()](#getPicture--) | 段落で箇条書きとして使用される画像を返します。 |
| [getFillFormat()](#getFillFormat--) | 段落の箇条書き塗りつぶし形式を返します。 |
### getType() {#getType--}
```
public abstract byte getType()
```

段落の箇条書きタイプを返します。読み取り専用 [BulletType](../../com.aspose.slides/bullettype)。

**Returns:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```

段落の箇条書き文字を返します。読み取り専用 char。

**Returns:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```

親段落の実際の箇条書き値を返します。読み取り専用 String。

**Returns:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

段落の箇条書きフォントを返します。読み取り専用 [IFontData](../../com.aspose.slides/ifontdata)。

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

段落の箇条書きの高さを返します。読み取り専用 float。

**Returns:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

番号付き箇条書きのグループで使用される最初の番号を返します。読み取り専用 short。

**Returns:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

番号付き箇条書きのスタイルを返します。読み取り専用 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)。

**Returns:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```

箇条書きが独自の色を持つか、段落の最初の部分から継承するかを判定します。箇条書きが独自の色を持つ場合は **true**、段落の最初の部分から色を継承する場合は **false** を返します。読み取り専用 boolean。

**Returns:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```

箇条書きが独自のフォントを持つか、段落の最初の部分から継承するかを判定します。箇条書きが独自のフォントを持つ場合は **true**、段落の最初の部分からフォントを継承する場合も **true** を返します。読み取り専用 boolean。

**Returns:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

段落で箇条書きとして使用される画像を返します。読み取り専用 [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)。

**Returns:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

段落の箇条書き塗りつぶし形式を返します。読み取り専用 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // 最初のスライドの最初のシェイプがテキストを持つAutoShapeであると仮定します...
>      // テキスト段落の箇条書き情報を出力します
>      AutoShape autoShape = (AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for (IParagraph para : autoShape.getTextFrame().getParagraphs())
>      {
>          IBulletFormatEffectiveData bulletFormatEffective = para.getParagraphFormat().getBullet().getEffective();
>          System.out.println("Bullet type: " + bulletFormatEffective.getType());
>          if (bulletFormatEffective.getType() != BulletType.None)
>          {
>              System.out.println("Bullet fill type: " + bulletFormatEffective.getFillFormat().getFillType());
>              switch (bulletFormatEffective.getFillFormat().getFillType())
>              {
>                  case FillType.Solid:
>                      System.out.println("Solid fill color: " + bulletFormatEffective.getFillFormat().getSolidFillColor());
>                      break;
>                  case FillType.Gradient:
>                      System.out.println("Gradient stops count: " + bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops().size());
>                      for (IGradientStopEffectiveData gradStop : bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops())
>                          System.out.println(gradStop.getPosition() + ": " + gradStop.getColor());
>                      break;
>                  case FillType.Pattern:
>                      System.out.println("Pattern style: " + bulletFormatEffective.getFillFormat().getPatternFormat().getPatternStyle());
>                      System.out.println("Fore color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getForeColor());
>                      System.out.println("Back color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getBackColor());
>                      break;
>              }
>          }
>          System.out.println();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)