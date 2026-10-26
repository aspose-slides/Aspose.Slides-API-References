---
title: IModernComment
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει ένα σχόλιο σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/imoderncomment/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Αντιπροσωπεύει ένα σχόλιο σε μια διαφάνεια.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShape()](#getShape--) | Επιστρέφει ένα σχήμα που σχετίζεται με το σχόλιο. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Επιστρέφει ή ορίζει τη θέση εκκίνησης της επιλογής κειμένου σε πλαίσιο κειμένου εάν το σχόλιο είναι συσχετισμένο με AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Επιστρέφει ή ορίζει τη θέση εκκίνησης της επιλογής κειμένου σε πλαίσιο κειμένου εάν το σχόλιο είναι συσχετισμένο με AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Επιστρέφει ή ορίζει το μήκος της επιλογής κειμένου σε πλαίσιο κειμένου εάν το σχόλιο είναι συσχετισμένο με AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Επιστρέφει ή ορίζει το μήκος της επιλογής κειμένου σε πλαίσιο κειμένου εάν το σχόλιο είναι συσχετισμένο με AutoShape. |
| [getStatus()](#getStatus--) | Επιστρέφει ή ορίζει την κατάσταση του σχολίου. |
| [setStatus(byte value)](#setStatus-byte-) | Επιστρέφει ή ορίζει την κατάσταση του σχολίου. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```


Επιστρέφει ένα σχήμα που σχετίζεται με το σχόλιο. Μόνο για ανάγνωση [IShape](../../com.aspose.slides/ishape).

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```


Επιστρέφει ή ορίζει τη θέση εκκίνησης της επιλογής κειμένου σε πλαίσιο κειμένου εάν το σχόλιο είναι συσχετισμένο με AutoShape. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```


Επιστρέφει ή ορίζει τη θέση εκκίνησης της επιλογής κειμένου σε πλαίσιο κειμένου εάν το σχόλιο είναι συσχετισμένο με AutoShape. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```


Επιστρέφει ή ορίζει το μήκος της επιλογής κειμένου σε πλαίσιο κειμένου εάν το σχόλιο είναι συσχετισμένο με AutoShape. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```


Επιστρέφει ή ορίζει το μήκος της επιλογής κειμένου σε πλαίσιο κειμένου εάν το σχόλιο είναι συσχετισμένο με AutoShape. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```


Επιστρέφει ή ορίζει την κατάσταση του σχολίου. Ανάγνωση/εγγραφή [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Επιστρέφει:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```


Επιστρέφει ή ορίζει την κατάσταση του σχολίου. Ανάγνωση/εγγραφή [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |