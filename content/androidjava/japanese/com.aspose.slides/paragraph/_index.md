---
title: Paragraph
second_title: Aspose.Slides for Android の Java API リファレンス
description: テキストの段落を表します。
type: docs
url: /ja/com.aspose.slides/paragraph/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

テキストの段落を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Paragraph()](#Paragraph--) | Paragraph クラスの新しいインスタンスをデフォルト プロパティで初期化します。 |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Paragraph クラスの新しいインスタンスを初期化するコピーコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPortions()](#getPortions--) | テキスト部分のコレクションを返します。 |
| [getParagraphFormat()](#getParagraphFormat--) | この段落の書式設定オブジェクトを返します。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 同じ書式設定のランを結合します。 |
| [getText()](#getText--) | 段落のプレーンテキストを取得または設定します。 |
| [setText(String value)](#setText-java.lang.String-) | 段落のプレーンテキストを取得または設定します。 |
| [getRect()](#getRect--) | 段落を囲む矩形の座標を取得します。 |
| [getLinesCount()](#getLinesCount--) | 段落の行数を取得します。 |
| [getImage()](#getImage--) | 段落の画像を返します。 |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | 指定されたスケールで段落の画像を返します。 |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | 最後の部分の後に別の部分が挿入された場合に使用される部分プロパティを指定します。 |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | 最後の部分の後に別の部分が挿入された場合に使用される部分プロパティを指定します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | 段落の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | 段落の親プレゼンテーションを返します。 |

### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Paragraph クラスの新しいインスタンスをデフォルト プロパティで初期化します。

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

Paragraph クラスの新しいインスタンスを初期化するコピーコンストラクタです。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

テキスト部分のコレクションを返します。読み取り専用 [IPortionCollection](../../com.aspose.slides/iportioncollection)。

**戻り値:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)

### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

この段落の書式設定オブジェクトを返します。読み取り専用 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

--------------------

書式設定オブジェクトは現在の段落に対して定義された書式パラメータのみを含み、継承されたデータは適用されません。

継承された値を含む実効値を取得するには、[ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) メソッドを使用します。

**戻り値:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

同じ書式設定のランを結合します。

### getText() {#getText--}
```
public final String getText()
```

段落のプレーンテキストを取得または設定します。読み取り/書き込み String。

値: テキスト。

**戻り値:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

段落のプレーンテキストを取得または設定します。読み取り/書き込み String。

値: テキスト。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```

段落を囲む矩形の座標を取得します。この矩形は段落内のすべてのテキスト行（空行を含む）を含みます。

**戻り値:**
android.graphics.RectF

### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

段落の行数を取得します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
int - 段落の行数

### getImage() {#getImage--}
```
public final IImage getImage()
```

段落の画像を返します。

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - 描画された段落を含む画像、または段落が親コレクションに見つからない、または有効な描画境界がない、あるいは画像の描画中にエラーが発生した場合は null。

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

指定されたスケールで段落の画像を返します。

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scaleX | float | 段落画像に適用される水平スケール係数。 |
| scaleY | float | 段落画像に適用される垂直スケール係数。 |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - 描画された段落を含む画像、または段落が親コレクションに見つからない、または有効な描画境界がない、あるいは画像の描画中にエラーが発生した場合は null。

### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

最後の部分の後に別の部分が挿入された場合に使用される部分プロパティを指定します。

**戻り値:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

最後の部分の後に別の部分が挿入された場合に使用される部分プロパティを指定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

段落の親スライドを返します。読み取り専用 [BaseSlide](../../com.aspose.slides/baseslide)。

**戻り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

段落の親プレゼンテーションを返します。読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation)