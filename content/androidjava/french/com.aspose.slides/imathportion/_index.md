---
title: IMathPortion
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une portion avec un contexte mathématique à l'intérieur.
type: docs
url: /fr/com.aspose.slides/imathportion/
---```
public interface IMathPortion
```

Représente une portion avec un contexte mathématique à l'intérieur.

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
## Methods

| Method | Description |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Math paragraph |
### getMathParagraph() {#getMathParagraph--}
```
public abstract IMathParagraph getMathParagraph()

Paragraphe mathématique

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

**Renvoie :**
[IMathParagraph](../../com.aspose.slides/imathparagraph)