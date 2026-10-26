---
title: ILayoutSlide
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αναπαριστά μια διαφάνεια διάταξης.
type: docs
url: /el/com.aspose.slides/ilayoutslide/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Αναπαριστά μια διαφάνεια διάταξης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας διάταξης. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Επιστρέφει τον διαχειριστή placeholder της διαφάνειας διάταξης. |
| [getMasterSlide()](#getMasterSlide--) | Επιστρέφει ή ορίζει τη master slide για μια διάταξη. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Επιστρέφει ή ορίζει τη master slide για μια διάταξη. |
| [getLayoutType()](#getLayoutType--) | Επιστρέφει τον τύπο διάταξης αυτής της διαφάνειας διάταξης. |
| [hasDependingSlides()](#hasDependingSlides--) | Επιστρέφει true αν υπάρχει τουλάχιστον μία διαφάνεια που εξαρτάται από αυτή τη διαφάνεια διάταξης. |
| [getDependingSlides()](#getDependingSlides--) | Επιστρέφει έναν πίνακα με όλες τις διαφάνειες, που εξαρτώνται από αυτή τη διαφάνεια διάταξης. |
| [remove()](#remove--) | Αφαιρεί τη διάταξη από την παρουσίαση. |
| [getDrawingGuides()](#getDrawingGuides--) | Επιστρέφει μια συλλογή από drawing guides για τη διαφάνεια διάταξης. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας διάταξης. Μόνο για ανάγνωση [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Επιστρέφει:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

Επιστρέφει τον διαχειριστή placeholder της διαφάνειας διάταξης. Μόνο για ανάγνωση [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Επιστρέφει:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

Επιστρέφει ή ορίζει τη master slide για μια διάταξη. Ανάγνωση/εγγραφή [IMasterSlide](../../com.aspose.slides/imasterslide).

**Επιστρέφει:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

Επιστρέφει ή ορίζει τη master slide για μια διάταξη. Ανάγνωση/εγγραφή [IMasterSlide](../../com.aspose.slides/imasterslide).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

Επιστρέφει τον τύπο διάταξης αυτής της διαφάνειας διάταξης. Μόνο για ανάγνωση [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Επιστρέφει:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Επιστρέφει true αν υπάρχει τουλάχιστον μία διαφάνεια που εξαρτάται από αυτή τη διαφάνεια διάταξης. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Επιστρέφει έναν πίνακα με όλες τις διαφάνειες, που εξαρτώνται από αυτή τη διαφάνεια διάταξης.

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Πίνακας με όλες τις διαφάνειες, που εξαρτώνται από αυτή τη διαφάνεια διάταξης
### remove() {#remove--}
```
public abstract void remove()
```

Αφαιρεί τη διάταξη από την παρουσίαση.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Επιστρέφει μια συλλογή από drawing guides για τη διαφάνεια διάταξης. Μόνο για ανάγνωση [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Προσθήκη της νέας κάθετης οδηγού σχεδίασης στα αριστερά του κέντρου της διαφάνειας
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)