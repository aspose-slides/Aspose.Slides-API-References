---
title: IMasterSlide
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει μια κύρια διαφάνεια σε μια παρουσίαση.
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
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Δημιουργεί μια νέα κύρια διαφάνεια βασισμένη στην τρέχουσα, εφαρμόζοντας ένα εξωτερικό θέμα σε αυτήν και εφαρμόζει τη δημιουργημένη κύρια διαφάνεια σε όλες τις εξαρτώμενες διαφάνειες. |
| [getBodyStyle()](#getBodyStyle--) | Επιστρέφει το στυλ ενός κειμένου σώματος. |
| [getOtherStyle()](#getOtherStyle--) | Επιστρέφει το στυλ ενός άλλου κειμένου. |
| [getLayoutSlides()](#getLayoutSlides--) | Επιστρέφει τη συλλογή των παιδικών διαφανειών διάταξης για αυτήν την κύρια διαφάνεια. |
| [getPreserve()](#getPreserve--) | Καθορίζει αν ο αντίστοιχος κύριος διαγράφεται όταν όλες οι διαφάνειες που τον ακολουθούν διαγραφούν. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Καθορίζει αν ο αντίστοιχος κύριος διαγράφεται όταν όλες οι διαφάνειες που τον ακολουθούν διαγραφούν. |
| [hasDependingSlides()](#hasDependingSlides--) | Επιστρέφει true αν υπάρχει τουλάχιστον μία διαφάνεια που εξαρτάται από αυτήν την κύρια διαφάνεια. |
| [getDependingSlides()](#getDependingSlides--) | Επιστρέφει έναν πίνακα με όλες τις διαφάνειες που εξαρτώνται από αυτήν την κύρια διαφάνεια. |
| [getDrawingGuides()](#getDrawingGuides--) | Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για την κύρια διαφάνεια. |
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

Δημιουργεί μια νέα κύρια διαφάνεια βασισμένη στην τρέχουσα, εφαρμόζοντας ένα εξωτερικό θέμα σε αυτήν και εφαρμόζει τη δημιουργημένη κύρια διαφάνεια σε όλες τις εξαρτώμενες διαφάνειες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | java.lang.String | Διαδρομή στο εξωτερικό αρχείο θέματος (.thmx). |

**Επιστρέφει:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Νέα θεματική MasterSlide.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

Επιστρέφει το στυλ ενός κειμένου σώματος. Μόνο για ανάγνωση [ITextStyle](../../com.aspose.slides/itextstyle).

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

Μπορείτε να προσπελάσετε εναλλακτικό API για προσθήκη/εισαγωγή/αφαίρεση/κλωνοποίηση διαφανειών διάταξης χρησιμοποιώντας την ιδιότητα ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Επιστρέφει:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

Καθορίζει αν ο αντίστοιχος κύριος διαγράφεται όταν όλες οι διαφάνειες που τον ακολουθούν διαγραφούν. Σημείωση: το Aspose.Slides δεν θα αφαιρέσει ποτέ αυτόματα κάποιον αχρησιμοποίητο κύριο· για να αφαιρέσετε πραγματικά αχρησιμοποίητους κύριους καλέστε [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-). Αναγνώσιμη/εγγράψιμη boolean.

**Επιστρέφει:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

Καθορίζει αν ο αντίστοιχος κύριος διαγράφεται όταν όλες οι διαφάνειες που τον ακολουθούν διαγραφούν. Σημείωση: το Aspose.Slides δεν θα αφαιρέσει ποτέ αυτόματα κάποιον αχρησιμοποίητο κύριο· για να αφαιρέσετε πραγματικά αχρησιμοποίητους κύριους καλέστε [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-). Αναγνώσιμη/εγγράψιμη boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Επιστρέφει true αν υπάρχει τουλάχιστον μία διαφάνεια που εξαρτάται από αυτήν την κύρια διαφάνεια. Μόνο για ανάγνωση boolean.

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

Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για την κύρια διαφάνεια. Μόνο για ανάγνωση [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Προσθήκη του νέου κάθετου οδηγού σχεδίασης δεξιά από το κέντρο της διαφάνειας
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)