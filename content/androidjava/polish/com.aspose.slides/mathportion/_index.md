---
title: MathPortion
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Reprezentuje fragment z kontekstem matematycznym wewnątrz.
type: docs
url: /pl/com.aspose.slides/mathportion/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

Reprezentuje fragment z kontekstem matematycznym wewnątrz.

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

| Konstruktor | Opis |
| --- | --- |
| [MathPortion()](#MathPortion--) | Inicjalizuje nową instancję klasy MathPortion. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Akapit matematyczny |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```


Inicjalizuje nową instancję klasy MathPortion.

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