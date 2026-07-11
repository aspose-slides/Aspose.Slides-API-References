---
title: ViewProperties
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Ιδιότητες προβολής για ολόκληρη την παρουσίαση.
type: docs
url: /el/com.aspose.slides/viewproperties/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Ιδιότητες προβολής για ολόκληρη την παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLastView()](#getLastView--) | Καθορίζει τη λειτουργία προβολής που χρησιμοποιήθηκε όταν το έγγραφο παρουσίασης αποθηκεύτηκε τελευταία φορά. |
| [setLastView(int value)](#setLastView-int-) | Καθορίζει τη λειτουργία προβολής που χρησιμοποιήθηκε όταν το έγγραφο παρουσίασης αποθηκεύτηκε τελευταία φορά. |
| [getShowComments()](#getShowComments--) | Καθορίζει εάν πρέπει να εμφανίζονται τα σχόλια διαφάνειας. |
| [setShowComments(byte value)](#setShowComments-byte-) | Καθορίζει εάν πρέπει να εμφανίζονται τα σχόλια διαφάνειας. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Αναπαριστά τις ιδιότητες κανονικής προβολής. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Καθορίζει τις κοινές ιδιότητες προβολής που σχετίζονται με τη λειτουργία προβολής διαφάνειας. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Καθορίζει τις κοινές ιδιότητες προβολής που σχετίζονται με τη λειτουργία προβολής σημειώσεων. |
| [getGridSpacing()](#getGridSpacing--) | Επιστρέφει ή ορίζει το διάστημα πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα που υποστηρίζει το έγγραφο παρουσίασης, σε σημεία. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Επιστρέφει ή ορίζει το διάστημα πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα που υποστηρίζει το έγγραφο παρουσίασης, σε σημεία. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

Καθορίζει τη λειτουργία προβολής που χρησιμοποιήθηκε όταν το έγγραφο παρουσίασης αποθηκεύτηκε τελευταία φορά. Ανάγνωση/Εγγραφή [ViewType](../../com.aspose.slides/viewtype).

**Επιστρέφει:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

Καθορίζει τη λειτουργία προβολής που χρησιμοποιήθηκε όταν το έγγραφο παρουσίασης αποθηκεύτηκε τελευταία φορά. Ανάγνωση/Εγγραφή [ViewType](../../com.aspose.slides/viewtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

Καθορίζει εάν πρέπει να εμφανίζονται τα σχόλια διαφάνειας. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

Καθορίζει εάν πρέπει να εμφανίζονται τα σχόλια διαφάνειας. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

Αναπαριστά τις ιδιότητες κανονικής προβολής. Η κανονική προβολή αποτελείται από τρεις περιοχές περιεχομένου: τη διαφάνεια ίδια, μια πλαϊνή περιοχή περιεχομένου και μια κάτω περιοχή περιεχομένου. Μόνο ανάγνωση [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Επιστρέφει:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

Καθορίζει τις κοινές ιδιότητες προβολής που σχετίζονται με τη λειτουργία προβολής διαφάνειας. Μόνο ανάγνωση [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Επιστρέφει:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

Καθορίζει τις κοινές ιδιότητες προβολής που σχετίζονται με τη λειτουργία προβολής σημειώσεων. Μόνο ανάγνωση [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Επιστρέφει:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

Επιστρέφει ή ορίζει το διάστημα πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα που υποστηρίζει το έγγραφο παρουσίασης, σε σημεία. Ανάγνωση/Εγγραφή float.

**Επιστρέφει:**
float
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
public final void setGridSpacing(float value)
```

Επιστρέφει ή ορίζει το διάστημα πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα που υποστηρίζει το έγγραφο παρουσίασης, σε σημεία. Ανάγνωση/Εγγραφή float.

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
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject