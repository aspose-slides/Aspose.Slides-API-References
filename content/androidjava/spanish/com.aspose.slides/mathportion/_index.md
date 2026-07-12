---
title: MathPortion
second_title: Aspose.Slides para Android mediante la API de Java
description: Representa una porción con contexto matemático dentro.
type: docs
url: /es/com.aspose.slides/mathportion/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

Representa una porción con contexto matemático dentro.

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
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathPortion()](#MathPortion--) | Inicializa una nueva instancia de la clase MathPortion. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Párrafo matemático |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```

Inicializa una nueva instancia de la clase MathPortion.

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

Párrafo matemático

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

**Devuelve:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)