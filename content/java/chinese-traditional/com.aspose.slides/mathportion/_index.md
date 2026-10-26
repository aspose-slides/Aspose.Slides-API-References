---
title: MathPortion
second_title: Aspose.Slides for Java API 參考
description: 表示內部具有數學環境的部分。
type: docs
url: /zh-hant/com.aspose.slides/mathportion/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**所有實作的介面：**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

表示內部具有數學環境的部分。

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

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [MathPortion()](#MathPortion--) | 初始化 MathPortion 類別的新執行個體。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | 數學段落 |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```

初始化 MathPortion 類別的新執行個體。

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

數學段落

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


**傳回值：**
[IMathParagraph](../../com.aspose.slides/imathparagraph)