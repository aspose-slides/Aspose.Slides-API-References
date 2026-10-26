---
title: MathPortion
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een gedeelte met wiskundige context voor.
type: docs
url: /nl/com.aspose.slides/mathportion/
---
**Overerving:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

Stelt een gedeelte met wiskundige context voor.

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
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MathPortion()](#MathPortion--) | Initialiseert een nieuw exemplaar van de MathPortion-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Wiskundig alinea |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```


Initialiseert een nieuw exemplaar van de MathPortion-klasse.

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


Wiskundig alinea

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


**Retour:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)