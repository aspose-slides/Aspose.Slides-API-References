---
title: IMasterNotesSlide
second_title: Αναφορά API Aspose.Slides for Java
description: Αναπαριστά τη κύρια διαφάνεια σημειώσεων.
type: docs
url: /el/com.aspose.slides/imasternotesslide/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

Αναπαριστά τη κύρια διαφάνεια σημειώσεων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει τον διαχειριστή HeaderFooter της κύριας διαφάνειας σημειώσεων. |
| [getNotesStyle()](#getNotesStyle--) | Επιστρέφει το στυλ ενός κειμένου σημειώσεων. |
| [getDrawingGuides()](#getDrawingGuides--) | Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη κύρια διαφάνεια σημειώσεων. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


Επιστρέφει τον διαχειριστή HeaderFooter της κύριας διαφάνειας σημειώσεων. Μόνο για ανάγνωση [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**Επιστρέφει:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```


Επιστρέφει το στυλ ενός κειμένου σημειώσεων. Μόνο για ανάγνωση [ITextStyle](../../com.aspose.slides/itextstyle).

**Επιστρέφει:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη κύρια διαφάνεια σημειώσεων. Μόνο για ανάγνωση [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Προσθήκη του νέου οριζόντιου οδηγού σχεδίασης κάτω από το κέντρο της διαφάνειας
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)