---
title: MathPortion
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una porzione con contesto matematico interno.
type: docs
url: /it/com.aspose.slides/mathportion/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

Rappresenta una porzione con contesto matematico interno.

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
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathPortion()](#MathPortion--) | Inizializza una nuova istanza della classe MathPortion. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Paragrafo matematico |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```

Inizializza una nuova istanza della classe MathPortion.

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

Paragrafo matematico

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

**Restituisce:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)