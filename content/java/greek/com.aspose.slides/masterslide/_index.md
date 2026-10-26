---
title: MasterSlide
second_title: Aspose.Slides για την Java API Αναφορά
description: Αναπαριστά μια κύρια διαφάνεια σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/masterslide/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Αντιπροσωπεί μια κύρια διαφάνεια σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει τον διαχειριστή HeaderFooter της κύριας διαφάνειας. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Δημιουργεί μια νέα κύρια διαφάνεια βασισμένη στην τρέχουσα, εφαρμόζοντας ένα εξωτερικό θέμα σε αυτήν και εφαρμόζει τη δημιουργημένη κύρια διαφάνεια σε όλες τις εξαρτημένες διαφάνειες. |
| [getTitleStyle()](#getTitleStyle--) | Επιστρέφει το στυλ του κειμένου τίτλου. |
| [getBodyStyle()](#getBodyStyle--) | Επιστρέφει το στυλ του κειμένου σώματος. |
| [getOtherStyle()](#getOtherStyle--) | Επιστρέφει το στυλ άλλου κειμένου. |
| [getLayoutSlides()](#getLayoutSlides--) | Επιστρέφει τη συλλογή των θυγατρικών διαφανειών διάταξης για αυτήν την κύρια διαφάνεια. |
| [getPreserve()](#getPreserve--) | Καθορίζει εάν η αντίστοιχη κύρια διαφάνεια διαγράφεται όταν διαγραφούν όλες οι διαφάνειες που ακολουθούν αυτήν. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Καθορίζει εάν η αντίστοιχη κύρια διαφάνεια διαγράφεται όταν διαγραφούν όλες οι διαφάνειες που ακολουθούν αυτήν. |
| [getDependingSlides()](#getDependingSlides--) | Επιστρέφει έναν πίνακα με όλες τις διαφάνειες που εξαρτώνται από αυτήν την κύρια διαφάνεια. |
| [hasDependingSlides()](#hasDependingSlides--) | Επιστρέφει true εάν υπάρχει τουλάχιστον μία διαφάνεια που εξαρτάται από αυτήν την κύρια διαφάνεια. |
| [getThemeManager()](#getThemeManager--) | Επιστρέφει τον διαχειριστή θέματος. |
| [getName()](#getName--) | Επιστρέφει ή ορίζει το όνομα μιας κύριας διαφάνειας. |
| [setName(String value)](#setName-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα μιας κύριας διαφάνειας. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Καθορίζει εάν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Καθορίζει εάν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [getDrawingGuides()](#getDrawingGuides--) | Επιστρέφει μια συλλογή οδηγών σχεδίασης για την κύρια διαφάνεια. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Επιστρέφει τον διαχειριστή HeaderFooter της κύριας διαφάνειας. Μόνο ανάγνωση [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Επιστρέφει:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Δημιουργεί μια νέα κύρια διαφάνεια βασισμένη στην τρέχουσα, εφαρμόζοντας ένα εξωτερικό θέμα σε αυτήν και εφαρμόζει τη δημιουργημένη κύρια διαφάνεια σε όλες τις εξαρτημένες διαφάνειες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fname | java.lang.String | Διαδρομή προς το εξωτερικό αρχείο θέματος (.thmx). |

**Επιστρέφει:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Νέα με θέμα MasterSlide.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Επιστρέφει το στυλ του κειμένου τίτλου. Μόνο ανάγνωση [ITextStyle](../../com.aspose.slides/itextstyle).

**Επιστρέφει:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Επιστρέφει το στυλ του κειμένου σώματος. Μόνο ανάγνωση [ITextStyle](../../com.aspose.slides/itextstyle).

**Επιστρέφει:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Επιστρέφει το στυλ άλλου κειμένου. Μόνο ανάγνωση [ITextStyle](../../com.aspose.slides/itextstyle).

**Επιστρέφει:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Επιστρέφει τη συλλογή των θυγατρικών διαφανειών διάταξης για αυτήν την κύρια διαφάνεια. Μόνο ανάγνωση [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Μπορείτε να αποκτήσετε πρόσβαση σε εναλλακτικό API για προσθήκη/εισαγωγή/αφαίρεση/κλωνοποίηση διαφανειών διάταξης χρησιμοποιώντας την ιδιότητα ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Επιστρέφει:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Καθορίζει εάν η αντίστοιχη κύρια διαφάνεια διαγράφεται όταν διαγραφούν όλες οι διαφάνειες που ακολουθούν αυτήν. Σημείωση: Το Aspose.Slides δεν θα αφαιρέσει ποτέ αυτόματα κάποιο μη χρησιμοποιημένο master, για να αφαιρέσετε πραγματικά μη χρησιμοποιημένα masters καλέστε [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Ανάγνωση/εγγραφή boolean .

**Επιστρέφει:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Καθορίζει εάν η αντίστοιχη κύρια διαφάνεια διαγράφεται όταν διαγραφούν όλες οι διαφάνειες που ακολουθούν αυτήν. Σημείωση: Το Aspose.Slides δεν θα αφαιρέσει ποτέ αυτόματα κάποιο μη χρησιμοποιημένο master, για να αφαιρέσετε πραγματικά μη χρησιμοποιημένα masters καλέστε [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Ανάγνωση/εγγραφή boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Επιστρέφει έναν πίνακα με όλες τις διαφάνειες που εξαρτώνται από αυτήν την κύρια διαφάνεια.

**Επιστρέφει:**
com.aspose.slides.ISlide[] - Πίνακας των [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Επιστρέφει true εάν υπάρχει τουλάχιστον μία διαφάνεια που εξαρτάται από αυτήν την κύρια διαφάνεια. Μόνο ανάγνωση boolean .

**Επιστρέφει:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Επιστρέφει τον διαχειριστή θέματος. Μόνο ανάγνωση [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Επιστρέφει:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```

Επιστρέφει ή ορίζει το όνομα μιας κύριας διαφάνειας. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Επιστρέφει ή ορίζει το όνομα μιας κύριας διαφάνειας. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Καθορίζει εάν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Για τη δική της κύρια διαφάνεια αυτή η ιδιότητα πάντα επιστρέφει false. Ανάγνωση/εγγραφή boolean .

**Επιστρέφει:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Καθορίζει εάν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Για τη δική της κύρια διαφάνεια αυτή η ιδιότητα πάντα επιστρέφει false. Ανάγνωση/εγγραφή boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Επιστρέφει μια συλλογή οδηγών σχεδίασης για την κύρια διαφάνεια. Μόνο ανάγνωση [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Προσθήκη του νέου κάθετου οδηγού σχεδίασης στα δεξιά του κέντρου της διαφάνειας
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)