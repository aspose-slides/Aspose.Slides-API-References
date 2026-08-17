---
title: IMasterHandoutSlide
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει τη κύρια διαφάνεια για φυλλάδια.
type: docs
url: /el/com.aspose.slides/imasterhandoutslide/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

Αντιπροσωπεύει τη κύρια διαφάνεια για φυλλάδια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει τον διαχειριστή HeaderFooter της κύριας διαφάνειας για φυλλάδια. |
| [getDrawingGuides()](#getDrawingGuides--) | Επιστρέφει μια συλλογή από οδηγίες σχεδίασης για τη κύρια διαφάνεια για φυλλάδια. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


Επιστρέφει τον διαχειριστή HeaderFooter της κύριας διαφάνειας για φυλλάδια. Μόνο για ανάγνωση [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Επιστρέφει:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Επιστρέφει μια συλλογή από οδηγίες σχεδίασης για τη κύρια διαφάνεια για φυλλάδια. Μόνο για ανάγνωση [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
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