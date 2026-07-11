---
title: IMathPortion
second_title: Aspose.Slides for Android via Java API Reference
description: Αντιπροσωπεύει ένα τμήμα με μαθηματικό περιεχόμενο μέσα.
type: docs
url: /el/com.aspose.slides/imathportion/
---```
public interface IMathPortion
```

Αντιπροσωπεύει ένα τμήμα με μαθηματικό περιεχόμενο μέσα.

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
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Μαθηματική παράγραφος |
### getMathParagraph() {#getMathParagraph--}
```
public abstract IMathParagraph getMathParagraph()
```


Μαθηματική παράγραφος

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

**Επιστρέφει:**
[IMathParagraph](../../com.aspose.slides/imathparagraph)