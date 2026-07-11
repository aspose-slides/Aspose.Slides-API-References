---
title: ISummaryZoomSectionCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει μια συλλογή αντικειμένων Summary Zoom Section.
type: docs
url: /el/com.aspose.slides/isummaryzoomsectioncollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

Αντιπροσωπεύει μια συλλογή αντικειμένων Summary Zoom Section.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Αποκτά το στοιχείο στον καθορισμένο δείκτη. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | Δημιουργεί νέο αντικείμενο Summary Zoom Section και το προσθέτει στη συλλογή |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | Επιστρέφει το στοιχείο Summary Zoom Section για το δεδομένο τμήμα. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | Αφαιρεί το αντικείμενο Summary Zoom Section από τη συλλογή. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | Επιστρέφει έναν δείκτη του συγκεκριμένου αντικειμένου SummaryZoomSection. |
| [clear()](#clear--) | Αφαιρεί όλα τα αντικείμενα SummaryZoomSection από τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```

Αποκτά το στοιχείο στον καθορισμένο δείκτη. Μόνο-ανάγνωση [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

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
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
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
| section | [ISection](../../com.aspose.slides/isection) | Τμήμα για ένα νέο στοιχείο Summary Zoom Section [ISection](../../com.aspose.slides/isection)

If an element for this section already exists in the collection, the existing element is returned. |
**Επιστρέφει:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - Προστέθηκε το στοιχείο [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```

Επιστρέφει το στοιχείο Summary Zoom Section για το δοσμένο τμήμα.

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
| section | [ISection](../../com.aspose.slides/isection) | Τμήμα προς εύρεση [ISection](../../com.aspose.slides/isection) |

**Επιστρέφει:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) ή null αν η συλλογή δεν περιέχει στοιχείο για το τμήμα.
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
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
| section | [ISection](../../com.aspose.slides/isection) | Τμήμα για το οποίο το στοιχείο Summary Zoom Section πρέπει να αφαιρεθεί [ISection](../../com.aspose.slides/isection). |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```

Επιστρέφει έναν δείκτη του συγκεκριμένου αντικειμένου SummaryZoomSection.

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
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | Αντικείμενο SummaryZoomSection προς εύρεση [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**Επιστρέφει:**
int - Δείκτης ενός αντικειμένου SummaryZoomSection ή -1 αν το αντικείμενο SummaryZoomSection δεν προέρχεται από αυτή τη συλλογή.
### clear() {#clear--}
```
public abstract void clear()
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