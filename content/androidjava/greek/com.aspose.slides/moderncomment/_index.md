---
title: ModernComment
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αναπαριστά ένα σχόλιο σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/moderncomment/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
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
| [getTextSelectionStart()](#getTextSelectionStart--) | Λαμβάνει ή ορίζει τη θέση έναρξης της επιλογής κειμένου στο πλαίσιο κειμένου εάν το σχόλιο σχετίζεται με AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Λαμβάνει ή ορίζει τη θέση έναρξης της επιλογής κειμένου στο πλαίσιο κειμένου εάν το σχόλιο σχετίζεται με AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Λαμβάνει ή ορίζει το μήκος της επιλογής κειμένου στο πλαίσιο κειμένου εάν το σχόλιο σχετίζεται με AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Λαμβάνει ή ορίζει το μήκος της επιλογής κειμένου στο πλαίσιο κειμένου εάν το σχόλιο σχετίζεται με AutoShape. |
| [getStatus()](#getStatus--) | Λαμβάνει ή ορίζει την κατάσταση του σχολίου. |
| [setStatus(byte value)](#setStatus-byte-) | Λαμβάνει ή ορίζει την κατάσταση του σχολίου. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getShape() {#getShape--}
```
public final IShape getShape()
```

Επιστρέφει ένα σχήμα που σχετίζεται με το σχόλιο. Μόνο για ανάγνωση [IShape](../../com.aspose.slides/ishape).

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)

### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

Λαμβάνει ή ορίζει τη θέση έναρξης της επιλογής κειμένου στο πλαίσιο κειμένου εάν το σχόλιο σχετίζεται με AutoShape. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

Λαμβάνει ή ορίζει τη θέση έναρξης της επιλογής κειμένου στο πλαίσιο κειμένου εάν το σχόλιο σχετίζεται με AutoShape. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

Λαμβάνει ή ορίζει το μήκος της επιλογής κειμένου στο πλαίσιο κειμένου εάν το σχόλιο σχετίζεται με AutoShape. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

Λαμβάνει ή ορίζει το μήκος της επιλογής κειμένου στο πλαίσιο κειμένου εάν το σχόλιο σχετίζεται με AutoShape. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```

Λαμβάνει ή ορίζει την κατάσταση του σχολίου. Ανάγνωση/εγγραφή [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Επιστρέφει:**
byte

### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

Λαμβάνει ή ορίζει την κατάσταση του σχολίου. Ανάγνωση/εγγραφή [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject