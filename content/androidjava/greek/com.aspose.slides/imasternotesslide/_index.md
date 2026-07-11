---
title: IMasterNotesSlide
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει τη κύρια διαφάνεια για σημειώσεις.
type: docs
url: /el/com.aspose.slides/imasternotesslide/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

Αντιπροσωπεύει τη κύρια διαφάνεια για σημειώσεις.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει τον διαχειριστή HeaderFooter της κύριας διαφάνειας σημειώσεων. |
| [getNotesStyle()](#getNotesStyle--) | Επιστρέφει το στιλ ενός κειμένου σημειώσεων. |
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


Επιστρέφει το στιλ ενός κειμένου σημειώσεων. Μόνο για ανάγνωση [ITextStyle](../../com.aspose.slides/itextstyle).

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
>      SizeF notesSize = pres.getNotesSize().getSize();
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