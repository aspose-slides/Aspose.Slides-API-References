---
title: IMathPortion
second_title: Aspose.Slides for Android via Java API Referenciája
description: Matematikai kontextussal rendelkező részt ábrázol.
type: docs
url: /hu/com.aspose.slides/imathportion/
---```
public interface IMathPortion
```

Matematikai kontextussal rendelkező részt ábrázol.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 300, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      MathPortion mathPortion = new MathPortion();
>      paragraph.getPortions().add(mathPortion);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Matematikai bekezdés |
### getMathParagraph() {#getMathParagraph--}
```
public abstract IMathParagraph getMathParagraph()
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

**Visszatér:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)