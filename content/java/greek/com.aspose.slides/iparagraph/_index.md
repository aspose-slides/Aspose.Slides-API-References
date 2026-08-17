---
title: IParagraph
second_title: Aspose.Slides για Java Αναφορά API
description: Αντιπροσωπεύει μια παράγραφο κειμένου.
type: docs
url: /el/com.aspose.slides/iparagraph/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Αντιπροσωπεύει μια παράγραφο κειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPortions()](#getPortions--) | Επιστρέφει τη συλλογή τμημάτων κειμένου. |
| [getParagraphFormat()](#getParagraphFormat--) | Επιστρέφει το αντικείμενο μορφοποίησης για αυτήν την παράγραφο. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Συμπενδώνει τμήματα με την ίδια μορφοποίηση. |
| [getText()](#getText--) | Λαμβάνει ή ορίζει το απλό κείμενο μιας παραγράφου. |
| [setText(String value)](#setText-java.lang.String-) | Λαμβάνει ή ορίζει το απλό κείμενο μιας παραγράφου. |
| [getRect()](#getRect--) | Λαμβάνει τις συντεταγμένες του ορθογωνίου που περιβάλλει την παράγραφο. |
| [getLinesCount()](#getLinesCount--) | Λαμβάνει τον αριθμό των γραμμών σε μια παράγραφο. |
| [getImage()](#getImage--) | Επιστρέφει μια εικόνα της παραγράφου. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Επιστρέφει μια εικόνα της παραγράφου με την καθορισμένη κλίμακα. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Καθορίζει τις ιδιότητες τμήματος που θα χρησιμοποιηθούν εάν ένα άλλο τμήμα εισαχθεί μετά το τελευταίο. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Καθορίζει τις ιδιότητες τμήματος που θα χρησιμοποιηθούν εάν ένα άλλο τμήμα εισαχθεί μετά το τελευταίο. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```


Επιστρέφει τη συλλογή τμημάτων κειμένου. Μόνο για ανάγνωση [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Επιστρέφει:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```


Επιστρέφει το αντικείμενο μορφοποίησης για αυτήν την παράγραφο. Μόνο για ανάγνωση [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Επιστρέφει:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Συμπενδώνει τμήματα με την ίδια μορφοποίηση.

### getText() {#getText--}
```
public abstract String getText()
```


Λαμβάνει ή ορίζει το απλό κείμενο μιας παραγράφου. Ανάγνωση/Εγγραφή String.

Τιμή: Το κείμενο.

**Επιστρέφει:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Λαμβάνει ή ορίζει το απλό κείμενο μιας παραγράφου. Ανάγνωση/Εγγραφή String.

Τιμή: Το κείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```


Λαμβάνει τις συντεταγμένες του ορθογωνίου που περιβάλλει την παράγραφο. Το ορθογώνιο περιλαμβάνει όλες τις γραμμές κειμένου στην παράγραφο, συμπεριλαμβανομένων των κενών.

**Επιστρέφει:**
java.awt.geom.Rectangle2D.Float - Rectangle that bounds paragraph java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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
### getImage() {#getImage--}
```
public abstract IImage getImage()
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
[IImage](../../com.aspose.slides/iimage) - Μια εικόνα που περιέχει την απόδοση της παραγράφου, ή null εάν η παράγραφος δεν μπορεί να βρεθεί στη γονική συλλογή της, δεν έχει έγκυρα όρια απόδοσης, ή προκύψει σφάλμα κατά την απόδοση της εικόνας.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
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
[IImage](../../com.aspose.slides/iimage) - Μια εικόνα που περιέχει την απόδοση της παραγράφου, ή null εάν η παράγραφος δεν μπορεί να βρεθεί στη γονική συλλογή της, δεν έχει έγκυρα όρια απόδοσης, ή προκύψει σφάλμα κατά την απόδοση της εικόνας.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```


Καθορίζει τις ιδιότητες τμήματος που θα χρησιμοποιηθούν εάν ένα άλλο τμήμα εισαχθεί μετά το τελευταίο.

**Επιστρέφει:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


Καθορίζει τις ιδιότητες τμήματος που θα χρησιμοποιηθούν εάν ένα άλλο τμήμα εισαχθεί μετά το τελευταίο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |