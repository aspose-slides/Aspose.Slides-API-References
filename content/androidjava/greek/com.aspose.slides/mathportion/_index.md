---
title: MathPortion
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεί ένα τμήμα με μαθηματικό περιεχόμενο μέσα.
type: docs
url: /el/com.aspose.slides/mathportion/
---
**Κληρονομιά:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

Αντιπροσωπεί ένα τμήμα με μαθηματικό περιεχόμενο μέσα.

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
## Κατασκευαστές

| Constructor | Περιγραφή |
| --- | --- |
| [MathPortion()](#MathPortion--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathPortion. |
## Μέθοδοι

| Method | Περιγραφή |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Παράγραφος μαθηματικών |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathPortion.

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


Παράγραφος μαθηματικών

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