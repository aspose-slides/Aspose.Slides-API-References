---
title: Paragraph
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεί μια παράγραφο κειμένου.
type: docs
url: /el/com.aspose.slides/paragraph/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Αντιπροσωπεί μια παράγραφο κειμένου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Paragraph()](#Paragraph--) | Αρχικοποιεί μια νέα εμφάνιση της κλάσης Paragraph με προεπιλεγμένες ιδιότητες. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Κατασκευαστής αντιγραφής που αρχικοποιεί μια νέα εμφάνιση της κλάσης Paragraph. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPortions()](#getPortions--) | Επιστρέφει τη συλλογή των τμημάτων κειμένου. |
| [getParagraphFormat()](#getParagraphFormat--) | Επιστρέφει το αντικείμενο μορφοποίησης για αυτήν την παράγραφο. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Ενώνοντας τμήματα με την ίδια μορφοποίηση. |
| [getText()](#getText--) | Ανακτά ή ορίζει το απλό κείμενο μιας παραγράφου. |
| [setText(String value)](#setText-java.lang.String-) | Ανακτά ή ορίζει το απλό κείμενο μιας παραγράφου. |
| [getRect()](#getRect--) | Λαμβάνει συντεταγμένες του ορθογωνίου που περιβάλλει την παράγραφο. |
| [getLinesCount()](#getLinesCount--) | Λαμβάνει τον αριθμό των γραμμών σε μια παράγραφο. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Καθορίζει τις ιδιότητες του τμήματος που θα χρησιμοποιηθούν αν εισαχθεί άλλο τμήμα μετά το τελευταίο. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Καθορίζει τις ιδιότητες του τμήματος που θα χρησιμοποιηθούν αν εισαχθεί άλλο τμήμα μετά το τελευταίο. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια μιας παραγράφου. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση μιας παραγράφου. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```


Αρχικοποιεί μια νέα εμφάνιση της κλάσης Paragraph με προεπιλεγμένες ιδιότητες.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```


Κατασκευαστής αντιγραφής που αρχικοποιεί μια νέα εμφάνιση της κλάσης Paragraph.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```


Επιστρέφει τη συλλογή των τμημάτων κειμένου. Μόνο για ανάγνωση [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Επιστρέφει:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```


Επιστρέφει το αντικείμενο μορφοποίησης για αυτήν την παράγραφο. Μόνο για ανάγνωση [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Το αντικείμενο μορφοποίησης περιέχει τις παραμέτρους μορφοποίησης που ορίζονται μόνο για την τρέχουσα παράγραφο, τα κληρονομισμένα δεδομένα δεν εφαρμόζονται.

Για να αποκτήσετε τις αποτελεσματικές τιμές συμπεριλαμβανομένων των κληρονομισμένων, χρησιμοποιήστε τη μέθοδο [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Επιστρέφει:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Ενώνει τμήματα με την ίδια μορφοποίηση.

### getText() {#getText--}
```
public final String getText()
```


Ανακτά ή ορίζει το απλό κείμενο μιας παραγράφου. Ανάγνωση/εγγραφή String.

Τιμή: Το κείμενο.

**Επιστρέφει:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Ανακτά ή ορίζει το απλό κείμενο μιας παραγράφου. Ανάγνωση/εγγραφή String.

Τιμή: Το κείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```


Λαμβάνει τις συντεταγμένες του ορθογωνίου που περιβάλλει την παράγραφο. Το ορθογώνιο περιλαμβάνει όλες τις γραμμές κειμένου στην παράγραφο, συμπεριλαμβανομένων και των κενών.

**Επιστρέφει:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```


Λαμβάνει τον αριθμό των γραμμών σε μια παράγραφο.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
int - Αριθμός γραμμών σε μια παράγραφο
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```


Καθορίζει τις ιδιότητες του τμήματος που θα χρησιμοποιηθούν αν εισαχθεί άλλο τμήμα μετά το τελευταίο.

**Επιστρέφει:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```


Καθορίζει τις ιδιότητες του τμήματος που θα χρησιμοποιηθούν αν εισαχθεί άλλο τμήμα μετά το τελευταίο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Επιστρέφει τη γονική διαφάνεια μιας παραγράφου. Μόνο για ανάγνωση [BaseSlide](../../com.aspose.slides/baseslide).

**Επιστρέφει:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Επιστρέφει την γονική παρουσίαση μιας παραγράφου. Μόνο για ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)