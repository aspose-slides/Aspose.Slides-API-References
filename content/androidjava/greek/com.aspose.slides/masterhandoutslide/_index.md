---
title: MasterHandoutSlide
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει την κύρια διαφάνεια για φυλλάδια.
type: docs
url: /el/com.aspose.slides/masterhandoutslide/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

Αντιπροσωπεύει την κύρια διαφάνεια για φυλλάδια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Καθορίζει αν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Καθορίζει αν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει το διαχειριστή HeaderFooter της κύριας διαφάνειας φυλλαδίου. |
| [getThemeManager()](#getThemeManager--) | Επιστρέφει το διαχειριστή θέματος. |
| [getDrawingGuides()](#getDrawingGuides--) | Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για την κύρια διαφάνεια φυλλαδίου. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Καθορίζει αν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Για τη ίδια τη κύρια διαφάνεια αυτή η ιδιότητα επιστρέφει πάντα false. Αναγνώσιμο/εγγράψιμο boolean.

**Επιστρέφει:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Καθορίζει αν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Για τη ίδια τη κύρια διαφάνεια αυτή η ιδιότητα επιστρέφει πάντα false. Αναγνώσιμο/εγγράψιμο boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

Επιστρέφει το διαχειριστή HeaderFooter της κύριας διαφάνειας φυλλαδίου. Μόνο για ανάγνωση [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Επιστρέφει:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Επιστρέφει το διαχειριστή θέματος. Μόνο για ανάγνωση [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Επιστρέφει:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για την κύρια διαφάνεια φυλλαδίου. Μόνο για ανάγνωση [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Προσθήκη του νέου οριζόντιου οδηγού σχεδίασης πάνω από το κέντρο της διαφάνειας
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)