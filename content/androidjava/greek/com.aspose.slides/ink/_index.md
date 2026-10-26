---
title: Ink
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει ένα αντικείμενο μελάνης σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/ink/
---
**Κληρονομία:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Αναπαριστά ένα αντικείμενο μελάνης σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTraces()](#getTraces--) | Ανακτά όλα τα ίχνη που περιέχονται στο στοιχείο IInk [IInkTrace](../../com.aspose.slides/iinktrace). Μόνο για ανάγνωση. |
| [getInkEffectImages()](#getInkEffectImages--) | Ανακτά τη συλλογή προσαρμοσμένων εικόνων που χρησιμοποιούνται για την προσομοίωση οπτικών εφέ για πινέλα μελάνης. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

Ανακτά όλα τα ίχνη που περιέχονται στο στοιχείο IInk [IInkTrace](../../com.aspose.slides/iinktrace). Μόνο για ανάγνωση.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```

Ανακτά τη συλλογή προσαρμοσμένων εικόνων που χρησιμοποιούνται για την προσομοίωση οπτικών εφέ για πινέλα μελάνης. Αυτές οι εικόνες χρησιμοποιούνται κατά τη σχεδίαση της μελάνης με συγκεκριμένες τιμές [InkEffectType](../../com.aspose.slides/inkeffecttype), όπως Galaxy, Rainbow κ.λπ. Παρέχοντας τις δικές σας εικόνες, μπορείτε να ελέγξετε πώς εμφανίζεται κάθε εφέ μελάνης.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

Αυτή η ιδιότητα επιτρέπει την αντικατάσταση των προεπιλεγμένων υφών εφέ μελάνης με αυτές που ορίζονται από τον χρήστη, κάτι που είναι ιδιαίτερα χρήσιμο όταν τα προεπιλεγμένα στοιχεία περιορίζονται από άδειες ή δεν είναι διαθέσιμα κατά την εκτέλεση. Κάθε καταχώριση στο λεξικό πρέπει να συσχετίζει μια τιμή [InkEffectType](../../com.aspose.slides/inkeffecttype) με το αντίστοιχο αντικείμενο [IImage](../../com.aspose.slides/iimage) (π.χ., Bitmap ή διεπαφή εικόνας Aspose).

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>