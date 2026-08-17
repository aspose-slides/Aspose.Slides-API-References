---
title: ISummaryZoomSectionCollection
second_title: Aspose.Slides για Java API Αναφορά
description: Αναπαριστά μια συλλογή από αντικείμενα Summary Zoom Section.
type: docs
url: /el/com.aspose.slides/isummaryzoomsectioncollection/
---
**All Implemented Interfaces:**  
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

Αναπαριστά μια συλλογή από αντικείμενα Summary Zoom Section.

## Μεθοδοί

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | Δημιουργεί νέο αντικείμενο Summary Zoom Section και το προσθέτει στη συλλογή |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | Επιστρέφει το στοιχείο Summary Zoom Section για την δεδομένη ενότητα. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | Αφαιρεί το αντικείμενο Summary Zoom Section από τη συλλογή. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | Επιστρέφει έναν δείκτη του συγκεκριμένου αντικειμένου SummaryZoomSection. |
| [clear()](#clear--) | Αφαιρεί όλα τα αντικείμενα SummaryZoomSection από τη συλλογή. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

--------------------

> ```
> Το παράδειγμα δείχνει την ανάκτηση του στοιχείου Summary Zoom Section με βάση το δείκτη:
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
| Παράμετρος | Type | Description |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)

### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```

Δημιουργεί νέο αντικείμενο Summary Zoom Section και το προσθέτει στη συλλογή

--------------------

> ```
> Το παράδειγμα δείχνει την ανάκτηση του στοιχείου Summary Zoom Section με βάση το δείκτη:
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
| Παράμετρος | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Τμήμα για νέο στοιχείο Summary Zoom Section [ISection](../../com.aspose.slides/isection) |

Εάν υπάρχει ήδη στοιχείο για αυτό το τμήμα στη συλλογή, επιστρέφεται το υπάρχον στοιχείο.

**Επιστρέφει:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - Προστέθηκε [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) στοιχείο

### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```

Επιστρέφει το στοιχείο Summary Zoom Section για την δεδομένη ενότητα.

--------------------

> ```
> Το παράδειγμα δείχνει την ανάκτηση του στοιχείου Summary Zoom Section με βάση το δείκτη:
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
| Παράμετρος | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Τμήμα προς εύρεση [ISection](../../com.aspose.slides/isection) |

**Επιστρέφει:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) ή null εάν η συλλογή δεν περιέχει στοιχείο για το τμήμα.

### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
```

Αφαιρεί το αντικείμενο Summary Zoom Section από τη συλλογή.

--------------------

> ```
> Το παράδειγμα δείχνει την ανάκτηση του στοιχείου Summary Zoom Section με βάση το δείκτη:
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
| Παράμετρος | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Τμήμα για το οποίο το στοιχείο Summary Zoom Section πρέπει να αφαιρεθεί [ISection](../../com.aspose.slides/isection). |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```

Επιστρέφει έναν δείκτη του συγκεκριμένου αντικειμένου SummaryZoomSection.

--------------------

> ```
> Το παράδειγμα δείχνει την ανάκτηση του στοιχείου Summary Zoom Section με βάση το δείκτη:
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
| Παράμετρος | Type | Description |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | Αντικείμενο SummaryZoomSection προς εύρεση [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**Επιστρέφει:**
int - Δείκτης ενός αντικειμένου SummaryZoomSection ή -1 εάν το αντικείμενο SummaryZoomSection δεν προέρχεται από αυτή τη συλλογή.

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλα τα αντικείμενα SummaryZoomSection από τη συλλογή.

--------------------

> ```
> Το παράδειγμα δείχνει την ανάκτηση του στοιχείου Summary Zoom Section με βάση το δείκτη:
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