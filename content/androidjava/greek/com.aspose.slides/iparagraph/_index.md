---
title: IParagraph
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά μια παράγραφο κειμένου.
type: docs
url: /el/com.aspose.slides/iparagraph/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Αναπαριστά μια παράγραφο κειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPortions()](#getPortions--) | Επιστρέφει τη συλλογή των τμημάτων κειμένου. |
| [getParagraphFormat()](#getParagraphFormat--) | Επιστρέφει το αντικείμενο μορφοποίησης για αυτήν την παράγραφο. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Συνδέει τμήματα με ίδια μορφοποίηση. |
| [getText()](#getText--) | Ανακτά ή ορίζει το καθαρό κείμενο μιας παραγράφου. |
| [setText(String value)](#setText-java.lang.String-) | Ανακτά ή ορίζει το καθαρό κείμενο μιας παραγράφου. |
| [getRect()](#getRect--) | Λαμβάνει τις συντεταγμένες του ορθογωνίου που περιορίζει την παράγραφο. |
| [getLinesCount()](#getLinesCount--) | Λαμβάνει τον αριθμό των γραμμών σε μια παράγραφο. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Καθορίζει τις ιδιότητες τμήματος που θα χρησιμοποιηθούν εάν εισαχθεί ένα άλλο τμήμα μετά το τελευταίο. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Καθορίζει τις ιδιότητες τμήματος που θα χρησιμοποιηθούν εάν εισαχθεί ένα άλλο τμήμα μετά το τελευταίο. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

Επιστρέφει τη συλλογή των τμημάτων κειμένου. Μόνο ανάγνωση [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Επιστρέφει:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

Επιστρέφει το αντικείμενο μορφοποίησης για αυτήν την παράγραφο. Μόνο ανάγνωση [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Επιστρέφει:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Συνδέει τμήματα με ίδια μορφοποίηση.

### getText() {#getText--}
```
public abstract String getText()
```

Ανακτά ή ορίζει το καθαρό κείμενο μιας παραγράφου. Ανάγνωση/Εγγραφή String.

Τιμή: Το κείμενο.

**Επιστρέφει:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Ανακτά ή ορίζει το καθαρό κείμενο μιας παραγράφου. Ανάγνωση/Εγγραφή String.

Τιμή: Το κείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract RectF getRect()
```

Λαμβάνει τις συντεταγμένες του ορθογωνίου που περιορίζει την παράγραφο. Το ορθογώνιο περιλαμβάνει όλες τις γραμμές κειμένου στην παράγραφο, συμπεριλαμβανομένων των κενών.

**Επιστρέφει:**
android.graphics.RectF - Ορθογώνιο που περιορίζει την παράγραφο android.graphics.RectF
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
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

Καθορίζει τις ιδιότητες τμήματος που θα χρησιμοποιηθούν εάν εισαχθεί ένα άλλο τμήμα μετά το τελευταίο.

**Επιστρέφει:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

Καθορίζει τις ιδιότητες τμήματος που θα χρησιμοποιηθούν εάν εισαχθεί ένα άλλο τμήμα μετά το τελευταίο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |