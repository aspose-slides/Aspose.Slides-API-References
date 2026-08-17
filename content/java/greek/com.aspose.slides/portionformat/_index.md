---
title: PortionFormat
second_title: Aspose.Slides για την Αναφορά API Java
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμήματος κειμένου.
type: docs
url: /el/com.aspose.slides/portionformat/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμήματος κειμένου. Σε αντίθεση με το [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Δημιουργήστε ένα αντικείμενο παρουσίασης που αντιπροσωπεύει ένα αρχείο παρουσίασης
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Το Aspose.Slides χρησιμοποιεί αυτούς τους ειδικούς ταυτοποιητές (παρόμοιους με αυτούς που χρησιμοποιούνται στο PowerPoint):
>      // +mn-lt - Σώμα γραμματοσειράς Λατινική (Δευτερεύουσα Λατινική Γραμματοσειρά)
>      // +mj-lt -Κεφαλίδα γραμματοσειράς Λατινική (Κύρια Λατινική Γραμματοσειρά)
>      // +mn-ea - Σώμα γραμματοσειράς Ανατολική Ασιατική (Δευτερεύουσα Ανατολική Ασιατική Γραμματοσειρά)
>      // +mj-ea - Σώμα γραμματοσειράς Ανατολική Ασιατική (Δευτερεύουσα Ανατολική Ασιατική Γραμματοσειρά)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης τμήματος κειμένου που ορίζονται για το συγκεκριμένο τμήμα. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομικότητα κατά τη λήψη τιμών, έτσι στις περισσότερες περιπτώσεις θα λαμβάνετε τιμές που σημαίνουν «απροσδιόριστο».

Για να λάβετε τις αποτελεσματικές τιμές των παραμέτρων μορφοποίησης, συμπεριλαμβανομένων των κληρονομημένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [getEffective](../../com.aspose.slides/portionformat\#getEffective) η οποία επιστρέφει μια παρουσία [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Δημιουργεί μια νέα παρουσία της κλάσης [PortionFormat](../../com.aspose.slides/portionformat). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Επιστρέφει ή ορίζει το αναγνωριστικό σελιδοδείκτη. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Επιστρέφει ή ορίζει το αναγνωριστικό σελιδοδείκτη. |
| [getSmartTagClean()](#getSmartTagClean--) | Καθορίζει αν η έξυπνη ετικέτα πρέπει να καθαριστεί. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Καθορίζει αν η έξυπνη ετικέτα πρέπει να καθαριστεί. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για μετάβαση ποντικιού. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για μετάβαση ποντικιού. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Διαχειριστής υπερσυνδέσμων. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης τμήματος με την εφαρμοσμένη κληρονομικότητα. |

### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```


Δημιουργεί μια νέα παρουσία της κλάσης [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```


Επιστρέφει ή ορίζει το αναγνωριστικό σελιδοδείκτη. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```


Επιστρέφει ή ορίζει το αναγνωριστικό σελιδοδείκτη. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```


Καθορίζει αν η έξυπνη ετικέτα πρέπει να καθαριστεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή  boolean .

**Επιστρέφει:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```


Καθορίζει αν η έξυπνη ετικέτα πρέπει να καθαριστεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή  boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```


Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/εγγραφή [IHyperlink](../../com.aspose.slides/ihyperlink).

**Επιστρέφει:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```


Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/εγγραφή [IHyperlink](../../com.aspose.slides/ihyperlink).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```


Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για μετάβαση ποντικιού. Ανάγνωση/εγγραφή [IHyperlink](../../com.aspose.slides/ihyperlink).

**Επιστρέφει:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```


Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για μετάβαση ποντικιού. Ανάγνωση/εγγραφή [IHyperlink](../../com.aspose.slides/ihyperlink).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```


Διαχειριστής υπερσυνδέσμων. Μόνο για ανάγνωση [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Επιστρέφει:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```


Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης τμήματος με την εφαρμοσμένη κληρονομικότητα.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).