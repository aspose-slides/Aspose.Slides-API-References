---
title: MasterNotesSlide
second_title: Αναφορά API για Aspose.Slides για Java
description: Αναπαριστά την κύρια διαφάνεια για σημειώσεις.
type: docs
url: /el/com.aspose.slides/masternotesslide/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

Αντιπροσωπεύει τη κύρια διαφάνεια για σημειώσεις.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Καθορίζει αν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Καθορίζει αν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει τον διαχειριστή HeaderFooter της κύριας διαφάνειας σημειώσεων. |
| [getThemeManager()](#getThemeManager--) | Επιστρέφει τον διαχειριστή θέματος. |
| [getNotesStyle()](#getNotesStyle--) | Επιστρέφει το στυλ ενός κειμένου σημειώσεων. |
| [getDrawingGuides()](#getDrawingGuides--) | Επιστρέφει μια συλλογή από οδηγίες σχεδίασης για την κύρια διαφάνεια σημειώσεων. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Καθορίζει αν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Για την ίδια τη κύρια διαφάνεια αυτή η ιδιότητα επιστρέφει πάντα false. **Ανάγνωση/εγγραφή boolean.**

**Επιστρέφει:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Καθορίζει αν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Για την ίδια τη κύρια διαφάνεια αυτή η ιδιότητα επιστρέφει πάντα false. **Ανάγνωση/εγγραφή boolean.**

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Επιστρέφει τον διαχειριστή HeaderFooter της κύριας διαφάνειας σημειώσεων. **Μόνο ανάγνωση** [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Επιστρέφει:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Επιστρέφει τον διαχειριστή θέματος. **Μόνο ανάγνωση** [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Επιστρέφει:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

Επιστρέφει το στυλ ενός κειμένου σημειώσεων. **Μόνο ανάγνωση** [ITextStyle](../../com.aspose.slides/itextstyle).

**Επιστρέφει:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Επιστρέφει μια συλλογή από οδηγίες σχεδίασης για την κύρια διαφάνεια σημειώσεων. **Μόνο ανάγνωση** [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Προσθήκη της νέας οριζόντιας οδηγίας σχεδίασης κάτω από το κέντρο της διαφάνειας
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)