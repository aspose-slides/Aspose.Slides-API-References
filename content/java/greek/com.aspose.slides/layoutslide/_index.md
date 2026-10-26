---
title: LayoutSlide
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά μια διαφάνεια διάταξης.
type: docs
url: /el/com.aspose.slides/layoutslide/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Αναπαριστά μια διαφάνεια διάταξης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας διάταξης. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Επιστρέφει τον διαχειριστή placeholder της διαφάνειας διάταξης. |
| [getMasterSlide()](#getMasterSlide--) | Επιστρέφει ή ορίζει τη διαφάνεια master για μια διάταξη. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Επιστρέφει ή ορίζει τη διαφάνεια master για μια διάταξη. |
| [remove()](#remove--) | Αφαιρεί τη διάταξη από την παρουσίαση. |
| [getThemeManager()](#getThemeManager--) | Επιστρέφει τον διαχειριστή theme που υπερισχύει. |
| [getLayoutType()](#getLayoutType--) | Επιστρέφει τον τύπο διάταξης αυτής της διαφάνειας διάταξης. |
| [getDependingSlides()](#getDependingSlides--) | Επιστρέφει έναν πίνακα με όλες τις διαφάνειες που εξαρτώνται από αυτήν τη διαφάνεια διάταξης. |
| [hasDependingSlides()](#hasDependingSlides--) | Επιστρέφει true εάν υπάρχει τουλάχιστον μία διαφάνεια που εξαρτάται από αυτήν τη διαφάνεια διάταξης. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Καθορίζει αν τα σχήματα στη διαφάνεια master πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Καθορίζει αν τα σχήματα στη διαφάνεια master πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [getDrawingGuides()](#getDrawingGuides--) | Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη διαφάνεια διάταξης. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας διάταξης. Μόνο ανάγνωση [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Επιστρέφει:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```


Επιστρέφει τον διαχειριστή placeholder της διαφάνειας διάταξης. Μόνο ανάγνωση [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Επιστρέφει:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```


Επιστρέφει ή ορίζει τη διαφάνεια master για μια διάταξη. Ανάγνωση/εγγραφή [IMasterSlide](../../com.aspose.slides/imasterslide).

**Επιστρέφει:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```


Επιστρέφει ή ορίζει τη διαφάνεια master για μια διάταξη. Ανάγνωση/εγγραφή [IMasterSlide](../../com.aspose.slides/imasterslide).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### remove() {#remove--}
```
public final void remove()
```


Αφαιρεί τη διάταξη από την παρουσίαση.

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Επιστρέφει τον διαχειριστή theme που υπερισχύει. Μόνο ανάγνωση [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Επιστρέφει:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```


Επιστρέφει τον τύπο διάταξης αυτής της διαφάνειας διάταξης. Μόνο ανάγνωση [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Επιστρέφει:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


Επιστρέφει έναν πίνακα με όλες τις διαφάνειες που εξαρτώνται από αυτήν τη διαφάνεια διάταξης.

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Πίνακας των [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


Επιστρέφει true εάν υπάρχει τουλάχιστον μία διαφάνεια που εξαρτάται από αυτήν τη διαφάνεια διάταξης. Μόνο ανάγνωση  boolean .

**Επιστρέφει:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Καθορίζει αν τα σχήματα στην διαφάνεια master πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Ανάγνωση/εγγραφή  boolean .

**Επιστρέφει:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Καθορίζει αν τα σχήματα στην διαφάνεια master πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Ανάγνωση/εγγραφή  boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη διαφάνεια διάταξης. Μόνο ανάγνωση [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Προσθήκη του νέου κατακόρυφου οδηγού σχεδίασης στα αριστερά του κέντρου της διαφάνειας
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)