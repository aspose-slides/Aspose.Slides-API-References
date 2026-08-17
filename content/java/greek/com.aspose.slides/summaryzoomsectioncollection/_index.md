---
title: SummaryZoomSectionCollection
second_title: Aspose.Slides για Java - Αναφορά API
description: Αναπαριστά μια συλλογή αντικειμένων Summary Zoom Section.
type: docs
url: /el/com.aspose.slides/summaryzoomsectioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
```
public final class SummaryZoomSectionCollection extends DomObject<SummaryZoomFrame> implements ISummaryZoomSectionCollection
```

Αναπαριστά μια συλλογή αντικειμένων Summary Zoom Section.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | Δημιουργεί νέο αντικείμενο Summary Zoom Section και το προσθέτει στη συλλογή |
| [size()](#size--) | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | Επιστρέφει έναν δείκτη του καθορισμένου αντικειμένου SummaryZoomSection. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | Αφαιρεί το αντικείμενο Summary Zoom Section από τη συλλογή. |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | Επιστρέφει το στοιχείο Summary Zoom Section για την δεδομένη ενότητα. |
| [clear()](#clear--) | Αφαιρεί όλα τα αντικείμενα SummaryZoomSection από τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει ολόκληρη τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν επαναλήπτη που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public final ISummaryZoomSection get_Item(int index)
```

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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
> The example demonstrates getting Summary Zoom Section element by index:
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
| section | [ISection](../../com.aspose.slides/isection) | Ενότητα για ένα νέο στοιχείο Summary Zoom Section [ISection](../../com.aspose.slides/isection) |

Εάν ένα στοιχείο για αυτήν την ενότητα υπάρχει ήδη στη συλλογή, το υπάρχον στοιχείο επιστρέφεται.

**Επιστρέφει:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - Προστέθηκε [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) στοιχείο
### size() {#size--}
```
public final int size()
```

Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public final int indexOf(ISummaryZoomSection summaryZoomSection)
```

Επιστρέφει έναν δείκτη του καθορισμένου αντικειμένου SummaryZoomSection.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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
int - Δείκτης ενός αντικειμένου SummaryZoomSection ή -1 αν το αντικείμενο SummaryZoomSection δεν προέρχεται από αυτήν τη συλλογή.
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public final void removeSummaryZoomSection(ISection section)
```

Αφαιρεί το αντικείμενο Summary Zoom Section από τη συλλογή.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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
| section | [ISection](../../com.aspose.slides/isection) | Ενότητα για την οποία πρέπει να αφαιρεθεί το στοιχείο Summary Zoom Section [ISection](../../com.aspose.slides/isection). |

### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection getSummarySection(ISection section)
```

Επιστρέφει το στοιχείο Summary Zoom Section για την δεδομένη ενότητα.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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
| section | [ISection](../../com.aspose.slides/isection) | Ενότητα για εύρεση [ISection](../../com.aspose.slides/isection) |

**Επιστρέφει:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) ή null αν η συλλογή δεν περιέχει στοιχείο για την ενότητα.
### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλα τα αντικείμενα SummaryZoomSection από τη συλλογή.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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

Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει μια ριζική τιμή συγχρονισμού. Μόνο για ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iterator()
```

Επιστρέφει έναν επαναλήπτη που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.