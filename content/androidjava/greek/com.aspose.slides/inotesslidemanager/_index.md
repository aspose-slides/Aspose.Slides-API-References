---
title: INotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Διαχειριστής διαφάνειας σημειώσεων.
type: docs
url: /el/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Διαχειριστής διαφάνειας σημειώσεων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Επιστρέφει τη διαφάνεια σημειώσεων για την τρέχουσα διαφάνεια. |
| [addNotesSlide()](#addNotesSlide--) | Επιστρέφει τη διαφάνεια σημειώσεων για την τρέχουσα διαφάνεια, δημιουργώντας μία εάν δεν υπάρχει. |
| [removeNotesSlide()](#removeNotesSlide--) | Καταργεί τη διαφάνεια σημειώσεων της τρέχουσας διαφάνειας. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

Επιστρέφει τη διαφάνεια σημειώσεων για την τρέχουσα διαφάνεια. Επιστρέφει null εάν η διαφάνεια δεν έχει διαφάνεια σημειώσεων. Μόνο ανάγνωση [INotesSlide](../../com.aspose.slides/inotesslide).

**Επιστρέφει:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

Επιστρέφει τη διαφάνεια σημειώσεων για την τρέχουσα διαφάνεια, δημιουργώντας μία εάν δεν υπάρχει.

**Επιστρέφει:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) για αυτή τη διαφάνεια.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

Καταργεί τη διαφάνεια σημειώσεων της τρέχουσας διαφάνειας.