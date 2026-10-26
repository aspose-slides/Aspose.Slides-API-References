---
title: NotesSlide
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά μια διαφάνεια σημειώσεων σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/notesslide/
---
**Κληρονομία:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Αναπαριστά μια διαφάνεια σημειώσεων σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει το διαχειριστή HeaderFooter της διαφάνειας σημειώσεων. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Επιστρέφει ένα TextFrame με το κείμενο των σημειώσεων αν υπάρχει. |
| [getThemeManager()](#getThemeManager--) | Επιστρέφει τον διαχειριστή θέματος που αντικαθιστά. |
| [getParentSlide()](#getParentSlide--) | Επιστρέφει τη γονική διαφάνεια. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Καθορίζει αν τα σχήματα στη διαφάνεια master πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Καθορίζει αν τα σχήματα στη διαφάνεια master πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Επιστρέφει το διαχειριστή HeaderFooter της διαφάνειας σημειώσεων. Μόνο για ανάγνωση [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Επιστρέφει:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

Επιστρέφει ένα TextFrame με το κείμενο των σημειώσεων αν υπάρχει. Μόνο για ανάγνωση [ITextFrame](../../com.aspose.slides/itextframe).

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Επιστρέφει τον διαχειριστή θέματος που αντικαθιστά. Μόνο για ανάγνωση [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Επιστρέφει:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

Επιστρέφει τη γονική διαφάνεια. Μόνο για ανάγνωση [ISlide](../../com.aspose.slides/islide).

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Καθορίζει αν τα σχήματα στη διαφάνεια master πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Καθορίζει αν τα σχήματα στη διαφάνεια master πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |