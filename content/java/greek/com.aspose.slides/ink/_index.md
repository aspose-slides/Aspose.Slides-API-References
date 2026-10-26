---
title: Ink
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει ένα αντικείμενο μελάνης σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/ink/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Αντιπροσωπεύει ένα αντικείμενο μελάνης σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTraces()](#getTraces--) | Λαμβάνει όλα τα ίχνη που περιέχονται στο στοιχείο IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | Λαμβάνει τη συλλογή των προσαρμοσμένων εικόνων που χρησιμοποιούνται για την προσομοίωση οπτικών εφέ για πινέλα μελάνης. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

Λαμβάνει όλα τα ίχνη που περιέχονται στο στοιχείο IInk [IInkTrace](../../com.aspose.slides/iinktrace). Μόνο για ανάγνωση.

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

Λαμβάνει τη συλλογή των προσαρμοσμένων εικόνων που χρησιμοποιούνται για την προσομοίωση οπτικών εφέ για πινέλα μελάνης. Αυτές οι εικόνες χρησιμοποιούνται κατά την απόδοση της μελάνης με συγκεκριμένες τιμές [InkEffectType](../../com.aspose.slides/inkeffecttype), όπως Galaxy, Rainbow κ.λπ. Παρέχοντας τις δικές σας εικόνες, μπορείτε να ελέγξετε πώς εμφανίζεται κάθε εφέ μελάνης.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

Αυτή η ιδιότητα επιτρέπει την αντικατάσταση των προεπιλεγμένων υφών εφέ μελάνης με δικές σας, κάτι που είναι ιδιαίτερα χρήσιμο όταν τα προεπιλεγμένα στοιχεία περιορίζονται από άδειες ή δεν είναι διαθέσιμα κατά την εκτέλεση. Κάθε καταχώρηση στο λεξικό πρέπει να συσχετίζει μια τιμή [InkEffectType](../../com.aspose.slides/inkeffecttype) με ένα αντίστοιχο αντικείμενο [IImage](../../com.aspose.slides/iimage) (π.χ., Bitmap ή μια διεπαφή εικόνας Aspose).

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>