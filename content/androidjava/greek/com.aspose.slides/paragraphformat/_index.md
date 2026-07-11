---
title: ParagraphFormat
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αυτή η κλάση περιέχει τις ιδιότητες διαμόρφωσης παραγράφου.
type: docs
url: /el/com.aspose.slides/paragraphformat/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Αυτή η κλάση περιέχει τις ιδιότητες διαμόρφωσης παραγράφου. Σε αντίθεση με [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.

--------------------

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων διαμόρφωσης παραγράφου που ορίζονται για τη συγκεκριμένη παράγραφο. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομικότητα κατά την ανάκτηση των τιμών, έτσι σε περισσότερες περιπτώσεις θα λαμβάνετε τιμές που σημαίνουν «απροσδιόριστη».

Για να λάβετε τις αποτελεσματικές τιμές των παραμέτρων διαμόρφωσης, συμπεριλαμβανομένων των κληρονομημένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) που επιστρέφει ένα αντικείμενο τύπου [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [ParagraphFormat](../../com.aspose.slides/paragraphformat). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBullet()](#getBullet--) | Επιστρέφει τη μορφή κουκκίδας της παραγράφου. |
| [getDepth()](#getDepth--) | Επιστρέφει ή ορίζει το βάθος της παραγράφου. |
| [setDepth(short value)](#setDepth-short-) | Επιστρέφει ή ορίζει το βάθος της παραγράφου. |
| [getAlignment()](#getAlignment--) | Επιστρέφει ή ορίζει την ευθυγράμμιση κειμένου σε μια παράγραφο χωρίς κληρονομικότητα. |
| [setAlignment(int value)](#setAlignment-int-) | Επιστρέφει ή ορίζει την ευθυγράμμιση κειμένου σε μια παράγραφο χωρίς κληρονομικότητα. |
| [getSpaceWithin()](#getSpaceWithin--) | Επιστρέφει ή ορίζει την ποσότητα του διαστήματος μεταξύ των βασικών γραμμών σε μια παράγραφο. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Επιστρέφει ή ορίζει την ποσότητα του διαστήματος μεταξύ των βασικών γραμμών σε μια παράγραφο. |
| [getSpaceBefore()](#getSpaceBefore--) | Επιστρέφει ή ορίζει την ποσότητα του διαστήματος πριν από την πρώτη γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Επιστρέφει ή ορίζει την ποσότητα του διαστήματος πριν από την πρώτη γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. |
| [getSpaceAfter()](#getSpaceAfter--) | Επιστρέφει ή ορίζει την ποσότητα του διαστήματος μετά την τελευταία γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Επιστρέφει ή ορίζει την ποσότητα του διαστήματος μετά την τελευταία γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Καθορίζει αν χρησιμοποιείται η αναγνώριση γραμμής Ανατολικής Ασίας σε μια παράγραφο. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Καθορίζει αν χρησιμοποιείται η αναγνώριση γραμμής Ανατολικής Ασίας σε μια παράγραφο. |
| [getRightToLeft()](#getRightToLeft--) | Καθορίζει αν χρησιμοποιείται η γραφή από δεξιά προς αριστερά σε μια παράγραφο. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Καθορίζει αν χρησιμοποιείται η γραφή από δεξιά προς αριστερά σε μια παράγραφο. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Καθορίζει αν χρησιμοποιείται η γραμμή διάλειψης Λατινικής σε μια παράγραφο. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Καθορίζει αν χρησιμοποιείται η γραμμή διάλειψης Λατινικής σε μια παράγραφο. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Καθορίζει αν χρησιμοποιείται η κρεμαστή στίξη σε μια παράγραφο. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Καθορίζει αν χρησιμοποιείται η κρεμαστή στίξη σε μια παράγραφο. |
| [getMarginLeft()](#getMarginLeft--) | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. |
| [getMarginRight()](#getMarginRight--) | Επιστρέφει ή ορίζει το δεξί περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. |
| [setMarginRight(float value)](#setMarginRight-float-) | Επιστρέφει ή ορίζει το δεξί περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. |
| [getIndent()](#getIndent--) | Επιστρέφει ή ορίζει το εσοχή πρώτης γραμμής/κρεμασμένη εσοχή παραγράφου χωρίς κληρονομικότητα. |
| [setIndent(float value)](#setIndent-float-) | Επιστρέφει ή ορίζει το εσοχή πρώτης γραμμής/κρεμασμένη εσοχή παραγράφου χωρίς κληρονομικότητα. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος εσοχής χωρίς κληρονομικότητα. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος εσοχής χωρίς κληρονομικότητα. |
| [getTabs()](#getTabs--) | Επιστρέφει τις εσοχές μιας παραγράφου. |
| [getFontAlignment()](#getFontAlignment--) | Επιστρέφει ή ορίζει μια ευθυγράμμιση γραμματοσειράς σε μια παράγραφο χωρίς κληρονομικότητα. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Επιστρέφει ή ορίζει μια ευθυγράμμιση γραμματοσειράς σε μια παράγραφο χωρίς κληρονομικότητα. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Επιστρέφει το προεπιλεγμένο φορμάτ τμήματος μιας παραγράφου. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα διαμόρφωσης παραγράφου με εφαρμογή κληρονομικότητας. |
| [getVersion()](#getVersion--) |  |
### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [ParagraphFormat](../../com.aspose.slides/paragraphformat).

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

Επιστρέφει τη μορφή κουκκίδας της παραγράφου. Μόνο για ανάγνωση [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Επιστρέφει:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```

Επιστρέφει ή ορίζει το βάθος της παραγράφου. Η τιμή 0 σημαίνει απροσδιόριστη τιμή. Ανάγνωση/εγγραφή  short .

**Επιστρέφει:**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

Επιστρέφει ή ορίζει το βάθος της παραγράφου. Η τιμή 0 σημαίνει απροσδιόριστη τιμή. Ανάγνωση/εγγραφή  short .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | short |  |
### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Επιστρέφει ή ορίζει την ευθυγράμμιση κειμένου σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a PPTX file
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Accessing first slide
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accessing the first and second placeholder in the slide and typecasting it as AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Change the text in both placeholders
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Getting the first paragraph of the placeholders
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Aligning the text paragraph to center
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Writing the presentation as a PPTX file
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Επιστρέφει ή ορίζει την ευθυγράμιση κειμένου σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a PPTX file
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Accessing first slide
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accessing the first and second placeholder in the slide and typecasting it as AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Change the text in both placeholders
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Getting the first paragraph of the placeholders
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Aligning the text paragraph to center
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Writing the presentation as a PPTX file
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

Επιστρέφει ή ορίζει την ποσότητα του διαστήματος μεταξύ των βασικών γραμμών σε μια παράγραφο. Θετική τιμή σημαίνει ποσοστό, αρνητική – μέγεθος σε σημείο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Επιστρέφει ή ορίζει την ποσότητα του διαστήματος μεταξύ των βασικών γραμμών σε μια παράγραφο. Θετική τιμή σημαίνει ποσοστό, αρνητική – μέγεθος σε σημείο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Επιστρέφει ή ορίζει την ποσότητα του διαστήματος πριν από την πρώτη γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. Θετική τιμή καθορίζει το ποσοστό του μεγέθους γραμματοσειράς που πρέπει να είναι το λευκό διάστημα. Αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε μονάδες σημείου. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Επιστρέφει ή ορίζει την ποσότητα του διαστήματος πριν από την πρώτη γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. Θετική τιμή καθορίζει το ποσοστό του μεγέθους γραμματοσειράς που πρέπει να είναι το λευκό διάστημα. Αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε μονάδες σημείου. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Επιστρέφει ή ορίζει την ποσότητα του διαστήματος μετά την τελευταία γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. Θετική τιμή καθορίζει το ποσοστό του μεγέθους γραμματοσειράς που πρέπει να είναι το λευκό διάστημα. Αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε μονάδες σημείου. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Επιστρέφει ή ορίζει την ποσότητα του διαστήματος μετά την τελευταία γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. Θετική τιμή καθορίζει το ποσοστό του μεγέθους γραμματοσειράς που πρέπει να είναι το λευκό διάστημα. Αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε μονάδες σημείου. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

Καθορίζει αν χρησιμοποιείται η αναγνώριση γραμμής Ανατολικής Ασίας σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Καθορίζει αν χρησιμοποιείται η αναγνώριση γραμμής Ανατολικής Ασίας σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Καθορίζει αν χρησιμοποιείται η γραφή από δεξιά προς αριστερά σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Καθορίζει αν χρησιμοποιείται η γραφή από δεξιά προς αριστερά σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Καθορίζει αν χρησιμοποιείται η γραμμή διάλειψης Λατινικής σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Καθορίζει αν χρησιμοποιείται η γραμμή διάλειψης Λατινικής σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Καθορίζει αν χρησιμοποιείται η κρεμαστή στίξη σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Καθορίζει αν χρησιμοποιείται η κρεμαστή στίξη σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

Επιστρέφει ή ορίζει το αριστερό περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

Επιστρέφει ή ορίζει το αριστερό περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

Επιστρέφει ή ορίζει το δεξί περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

Επιστρέφει ή ορίζει το δεξί περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getIndent() {#getIndent--}
```
public final float getIndent()
```

Επιστρέφει ή ορίζει το εσοχή πρώτης γραμμής/κρεμασμένη εσοχή παραγράφου χωρίς κληρονομικότητα. Η κρεμαστή εσοχή μπορεί να οριστεί με αρνητικές τιμές. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Επιστρέφει ή ορίζει το εσοχή πρώτης γραμμής/κρεμασμένη εσοχή παραγράφου χωρίς κληρονομικότητα. Η κρεμαστή εσοχή μπορεί να οριστεί με αρνητικές τιμές. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος εσοχής χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος εσοχής χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

Επιστρέφει τις εσοχές μιας παραγράφου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [ITabCollection](../../com.aspose.slides/itabcollection).

**Επιστρέφει:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

Επιστρέφει ή ορίζει μια ευθυγράμμιση γραμματοσειράς σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή [FontAlignment](../../com.aspose.slides/fontalignment).

**Επιστρέφει:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

Επιστρέφει ή ορίζει μια ευθυγράμμιση γραμματοσειράς σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή [FontAlignment](../../com.aspose.slides/fontalignment).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

Επιστρέφει το προεπιλεγμένο φορμάτ τμήματος μιας παραγράφου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [IPortionFormat](../../com.aspose.slides/iportionformat).

**Επιστρέφει:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα διαμόρφωσης παραγράφου με εφαρμογή κληρονομικότητας.

--------------------

> ```
> This example demonstrates getting some effective paragraph format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long