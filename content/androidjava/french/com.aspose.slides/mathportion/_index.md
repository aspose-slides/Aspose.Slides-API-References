---
title: MathPortion
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Représente une portion avec un contexte mathématique à l'intérieur.
type: docs
url: /fr/com.aspose.slides/mathportion/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

Représente une portion avec un contexte mathématique à l'intérieur.

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
## Constructors

| Constructor | Description |
| --- | --- |
| [MathPortion()](#MathPortion--) | Initializes a new instance of the MathPortion class. |
## Methods

| Method | Description |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Math paragraph |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```

Initializes a new instance of the MathPortion class.

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

Math paragraph

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

**Renvoie:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph)