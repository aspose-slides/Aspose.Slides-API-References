---
title: MathPortion
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά ένα τμήμα με μαθηματικό περιεχόμενο.
type: docs
url: /el/com.aspose.slides/mathportion/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)
```
public final class MathPortion extends Portion implements IMathPortion
```

Αναπαριστά ένα τμήμα με μαθηματικό περιεχόμενο.

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

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathPortion()](#MathPortion--) | Αρχικοποιεί μια νέα παρουσία της κλάσης MathPortion. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | Παράγραφος μαθηματικών |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης MathPortion.

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