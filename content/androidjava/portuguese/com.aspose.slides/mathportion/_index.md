---
title: MathPortion
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma porção com contexto matemático interno.
type: docs
url: /pt/com.aspose.slides/mathportion/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

Representa uma porção com contexto matemático interno.

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
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathPortion()](#MathPortion--) | Inicializa uma nova instância da classe MathPortion. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Parágrafo de matemática |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```

Inicializa uma nova instância da classe MathPortion.

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

Parágrafo de matemática

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

**Retorna:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)