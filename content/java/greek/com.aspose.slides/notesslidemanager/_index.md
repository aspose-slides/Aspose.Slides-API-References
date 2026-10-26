---
title: NotesSlideManager
second_title: Αναφορά API του Aspose.Slides για Java
description: Διαχειριστής διαφάνειας σημειώσεων.
type: docs
url: /el/com.aspose.slides/notesslidemanager/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Διαχειριστής διαφάνειας σημειώσεων.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Δημιουργήστε ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Προσθέστε σημειώσεις στην πρώτη διαφάνεια
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // Αποθηκεύστε την παρουσίαση στο δίσκο
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Δημιουργήστε ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Αφαίρεση σημειώσεων της πρώτης διαφάνειας
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Αποθηκεύστε την παρουσίαση στο δίσκο
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Επιστρέφει τη διαφάνεια σημειώσεων για την τρέχουσα διαφάνεια. |
| [addNotesSlide()](#addNotesSlide--) | Επιστρέφει τη διαφάνεια σημειώσεων για την τρέχουσα διαφάνεια, δημιουργώντας τη εάν δεν υπάρχει. |
| [removeNotesSlide()](#removeNotesSlide--) | Αφαιρεί τη διαφάνεια σημειώσεων της τρέχουσας διαφάνειας. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```

Επιστρέφει τη διαφάνεια σημειώσεων για την τρέχουσα διαφάνεια. Επιστρέφει null εάν η διαφάνεια δεν έχει διαφάνεια σημειώσεων. Μόνο για ανάγνωση [INotesSlide](../../com.aspose.slides/inotesslide).

**Επιστρέφει:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```

Επιστρέφει τη διαφάνεια σημειώσεων για την τρέχουσα διαφάνεια, δημιουργώντας τη εάν δεν υπάρχει.

**Επιστρέφει:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) για αυτή τη διαφάνεια.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```

Αφαιρεί τη διαφάνεια σημειώσεων της τρέχουσας διαφάνειας.