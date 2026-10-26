---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Αποπροσωπεύει τις κοινές ιδιότητες προβολής διαφάνειας.
type: docs
url: /el/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Αποπροσωπεύει τις κοινές ιδιότητες προβολής διαφάνειας.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getScale()](#getScale--) | Καθορίζει το λόγο κλιμάκωσης της προβολής σε ποσοστό. |
| [setScale(int value)](#setScale-int-) | Καθορίζει το λόγο κλιμάκωσης της προβολής σε ποσοστό. |
| [getVariableScale()](#getVariableScale--) | Καθορίζει ότι το περιεχόμενο της προβολής θα πρέπει να κλιμακώνεται αυτόματα ώστε να ταιριάζει καλύτερα στο μέγεθος του τρέχοντος παραθύρου. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Καθορίζει ότι το περιεχόμενο της προβολής θα πρέπει να κλιμακώνεται αυτόματα ώστε να ταιριάζει καλύτερα στο μέγεθος του τρέχοντος παραθύρου. |
| [getDrawingGuides()](#getDrawingGuides--) | Επιστρέφει τη συλλογή των οδηγών σχεδίασης. |

### getScale() {#getScale--}
```
public abstract int getScale()
```

Καθορίζει το λόγο κλιμάκωσης της προβολής σε ποσοστό. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

Καθορίζει το λόγο κλιμάκωσης της προβολής σε ποσοστό. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

Καθορίζει ότι το περιεχόμενο της προβολής θα πρέπει να κλιμακώνεται αυτόματα ώστε να ταιριάζει καλύτερα στο μέγεθος του τρέχοντος παραθύρου. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

Καθορίζει ότι το περιεχόμενο της προβολής θα πρέπει να κλιμακώνεται αυτόματα ώστε να ταιριάζει καλύτερα στο μέγεθος του τρέχοντος παραθύρου. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Επιστρέφει τη συλλογή των οδηγών σχεδίασης. Μόνο για ανάγνωση [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Προσθήκη της νέας κατακόρυφης οδηγού σχεδίασης δεξιά του κέντρου της διαφάνειας
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // Προσθήκη της νέας οριζόντιας οδηγού σχεδίασης κάτω από το κέντρο της διαφάνειας
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)