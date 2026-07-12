---
title: IParagraph
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: テキストの段落を表します。
type: docs
url: /ja/com.aspose.slides/iparagraph/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

テキストの段落を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPortions()](#getPortions--) | テキスト部分のコレクションを返します。 |
| [getParagraphFormat()](#getParagraphFormat--) | この段落の書式オブジェクトを返します。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 同じ書式のランを結合します。 |
| [getText()](#getText--) | 段落のプレーンテキストを取得または設定します。 |
| [setText(String value)](#setText-java.lang.String-) | 段落のプレーンテキストを取得または設定します。 |
| [getRect()](#getRect--) | 段落を囲む矩形の座標を取得します。 |
| [getLinesCount()](#getLinesCount--) | 段落の行数を取得します。 |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | 最後の部分の後に別の部分が挿入された場合に使用される部分プロパティを指定します。 |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | 最後の部分の後に別の部分が挿入された場合に使用される部分プロパティを指定します。 |

### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

テキスト部分のコレクションを返します。読み取り専用 [IPortionCollection](../../com.aspose.slides/iportioncollection)。

**戻り値:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)

### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

この段落の書式オブジェクトを返します。読み取り専用 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**戻り値:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

同じ書式のランを結合します。

### getText() {#getText--}
```
public abstract String getText()
```

段落のプレーンテキストを取得または設定します。読み取り/書き込み String。

値: テキスト。

**戻り値:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

段落のプレーンテキストを取得または設定します。読み取り/書き込み String。

値: テキスト。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract RectF getRect()
```

段落を囲む矩形の座標を取得します。矩形は段落内のすべてのテキスト行（空行も含む）を含みます。

**戻り値:**
android.graphics.RectF - 段落を囲む矩形 android.graphics.RectF

### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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

**戻り値:** int - 段落の行数

### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

最後の部分の後に別の部分が挿入された場合に使用される部分プロパティを指定します。

**戻り値:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

最後の部分の後に別の部分が挿入された場合に使用される部分プロパティを指定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |