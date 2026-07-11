---
title: IMathPortion
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет часть с математическим контекстом внутри.
type: docs
url: /ru/com.aspose.slides/imathportion/
---```
public interface IMathPortion
```

Представляет часть с математическим контекстом внутри.

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
## Методы

| Метод | Описание |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Математический абзац |
### getMathParagraph() {#getMathParagraph--}
```
public abstract IMathParagraph getMathParagraph()
```


Математический абзац

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

**Возвращаемое значение:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)