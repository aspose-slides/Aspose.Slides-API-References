---
title: INotesSlide
second_title: Aspose.Slides για Java API Αναφορά
description: Αντιπροσωπεύει μια διαφάνεια σημειώσεων σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/inotesslide/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Αντιπροσωπεύει μια διαφάνεια σημειώσεων σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας σημειώσεων. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Επιστρέφει ένα TextFrame με το κείμενο των σημειώσεων εάν υπάρχει. |
| [getParentSlide()](#getParentSlide--) | Επιστρέφει ένα ParentSlide Μόνο για ανάγνωση [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας σημειώσεων. Μόνο για ανάγνωση [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Επιστρέφει:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

Επιστρέφει ένα TextFrame με το κείμενο των σημειώσεων εάν υπάρχει. Μόνο για ανάγνωση [ITextFrame](../../com.aspose.slides/itextframe).

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

Επιστρέφει ένα ParentSlide Μόνο για ανάγνωση [ISlide](../../com.aspose.slides/islide).

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide)