---
title: SummaryZoomSectionCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά μια συλλογή αντικειμένων Summary Zoom Section.
type: docs
url: /el/com.aspose.slides/summaryzoomsectioncollection/
---
**Κληρονομικότητα:**  
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**  
[com.aspose.slides.ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)  
```
public final class SummaryZoomSectionCollection extends DomObject<SummaryZoomFrame> implements ISummaryZoomSectionCollection
```

Αναπαριστά μια συλλογή αντικειμένων Summary Zoom Section.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον συγκεκριμένο δείκτη. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | Δημιουργεί νέο αντικείμενο Summary Zoom Section και το προσθέτει στη συλλογή |
| [size()](#size--) | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται στην συλλογή. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | Επιστρέφει ένα δείκτη του καθορισμένου αντικειμένου SummaryZoomSection. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | Αφαιρεί το αντικείμενο Summary Zoom Section από τη συλλογή. |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | Επιστρέφει το στοιχείο Summary Zoom Section για το δεδομένο τμήμα. |
| [clear()](#clear--) | Αφαιρεί όλα τα αντικείμενα SummaryZoomSection από τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει ολόκληρη τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που δείχνει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν αριθμητή που διασχίζει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public final ISummaryZoomSection get_Item(int index)
```

Λαμβάνει το στοιχείο στον συγκεκριμένο δείκτη. Μόνο ανάγνωση [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

--------------------

> ```
> Το παράδειγμα δείχνει πώς να παίρνετε το στοιχείο Summary Zoom Section με βάση το δείκτη:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection zoomSection = collection.get_Item(1);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**  
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection addSummaryZoomSection(ISection section)
```

Δημιουργεί νέο αντικείμενο Summary Zoom Section και το προσθέτει στη συλλογή

--------------------

> ```
> Το παράδειγμα δείχνει πώς να παίρνετε το στοιχείο Summary Zoom Section με βάση το δείκτη:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection newZoomSection = collection.addSummaryZoomSection(pres.getSections().get_Item(3));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Τμήμα για ένα νέο στοιχείο Summary Zoom Section [ISection](../../com.aspose.slides/isection) |

Εάν υπάρχει ήδη στοιχείο για αυτό το τμήμα στη συλλογή, επιστρέφεται το υπάρχον στοιχείο.

**Επιστρέφει:**  
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - Προστέθηκε [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) στοιχείο
### size() {#size--}
```
public final int size()
```

Λαμβάνει τον αριθμό των στοιχείων που περιέχονται στην συλλογή. Μόνο ανάγνωση int.

**Επιστρέφει:**  
int
### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public final int indexOf(ISummaryZoomSection summaryZoomSection)
```

Επιστρέφει ένα δείκτη του καθορισμένου αντικειμένου SummaryZoomSection.

--------------------

> ```
> Το παράδειγμα δείχνει πώς να παίρνετε το στοιχείο Summary Zoom Section με βάση το δείκτη:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>       int idx = collection.indexOf(selectedObject);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | Αντικείμενο SummaryZoomSection για εύρεση [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**Επιστρέφει:**  
int - Δείκτης αντικειμένου SummaryZoomSection ή -1 εάν το αντικείμενο SummaryZoomSection δεν ανήκει σε αυτή τη συλλογή.
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public final void removeSummaryZoomSection(ISection section)
```

Αφαιρεί το αντικείμενο Summary Zoom Section από τη συλλογή.

--------------------

> ```
> Το παράδειγμα δείχνει πώς να παίρνετε το στοιχείο Summary Zoom Section με βάση το δείκτη:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.removeSummaryZoomSection(pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Τμήμα για το οποίο θα αφαιρεθεί το στοιχείο Summary Zoom Section [ISection](../../com.aspose.slides/isection). |

### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection getSummarySection(ISection section)
```

Επιστρέφει το στοιχείο Summary Zoom Section για το δεδομένο τμήμα.

--------------------

> ```
> Το παράδειγμα δείχνει πώς να παίρνετε το στοιχείο Summary Zoom Section με βάση το δείκτη:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Τμήμα για εύρεση [ISection](../../com.aspose.slides/isection) |

**Επιστρέφει:**  
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) ή null εάν η συλλογή δεν περιέχει στοιχείο για το τμήμα.
### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλα τα αντικείμενα SummaryZoomSection από τη συλλογή.

--------------------

> ```
> Το παράδειγμα δείχνει πώς να παίρνετε το στοιχείο Summary Zoom Section με βάση το δείκτη:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.clear();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει ολόκληρη τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας προορισμού |
| index | int | Δείκτης στον πίνακα προορισμού. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που δείχνει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο ανάγνωση boolean.

**Επιστρέφει:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει τη ρίζα συγχρονισμού. Μόνο ανάγνωση Object.

**Επιστρέφει:**  
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iterator()
```

Επιστρέφει έναν αριθμητή που διασχίζει τη συλλογή.

**Επιστρέφει:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την διαπέραση της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.