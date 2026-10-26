---
title: ViewProperties
second_title: Αναφορά API Aspose.Slides για Java
description: Γενικές ιδιότητες προβολής παρουσίασης.
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

Γενικές ιδιότητες προβολής παρουσίασης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLastView()](#getLastView--) | Καθορίζει τη λειτουργία προβολής που χρησιμοποιήθηκε όταν το έγγραφο παρουσίασης αποθηκεύτηκε τελευταία. |
| [setLastView(int value)](#setLastView-int-) | Καθορίζει τη λειτουργία προβολής που χρησιμοποιήθηκε όταν το έγγραφο παρουσίασης αποθηκεύτηκε τελευταία. |
| [getShowComments()](#getShowComments--) | Καθορίζει εάν τα σχόλια της διαφάνειας πρέπει να εμφανίζονται. |
| [setShowComments(byte value)](#setShowComments-byte-) | Καθορίζει εάν τα σχόλια της διαφάνειας πρέπει να εμφανίζονται. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Αναπαριστά τις ιδιότητες κανονικής προβολής. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Καθορίζει τις κοινές ιδιότητες προβολής που σχετίζονται με τη λειτουργία προβολής διαφάνειας. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Καθορίζει τις κοινές ιδιότητες προβολής που σχετίζονται με τη λειτουργία προβολής σημειώσεων. |
| [getGridSpacing()](#getGridSpacing--) | Επιστρέφει ή ορίζει το διάστιχο πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα του εγγράφου παρουσίασης, σε μονάδες point. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Επιστρέφει ή ορίζει το διάστιχο πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα του εγγράφου παρουσίασης, σε μονάδες point. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

Καθορίζει τη λειτουργία προβολής που χρησιμοποιήθηκε όταν το έγγραφο παρουσίασης αποθηκεύτηκε τελευταία. Ανάγνωση/Εγγραφή [ViewType](../../com.aspose.slides/viewtype).

**Επιστρέφει:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

Καθορίζει τη λειτουργία προβολής που χρησιμοποιήθηκε όταν το έγγραφο παρουσίασης αποθηκεύτηκε τελευταία. Ανάγνωση/Εγγραφή [ViewType](../../com.aspose.slides/viewtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

Καθορίζει εάν τα σχόλια της διαφάνειας πρέπει να εμφανίζονται. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

Καθορίζει εάν τα σχόλια της διαφάνειας πρέπει να εμφανίζονται. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

Αναπαριστά τις ιδιότητες κανονικής προβολής. Η κανονική προβολή αποτελείται από τρεις περιοχές περιεχομένου: τη διαφάνεια, μια πλευρική περιοχή περιεχομένου και μια κάτω περιοχή περιεχομένου. Μόνο ανάγνωση [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

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

Επιστρέφει ή ορίζει το διάστιχο πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα του εγγράφου παρουσίασης, σε μονάδες point. Ανάγνωση/Εγγραφή float.

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

Η τιμή του διαστήματος πλέγματος πρέπει να είναι θετικός αριθμός. Η τυπική περιοχή τιμών είναι από 1 mm (2.8349607 points) έως 2 ίντσες (144 points).

**Επιστρέφει:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

Επιστρέφει ή ορίζει το διάστιχο πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα του εγγράφου παρουσίασης, σε μονάδες point. Ανάγνωση/Εγγραφή float.

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

Η τιμή του διαστήματος πλέγματος πρέπει να είναι θετικός αριθμός. Η τυπική περιοχή τιμών είναι από 1 mm (2.8349607 points) έως 2 ίντσες (144 points).

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