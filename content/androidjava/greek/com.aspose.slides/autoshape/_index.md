---
title: AutoShape
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει ένα AutoShape.
type: docs
url: /el/com.aspose.slides/autoshape/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Αναπαριστά ένα AutoShape.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Επιστρέφει τα κλειδώματα του σχήματος. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Επιστρέφει τα κλειδώματα του autoshape. |
| [getTextFrame()](#getTextFrame--) | Επιστρέφει το αντικείμενο TextFrame για το AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Καθορίζει αν αυτό το autoshape πρέπει να γεμίσει με το φόντο της διαφάνειας αντί για το στυλ ή τη μορφή γεμίσματος που καθορίζονται. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Καθορίζει αν αυτό το autoshape πρέπει να γεμίσει με το φόντο της διαφάνειας αντί για το στυλ ή τη μορφή γεμίσματος που καθορίζονται. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Προσθέτει ένα νέο TextFrame σε ένα σχήμα. |
| [isTextBox()](#isTextBox--) | Καθορίζει εάν το σχήμα είναι πλαίσιο κειμένου. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```


Επιστρέφει τα κλειδώματα του σχήματος. Μόνο-ανάγνωση [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Επιστρέφει:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```


Επιστρέφει τα κλειδώματα του autoshape. Μόνο-ανάγνωση [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Επιστρέφει:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Επιστρέφει το αντικείμενο TextFrame για το AutoShape. Μόνο-ανάγνωση [ITextFrame](../../com.aspose.slides/itextframe).

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```


Καθορίζει αν αυτό το autoshape πρέπει να γεμίσει με το φόντο της διαφάνειας αντί για το στυλ ή τη μορφή γεμίσματος που καθορίζονται. Boolean ανάγνωση/εγγραφή.

**Επιστρέφει:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```


Καθορίζει αν αυτό το autoshape πρέπει να γεμίσει με το φόντο της διαφάνειας αντί για το στυλ ή τη μορφή γεμίσματος που καθορίζονται. Boolean ανάγνωση/εγγραφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```


Προσθέτει ένα νέο TextFrame σε ένα σχήμα. Εάν το σχήμα διαθέτει ήδη TextFrame, τότε απλώς αλλάζει το κείμενό του.

--------------------

> ```
> The following sample code shows how to add watermark text in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape watermarkShape = slide.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 150, 50);
>      ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to create Text Box on Slide.
>  
>  // Δημιουργεί παρουσίαση
>  Presentation pres = new Presentation();
>  try {
>      // Αποκτά την πρώτη διαφάνεια στην παρουσίαση
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Προσθέτει ένα AutoShape με τύπο ορισμένο ως Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Προσθέτει TextFrame στο Rectangle
>      ashp.addTextFrame(" ");
>      // Πρόσβαση στο πλαίσιο κειμένου
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Δημιουργεί το αντικείμενο Paragraph για το πλαίσιο κειμένου
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Δημιουργεί ένα αντικείμενο Portion για την παράγραφο
>      IPortion portion = para.getPortions().get_Item(0);
>      // Ορίζει το κείμενο
>      portion.setText("Aspose TextBox");
>      // Αποθηκεύει την παρουσίαση στον δίσκο
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Αποκτά την πρώτη διαφάνεια στην παρουσίαση
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Προσθέτει ένα AutoShape με τύπο ορισμένο ως Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Προσθέτει TextFrame στο Rectangle
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Αποκτά τη μορφή κειμένου του TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Καθορίζει τον αριθμό των στηλών στο TextFrame
>      format.setColumnCount(3);
>      // Καθορίζει την απόσταση μεταξύ των στηλών
>      format.setColumnSpacing(10);
>      // Αποθηκεύει την παρουσίαση
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Προεπιλεγμένο κείμενο για ένα νέο TextFrame. |

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```


Καθορίζει αν το σχήμα είναι πλαίσιο κειμένου.

--------------------

Το ότι το σχήμα δεν έχει οριστεί ως πλαίσιο κειμένου δεν σημαίνει ότι δεν μπορεί να έχει κείμενο συνδεδεμένο με αυτό. Ένα πλαίσιο κειμένου είναι απλώς ένα εξειδικευμένο σχήμα με συγκεκριμένες ιδιότητες.

**Επιστρέφει:**
boolean