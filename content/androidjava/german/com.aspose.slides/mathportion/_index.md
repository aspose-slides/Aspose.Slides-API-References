---
title: MathPortion
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Abschnitt mit mathematischem Kontext dar.
type: docs
url: /de/com.aspose.slides/mathportion/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

Stellt einen Abschnitt mit mathematischem Kontext dar.

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathPortion()](#MathPortion--) | Initialisiert eine neue Instanz der MathPortion-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Mathematischer Absatz |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```

Initialisiert eine neue Instanz der MathPortion-Klasse.

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

Mathematischer Absatz

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

**Rückgabewert:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)