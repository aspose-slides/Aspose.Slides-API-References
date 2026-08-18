---
title: IMathPortion
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje fragment z kontekstem matematycznym wewnątrz.
type: docs
url: /pl/com.aspose.slides/imathportion/
---```
public interface IMathPortion
```

Reprezentuje fragment z kontekstem matematycznym wewnątrz.

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
## Metody

| Metoda | Opis |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Akapit matematyczny |
### getMathParagraph() {#getMathParagraph--}
```
public abstract IMathParagraph getMathParagraph()
```


Akapit matematyczny

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

**Zwraca:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)