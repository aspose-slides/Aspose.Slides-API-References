---
title: MathPortion
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Matematikai kontextussal rendelkező részt képvisel.
type: docs
url: /hu/com.aspose.slides/mathportion/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

Matematikai kontextussal rendelkező részt képvisel.

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
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathPortion()](#MathPortion--) | Új példányt hoz létre a MathPortion osztályból. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Matematikai bekezdés |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```

Új példányt hoz létre a MathPortion osztályból.

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

Matematikai bekezdés

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

**Visszatérési érték:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)