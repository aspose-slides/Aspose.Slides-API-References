---
title: CommonSlideViewProperties
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά κοινές ιδιότητες προβολής διαφάνειας.
type: docs
url: /el/com.aspose.slides/commonslideviewproperties/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Αναπαριστά κοινά χαρακτηριστικά προβολής διαφάνειας.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Δημιουργεί ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Ορισμός ιδιοτήτων προβολής της παρουσίασης
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Τιμή ζουμ σε ποσοστά για προβολή διαφάνειας
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Τιμή ζουμ σε ποσοστά για προβολή σημειώσεων
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getScale()](#getScale--) | Καθορίζει το λόγο κλιμάκωσης της προβολής σε ποσοστά. |
| [setScale(int value)](#setScale-int-) | Καθορίζει το λόγο κλιμάκωσης της προβολής σε ποσοστά. |
| [getVariableScale()](#getVariableScale--) | Καθορίζει ότι το περιεχόμενο της προβολής πρέπει να κλιμακώνεται αυτόματα ώστε να ταιριάζει καλύτερα στο τρέχον μέγεθος παραθύρου. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Καθορίζει ότι το περιεχόμενο της προβολής πρέπει να κλιμακώνεται αυτόματα ώστε να ταιριάζει καλύτερα στο τρέχον μέγεθος παραθύρου. |
| [getDrawingGuides()](#getDrawingGuides--) | Επιστρέφει τη συλλογή των οδηγών σχεδίασης. |
### getScale() {#getScale--}
```
public final int getScale()
```


Καθορίζει το λόγο κλιμάκωσης της προβολής σε ποσοστά. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Καθορίζει το λόγο κλιμάκωσης της προβολής σε ποσοστά. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```


Καθορίζει ότι το περιεχόμενο της προβολής πρέπει να κλιμακώνεται αυτόματα ώστε να ταιριάζει καλύτερα στο τρέχον μέγεθος παραθύρου. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```


Καθορίζει ότι το περιεχόμενο της προβολής πρέπει να κλιμακώνεται αυτόματα ώστε να ταιριάζει καλύτερα στο τρέχον μέγεθος παραθύρου. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Επιστρέφει τη συλλογή των οδηγών σχεδίασης. Μόνο ανάγνωση [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Προσθήκη του νέου κάθετου οδηγού σχεδίασης δεξιά του κέντρου της διαφάνειας
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Προσθήκη του νέου οριζόντιου οδηγού σχεδίασης κάτω από το κέντρο της διαφάνειας
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)