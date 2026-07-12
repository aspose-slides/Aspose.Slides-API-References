---
title: MathPortion
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 数学的コンテキストを持つ部分を表します。
type: docs
url: /ja/com.aspose.slides/mathportion/
---
**継承:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

数学的コンテキストを持つ部分を表します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>  	 IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 300, 50);
>  	 IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>  	 MathPortion mathPortion = new MathPortion();
>  	 paragraph.getPortions().add(mathPortion);
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathPortion()](#MathPortion--) | MathPortion クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Math段落 |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```

MathPortion クラスの新しいインスタンスを初期化します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>  	 IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 300, 50);
>  	 IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>  	 MathPortion mathPortion = new MathPortion();
>  	 paragraph.getPortions().add(mathPortion);
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```

### getMathParagraph() {#getMathParagraph--}
```
public final IMathParagraph getMathParagraph()
```

Math段落

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 300, 50);
>      IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      mathParagraph.add(new MathBlock(new MathematicalText("x+y")));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値：**
[IMathParagraph](../../com.aspose.slides/imathparagraph)