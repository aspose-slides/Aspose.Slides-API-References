---
title: MathPortion
second_title: Aspose.Slides لمرجع واجهة برمجة تطبيقات جافا
description: يمثل جزءًا بسياق رياضي داخلي.
type: docs
url: /ar/com.aspose.slides/mathportion/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

يمثل جزءًا بسياق رياضي داخل.

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
## المنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MathPortion()](#MathPortion--) | يهيء نسخة جديدة من الفئة MathPortion. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | فقرة رياضية |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```

تهيء نسخة جديدة من الفئة MathPortion.

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

فقرة رياضية

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

**الإرجاع:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)