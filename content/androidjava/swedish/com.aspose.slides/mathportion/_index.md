---
title: MathPortion
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en del med matematisk kontext inuti.
type: docs
url: /sv/com.aspose.slides/mathportion/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

Representerar en del med matematisk kontext inuti.

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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathPortion()](#MathPortion--) | Skapar en ny instans av klassen MathPortion. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Matematiskt stycke |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```


Skapar en ny instans av klassen MathPortion.

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


Matematiskt stycke

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