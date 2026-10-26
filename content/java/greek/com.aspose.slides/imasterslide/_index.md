---
title: IMasterSlide
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά μια κύρια διαφάνεια σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/imasterslide/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Αναπαριστά μια κύρια διαφάνεια σε μια παρουσίαση.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει τον διαχειριστή HeaderFooter της κύριας διαφάνειας. |
| [getTitleStyle()](#getTitleStyle--) | Επιστρέφει το στυλ ενός κειμένου τίτλου. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Δημιουργεί μια νέα κύρια διαφάνεια βασισμένη στην τρέχουσα, εφαρμόζει εξωτερικό θέμα σε αυτήν και εφαρμόζει τη δημιουργημένη κύρια διαφάνεια σε όλες τις εξαρτημένες διαφάνειες. |
| [getBodyStyle()](#getBodyStyle--) | Επιστρέφει το στυλ ενός κυρίως κειμένου. |
| [getOtherStyle()](#getOtherStyle--) | Επιστρέφει το στυλ ενός άλλου κειμένου. |
| [getLayoutSlides()](#getLayoutSlides--) | Επιστρέφει τη συλλογή των παιδικών διαφανειών διάταξης για αυτήν την κύρια διαφάνεια. |
| [getPreserve()](#getPreserve--) | Καθορίζει εάν η αντίστοιχη κύρια διαφάνεια διαγράφεται όταν όλες οι διαφάνειες που την ακολουθούν διαγράφονται. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Καθορίζει εάν η αντίστοιχη κύρια διαφάνεια διαγράφεται όταν όλες οι διαφάνειες που την ακολουθούν διαγράφονται. |
| [hasDependingSlides()](#hasDependingSlides--) | Επιστρέφει true εάν υπάρχει τουλάχιστο μία διαφάνεια που εξαρτάται από αυτήν την κύρια διαφάνεια. |
| [getDependingSlides()](#getDependingSlides--) | Επιστρέφει έναν πίνακα με όλες τις διαφάνειες που εξαρτώνται από αυτήν την κύρια διαφάνεια. |
| [getDrawingGuides()](#getDrawingGuides--) | Επιστρέφει μια συλλογή από οδηγίες σχεδίασης για την κύρια διαφάνεια. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Επιστρέφει τον διαχειριστή HeaderFooter της κύριας διαφάνειας. Μόνο για ανάγνωση [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Επιστρέφει:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

Επιστρέφει το στυλ ενός κειμένου τίτλου. Μόνο για ανάγνωση [ITextStyle](../../com.aspose.slides/itextstyle).

**Επιστρέφει:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Δημιουργεί μια νέα κύρια διαφάνεια βασισμένη στην τρέχουσα, εφαρμόζει εξωτερικό θέμα σε αυτήν και εφαρμόζει τη δημιουργημένη κύρια διαφάνεια σε όλες τις εξαρτημένες διαφάνιες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | java.lang.String | Διαδρομή προς το αρχείο εξωτερικού θέματος (.thmx). |

**Επιστρέφει:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Νέα MasterSlide με θέμα.

### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

Επιστρέφει το στυλ ενός κυρίως κειμένου. Μόνο για ανάγνωση [ITextStyle](../../com.aspose.slides/itextstyle).

**Επιστρέφει:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

Επιστρέφει το στυλ ενός άλλου κειμένου. Μόνο για ανάγνωση [ITextStyle](../../com.aspose.slides/itextstyle).

**Επιστρέφει:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

Επιστρέφει τη συλλογή των παιδικών διαφανειών διάταξης για αυτήν την κύρια διαφάνεια. Μόνο για ανάγνωση [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Μπορείτε να έχετε πρόσβαση σε εναλλακτικό API για προσθήκη/εισαγωγή/αφαίρεση/κλωνοποίηση διαφανειών διάταξης χρησιμοποιώντας την ιδιότητα ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Επιστρέφει:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

Καθορίζει εάν η αντίστοιχη κύρια διαφάνεια διαγράφεται όταν όλες οι διαφάνειες που την ακολουθούν διαγράφονται. Σημείωση: το Aspose.Slides δεν θα αφαιρέσει ποτέ αυτόματα οποιαδήποτε αχρησιμοποίητη κύρια διαφάνεια· για να αφαιρέσετε πραγματικά τις αχρησιμοποίητες κύριες διαφάνειες, καλέστε [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

Καθορίζει εάν η αντίστοιχη κύρια διαφάνεια διαγράφεται όταν όλες οι διαφάνειες που την ακολουθούν διαγράφονται. Σημείωση: το Aspose.Slides δεν θα αφαιρέσει ποτέ αυτόματα οποιαδήποτε αχρησιμοποίητη κύρια διαφάνεια· για να αφαιρέσετε πραγματικά τις αχρησιμοποίητες κύριες διαφάνειες, καλέστε [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Επιστρέφει true εάν υπάρχει τουλάχιστο μία διαφάνεια που εξαρτάται από αυτήν την κύρια διαφάνεια. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Επιστρέφει έναν πίνακα με όλες τις διαφάνειες που εξαρτώνται από αυτήν την κύρια διαφάνεια.

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Πίνακας των [ISlide](../../com.aspose.slides/islide), που εξαρτώνται από αυτήν την κύρια διαφάνεια

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Επιστρέφει μια συλλογή από οδηγίες σχεδίασης για την κύρια διαφάνεια. Μόνο για ανάγνωση [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Προσθήκη της νέας κατακόρυφης οδηγίας σχεδίασης δεξιά του κέντρου της διαφάνειας
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)