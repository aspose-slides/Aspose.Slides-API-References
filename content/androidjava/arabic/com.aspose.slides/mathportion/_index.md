---
title: MathPortion
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يمثل جزءًا بسياق رياضي داخله.
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

يمثل جزءًا بسياق رياضي بداخله.

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
## المُنشئون

| المنشئ | الوصف |
| --- | --- |
| [MathPortion()](#MathPortion--) | ينشئ مثيلًا جديدًا من فئة MathPortion. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | فقرة رياضية |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```

ينشئ مثيلًا جديدًا من فئة MathPortion.

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

**القيمة المرجعة:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph)