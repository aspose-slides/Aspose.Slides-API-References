---
title: ParagraphFormat
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: このクラスは段落書式設定プロパティを含んでいます。
type: docs
url: /ja/com.aspose.slides/paragraphformat/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)  
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

このクラスは段落書式設定プロパティを保持します。[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) とは異なり、このクラスのすべてのプロパティは書き込み可能です。

--------------------

このクラスは、特定の段落に定義された段落書式設定プロパティを取得および操作するために使用されます。値を取得する際に継承が適用されないため、ほとんどの場合「未定義」を意味する値が返されます。

継承された書式パラメータの有効な値を取得するには、[getEffective](../../com.aspose.slides/paragraphformat\#getEffective) メソッドを使用し、[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) インスタンスを返します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | [ParagraphFormat](../../com.aspose.slides/paragraphformat) クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBullet()](#getBullet--) | 段落の箇条書き形式を返します。 |
| [getDepth()](#getDepth--) | 段落の深さを取得または設定します。 |
| [setDepth(short value)](#setDepth-short-) | 段落の深さを取得または設定します。 |
| [getAlignment()](#getAlignment--) | 継承なしで段落のテキスト配置を取得または設定します。 |
| [setAlignment(int value)](#setAlignment-int-) | 継承なしで段落のテキスト配置を取得または設定します。 |
| [getSpaceWithin()](#getSpaceWithin--) | 継承なしで段落の基準線間のスペースを取得または設定します。 |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | 継承なしで段落の基準線間のスペースを取得または設定します。 |
| [getSpaceBefore()](#getSpaceBefore--) | 継承なしで段落の最初の行の前のスペースを取得または設定します。 |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | 継承なしで段落の最初の行の前のスペースを取得または設定します。 |
| [getSpaceAfter()](#getSpaceAfter--) | 継承なしで段落の最後の行の後のスペースを取得または設定します。 |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | 継承なしで段落の最後の行の後のスペースを取得または設定します。 |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | 段落で東アジアの改行が使用されているかどうかを判定します。 |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | 段落で東アジアの改行が使用されているかどうかを判定します。 |
| [getRightToLeft()](#getRightToLeft--) | 段落で右から左への書字が使用されているかどうかを判定します。 |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | 段落で右から左への書字が使用されているかどうかを判定します。 |
| [getLatinLineBreak()](#getLatinLineBreak--) | 段落でラテン文字の改行が使用されているかどうかを判定します。 |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | 段落でラテン文字の改行が使用されているかどうかを判定します。 |
| [getHangingPunctuation()](#getHangingPunctuation--) | 段落でハンギング句読点が使用されているかどうかを判定します。 |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | 段落でハンギング句読点が使用されているかどうかを判定します。 |
| [getMarginLeft()](#getMarginLeft--) | 継承なしで段落の左余白を取得または設定します。 |
| [setMarginLeft(float value)](#setMarginLeft-float-) | 継承なしで段落の左余白を取得または設定します。 |
| [getMarginRight()](#getMarginRight--) | 継承なしで段落の右余白を取得または設定します。 |
| [setMarginRight(float value)](#setMarginRight-float-) | 継承なしで段落の右余白を取得または設定します。 |
| [getIndent()](#getIndent--) | 継承なしで段落の1行目インデント/ハンギングインデントを取得または設定します。 |
| [setIndent(float value)](#setIndent-float-) | 継承なしで段落の1行目インデント/ハンギングインデントを取得または設定します。 |
| [getDefaultTabSize()](#getDefaultTabSize--) | 継承なしでデフォルトタブサイズを取得または設定します。 |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | 継承なしでデフォルトタブサイズを取得または設定します。 |
| [getTabs()](#getTabs--) | 段落のタブ情報を取得します。 |
| [getFontAlignment()](#getFontAlignment--) | 継承なしで段落のフォント配置を取得または設定します。 |
| [setFontAlignment(int value)](#setFontAlignment-int-) | 継承なしで段落のフォント配置を取得または設定します。 |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | 段落のデフォルト部分書式を取得します。 |
| [getEffective()](#getEffective--) | 継承を適用した有効な段落書式データを取得します。 |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

[ParagraphFormat](../../com.aspose.slides/paragraphformat) クラスの新しいインスタンスを初期化します。

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

段落の箇条書き形式を返します。読み取り専用 [IBulletFormat](../../com.aspose.slides/ibulletformat)。

**戻り値:**  
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public final short getDepth()
```

段落の深さを取得または設定します。値 0 は未定義を意味します。読み書き short 。

**戻り値:**  
short

### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

段落の深さを取得または設定します。値 0 は未定義を意味します。読み書き short 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

継承なしで段落のテキスト配置を取得または設定します。読み書き [TextAlignment](../../com.aspose.slides/textalignment)。

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // PPTX ファイルを表す Presentation オブジェクトをインスタンス化します
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // 最初のスライドにアクセス
>      ISlide slide = pres.getSlides().get_Item(0);
>      // スライド内の最初と2番目のプレースホルダーにアクセスし、AutoShape に型キャストします
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // 両方のプレースホルダーのテキストを変更します
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // プレースホルダーの最初の段落を取得します
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // テキスト段落を中央揃えにします
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // プレゼンテーションを PPTX ファイルとして書き込みます
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**  
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

継承なしで段落のテキスト配置を取得または設定します。読み書き [TextAlignment](../../com.aspose.slides/textalignment)。

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // PPTX ファイルを表す Presentation オブジェクトをインスタンス化します
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // 最初のスライドにアクセス
>      ISlide slide = pres.getSlides().get_Item(0);
>      // スライド内の最初と2番目のプレースホルダーにアクセスし、AutoShape に型キャストします
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // 両方のプレースホルダーのテキストを変更します
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // プレースホルダーの最初の段落を取得します
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // テキスト段落を中央揃えにします
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Writing プレゼンテーションを PPTX ファイルとして書き込みます
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

継承なしで段落の基準線間のスペースを取得または設定します。正の値はパーセンテージ、負の値はポイントサイズです。読み書き float 。

**戻り値:**  
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

継承なしで段落の基準線間のスペースを取得または設定します。正の値はパーセンテージ、負の値はポイントサイズです。読み書き float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

継承なしで段落の最初の行の前のスペースを取得または設定します。正の値はフォントサイズに対するパーセンテージ、負の値はポイントサイズで指定します。読み書き float 。

**戻り値:**  
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

継承なしで段落の最初の行の前のスペースを取得または設定します。正の値はフォントサイズに対するパーセンテージ、負の値はポイントサイズで指定します。読み書き float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

継承なしで段落の最後の行の後のスペースを取得または設定します。正の値はフォントサイズに対するパーセンテージ、負の値はポイントサイズで指定します。読み書き float 。

**戻り値:**  
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

継承なしで段落の最後の行の後のスペースを取得または設定します。正の値はフォントサイズに対するパーセンテージ、負の値はポイントサイズで指定します。読み書き float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

段落で東アジアの改行が使用されているかどうかを判定します。継承なし。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**  
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

段落で東アジアの改行が使用されているかどうかを判定します。継承なし。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

段落で右から左への書字が使用されているかどうかを判定します。継承なし。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**  
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

段落で右から左への書字が使用されているかどうかを判定します。継承なし。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

段落でラテン文字の改行が使用されているかどうかを判定します。継承なし。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**  
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

段落でラテン文字の改行が使用されているかどうかを判定します。継承なし。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

段落でハンギング句読点が使用されているかどうかを判定します。継承なし。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**  
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

段落でハンギング句読点が使用されているかどうかを判定します。継承なし。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

継承なしで段落の左余白を取得または設定します。読み書き float 。

**戻り値:**  
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

継承なしで段落の左余白を取得または設定します。読み書き float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

継承なしで段落の右余白を取得または設定します。読み書き float 。

**戻り値:**  
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

継承なしで段落の右余白を取得または設定します。読み書き float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

継承なしで段落の1行目インデント/ハンギングインデントを取得または設定します。ハンギングインデントは負の値で定義できます。読み書き float 。

**戻り値:**  
float

### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

継承なしで段落の1行目インデント/ハンギングインデントを取得または設定します。ハンギングインデントは負の値で定義できます。読み書き float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

継承なしでデフォルトタブサイズを取得または設定します。読み書き float 。

**戻り値:**  
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

継承なしでデフォルトタブサイズを取得または設定します。読み書き float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

段落のタブ情報を取得します。継承なし。読み取り専用 [ITabCollection](../../com.aspose.slides/itabcollection)。

**戻り値:**  
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

継承なしでフォント配置を取得または設定します。読み書き [FontAlignment](../../com.aspose.slides/fontalignment)。

**戻り値:**  
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

継承なしでフォント配置を取得または設定します。読み書き [FontAlignment](../../com.aspose.slides/fontalignment)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

段落のデフォルト部分書式を取得します。継承なし。読み取り専用 [IPortionFormat](../../com.aspose.slides/iportionformat)。

**戻り値:**  
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

継承を適用した有効な段落書式データを取得します。

--------------------

> ```
> この例は、いくつかの有効な段落書式プロパティを取得する方法を示しています。
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**  
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)。

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long。

**戻り値:**  
long