---
title: IViewProperties
second_title: Aspose.Slides for Java API Reference
description: Ιδιότητες προβολής σε όλη την παρουσίαση.
type: docs
url: /el/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Ιδιότητες προβολής σε όλη την παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLastView()](#getLastView--) | Καθορίζει τη λειτουργία προβολής που χρησιμοποιήθηκε όταν το έγγραφο παρουσίασης αποθηκεύτηκε τελευταία. |
| [setLastView(int value)](#setLastView-int-) | Καθορίζει τη λειτουργία προβολής που χρησιμοποιήθηκε όταν το έγγραφο παρουσίασης αποθηκεύτηκε τελευταία. |
| [getShowComments()](#getShowComments--) | Καθορίζει εάν πρέπει να εμφανίζονται τα σχόλια διαφάνειας. |
| [setShowComments(byte value)](#setShowComments-byte-) | Καθορίζει εάν πρέπει να εμφανίζονται τα σχόλια διαφάνειας. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Καθορίζει τις κοινές ιδιότητες προβολής που σχετίζονται με τη λειτουργία προβολής διαφάνειας. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Καθορίζει τις κοινές ιδιότητες προβολής που σχετίζονται με τη λειτουργία προβολής σημειώσεων. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Αντιπροσωπεύει τις ιδιότητες κανονικής προβολής. |
| [getGridSpacing()](#getGridSpacing--) | Επιστρέφει ή ορίζει το διάστημα πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα που υποστηρίζει το έγγραφο παρουσίασης, σε σημεία. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Επιστρέφει ή ορίζει το διάστημα πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα που υποστηρίζει το έγγραφο παρουσίασης, σε σημεία. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Καθορίζει τη λειτουργία προβολής που χρησιμοποιήθηκε όταν το έγγραφο παρουσίασης αποθηκεύτηκε τελευταία. Ανάγνωση/εγγραφή [ViewType](../../com.aspose.slides/viewtype).

**Επιστρέφει:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Καθορίζει τη λειτουργία προβολής που χρησιμοποιήθηκε όταν το έγγραφο παρουσίασης αποθηκεύτηκε τελευταία. Ανάγνωση/εγγραφή [ViewType](../../com.aspose.slides/viewtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Καθορίζει εάν πρέπει να εμφανίζονται τα σχόλια διαφάνειας. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Καθορίζει εάν πρέπει να εμφανίζονται τα σχόλια διαφάνειας. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Καθορίζει τις κοινές ιδιότητες προβολής που σχετίζονται με τη λειτουργία προβολής διαφάνειας. Μόνο για ανάγνωση [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Επιστρέφει:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Καθορίζει τις κοινές ιδιότητες προβολής που σχετίζονται με τη λειτουργία προβολής σημειώσεων. Μόνο για ανάγνωση [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Επιστρέφει:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Αντιπροσωπεύει τις ιδιότητες κανονικής προβολής. Η κανονική προβολή αποτελείται από τρεις περιοχές περιεχομένου: τη διαφάνεια καθαυτή, μια πλευρική περιοχή περιεχομένου και μια κατώτερη περιοχή περιεχομένου. Μόνο για ανάγνωση [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Επιστρέφει:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Επιστρέφει ή ορίζει το διάστημα πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα που υποστηρίζει το έγγραφο παρουσίασης, σε σημεία. Ανάγνωση/εγγραφή float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Η τιμή του διαστήματος πλέγματος πρέπει να είναι θετικός αριθμός. Το τυπικό εύρος τιμών είναι από 1 mm (2.8349607 σημεία) έως 2 ίντσες (144 σημεία).

**Επιστρέφει:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Επιστρέφει ή ορίζει το διάστημα πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα που υποστηρίζει το έγγραφο παρουσίασης, σε σημεία. Ανάγνωση/εγγραφή float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Η τιμή του διαστήματος πλέγματος πρέπει να είναι θετικός αριθμός. Το τυπικό εύρος τιμών είναι από 1 mm (2.8349607 σημεία) έως 2 ίντσες (144 σημεία).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |