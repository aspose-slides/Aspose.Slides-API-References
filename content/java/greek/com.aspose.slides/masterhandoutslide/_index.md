---
title: MasterHandoutSlide
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει τη διαφάνεια master για φυλλάδια.
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

Αντιπροσωπεύει τη διαφάνεια master για φυλλάδια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Καθορίζει εάν τα σχήματα στη διαφάνεια master πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Καθορίζει εάν τα σχήματα στη διαφάνεια master πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει τον διαχειριστή HeaderFooter της κύριας διαφάνειας φυλλάδιο. |
| [getThemeManager()](#getThemeManager--) | Επιστρέφει τον διαχειριστή θεμάτων. |
| [getDrawingGuides()](#getDrawingGuides--) | Επιστρέφει μια συλλογή από οδηγίες σχεδίασης για τη διαφάνεια master του φυλλαδίου. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Καθορίζει εάν τα σχήματα στη διαφάνεια master πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Για τη διαφάνεια master αυτή η ιδιότητα επιστρέφει πάντα false. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Καθορίζει εάν τα σχήματα στη διαφάνεια master πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Για τη διαφάνεια master αυτή η ιδιότητα επιστρέφει πάντα false. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

Επιστρέφει τον διαχειριστή HeaderFooter της κύριας διαφάνειας φυλλάδιο. Μόνο για ανάγνωση [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Επιστρέφει:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Επιστρέφει τον διαχειριστή θεμάτων. Μόνο για ανάγνωση [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Επιστρέφει:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Επιστρέφει μια συλλογή από οδηγίες σχεδίασης για τη διαφάνεια master του φυλλαδίου. Μόνο για ανάγνωση [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Προσθήκη της νέας οριζόντιας οδηγίας σχεδίασης πάνω από το κέντρο της διαφάνειας
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)