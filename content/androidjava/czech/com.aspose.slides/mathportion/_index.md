---
title: MathPortion
second_title: Aspose.Slides pro Android prostřednictvím Java API
description: Reprezentuje část s matematickým kontextem uvnitř.
type: docs
url: /cs/com.aspose.slides/mathportion/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

Reprezentuje část s matematickým kontextem uvnitř.

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
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathPortion()](#MathPortion--) | Inicializuje novou instanci třídy MathPortion. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Matematický odstavec |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```


Inicializuje novou instanci třídy MathPortion.

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


Matematický odstavec

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

**Vrací:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)