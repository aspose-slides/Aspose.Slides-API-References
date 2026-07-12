---
title: TextStyle
second_title: Java API リファレンス経由の Android 用 Aspose.Slides
description: このクラスはテキストスタイルの書式設定プロパティを含みます。
type: docs
url: /ja/com.aspose.slides/textstyle/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

このクラスはテキストスタイルの書式設定プロパティを含みます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | スタイルのレベルが存在すればそれを返し、存在しなければ null を返します。 |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | デフォルトの段落プロパティ。 |
| [getEffective()](#getEffective--) | 継承が適用された有効なテキストスタイル書式設定データを取得します。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long。

**戻り値:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```

スタイルのレベルが存在すればそれを返し、存在しなければ null を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | レベルの 0 基準インデックス。0..8 の範囲内である必要があります。 |

**戻り値:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - レベル [IParagraphFormat](../../com.aspose.slides/iparagraphformat) の書式設定。
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```

デフォルトの段落プロパティ。読み取り専用 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**戻り値:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```

継承が適用された有効なテキストスタイル書式設定データを取得します。

--------------------

> ```
> This example demonstrates getting some of effective text style properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextStyleEffectiveData effectiveTextStyle = shape.getTextFrame().getTextFrameFormat().getTextStyle().getEffective();
>      for (int i = 0; i <= 8; i++)
>      {
>          IParagraphFormatEffectiveData effectiveStyleLevel = effectiveTextStyle.getLevel(i);
>          System.out.println("= Effective paragraph formatting for style level #" + i + " =");
>          System.out.println("Depth: " + effectiveStyleLevel.getDepth());
>          System.out.println("Indent: " + effectiveStyleLevel.getIndent());
>          System.out.println("Alignment: " + effectiveStyleLevel.getAlignment());
>          System.out.println("Font alignment: " + effectiveStyleLevel.getFontAlignment());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)。