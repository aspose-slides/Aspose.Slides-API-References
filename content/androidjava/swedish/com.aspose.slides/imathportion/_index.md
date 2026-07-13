---
title: IMathPortion
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar en del med matematisk kontext inuti.
type: docs
url: /sv/com.aspose.slides/imathportion/
---```
public interface IMathPortion
```

Representerar en del med matematisk kontext inuti.

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
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Matematisk stycke |
### getMathParagraph() {#getMathParagraph--}
```
public abstract IMathParagraph getMathParagraph()
```


Matematisk stycke

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

**Returnerar:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)