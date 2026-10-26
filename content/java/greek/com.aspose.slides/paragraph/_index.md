---
title: Paragraph
second_title: Aspose.Slides για την Αναφορά API Java
description: Αντιπροσωπεύει μια παράγραφο κειμένου.
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

Αντιπροσωπεύει μια παράγραφο κειμένου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Paragraph()](#Paragraph--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Paragraph με προεπιλεγμένες ιδιότητες. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Κατασκευαστής αντιγραφής που αρχικοποιεί ένα νέο αντικείμενο της κλάσης Paragraph. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPortions()](#getPortions--) | Επιστρέφει τη συλλογή των τμημάτων κειμένου. |
| [getParagraphFormat()](#getParagraphFormat--) | Επιστρέφει το αντικείμενο μορφοποίησης για αυτήν την παράγραφο. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Ενώνει τμήματα με την ίδια μορφοποίηση. |
| [getText()](#getText--) | Λαμβάνει ή θέτει το απλό κείμενο μιας παραγράφου. |
| [setText(String value)](#setText-java.lang.String-) | Λαμβάνει ή θέτει το απλό κείμενο μιας παραγράφου. |
| [getRect()](#getRect--) | Λαμβάνει τις συντεταγμένες του ορθογωνίου που περιβάλλει την παράγραφο. |
| [getLinesCount()](#getLinesCount--) | Λαμβάνει τον αριθμό γραμμών σε μια παράγραφο. |
| [getImage()](#getImage--) | Επιστρέφει μια εικόνα της παραγράφου. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Επιστρέφει μια εικόνα της παραγράφου με την καθορισμένη κλίμακα. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Καθορίζει τις ιδιότητες τμήματος που θα χρησιμοποιηθούν εάν εισαχθεί ένα άλλο τμήμα μετά το τελευταίο. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Καθορίζει τις ιδιότητες τμήματος που θα χρησιμοποιηθούν εάν εισαχθεί ένα άλλο τμήμα μετά το τελευταίο. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια μιας παραγράφου. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση μιας παραγράφου. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Paragraph με προεπιλεγμένες ιδιότητες.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```


Κατασκευαστής αντιγραφής που αρχικοποιεί ένα νέο αντικείμενο της κλάσης Paragraph.

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

Το αντικείμενο μορφοποίησης περιέχει τις παραμέτρους μορφοποίησης που ορίζονται μόνο για την τρέχουσα παράγραφο, τα κληρονομημένα δεδομένα δεν εφαρμόζονται.

Για να λάβετε τις αποτελεσματικές τιμές, συμπεριλαμβανομένων των κληρονομημένων, χρησιμοποιήστε τη μέθοδο [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

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


Λαμβάνει ή θέτει το απλό κείμενο μιας παραγράφου. Ανάγνωση/εγγραφή String.

Τιμή: Το κείμενο.

**Επιστρέφει:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Λαμβάνει ή θέτει το απλό κείμενο μιας παραγράφου. Ανάγνωση/εγγραφή String.

Τιμή: Το κείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```


Λαμβάνει τις συντεταγμένες του ορθογωνίου που περιβάλλει την παράγραφο. Το ορθογώνιο περιλαμβάνει όλες τις γραμμές κειμένου στην παράγραφο, συμπεριλαμβανομένων των κενών.

**Επιστρέφει:**
java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```


Λαμβάνει τον αριθμό γραμμών σε μια παράγραφο.

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
### getImage() {#getImage--}
```
public final IImage getImage()
```


Επιστρέφει μια εικόνα της παραγράφου.

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Μια εικόνα που περιέχει την αποτυπωμένη παράγραφο, ή null εάν η παράγραφο δεν μπορεί να βρεθεί στη γονική συλλογή, δεν έχει έγκυρα όρια αποτύπωσης, ή προκύψει σφάλμα κατά την αποτύπωση της εικόνας.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```


Επιστρέφει μια εικόνα της παραγράφου με την καθορισμένη κλίμακα.

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scaleX | float | Ο οριζόντιος συντελεστής κλίμακας που εφαρμόζεται στην εικόνα της παραγράφου. |
| scaleY | float | Ο κάθετος συντελεστής κλίμακας που εφαρμόζεται στην εικόνα της παραγράφου. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Μια εικόνα που περιέχει την αποτυπωμένη παράγραφο, ή null εάν η παράγραφο δεν μπορεί να βρεθεί στη γονική συλλογή, δεν έχει έγκυρα όρια αποτύπωσης, ή προκύψει σφάλμα κατά την αποτύπωση της εικόνας.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```


Καθορίζει τις ιδιότητες τμήματος που θα χρησιμοποιηθούν εάν εισαχθεί ένα άλλο τμήμα μετά το τελευταίο.

**Επιστρέφει:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```


Καθορίζει τις ιδιότητες τμήματος που θα χρησιμοποιηθούν εάν εισαχθεί ένα άλλο τμήμα μετά το τελευταίο.

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