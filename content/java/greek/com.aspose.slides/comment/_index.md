---
title: Comment
second_title: Aspose.Slides για Java – Αναφορά API
description: Αναπαριστά ένα σχόλιο σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/comment/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

Αναπαριστά ένα σχόλιο σε μια διαφάνεια.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Αρχικοποιεί την κλάση Presentation
>  Presentation presentation = new Presentation();
>  try {
>     // Προσθέτει μια κενή διαφάνεια
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Προσθέτει έναν συγγραφέα
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Ορίζει τη θέση για σχόλια
>      Point2D.Float point = new Point2D.Float();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Προσθέτει σχόλιο διαφάνειας για έναν συγγραφέα στη διαφάνεια 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Προσθέτει σχόλιο διαφάνειας για έναν συγγραφέα στη διαφάνεια 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Αποθηκεύει το αρχείο παρουσίασης PowerPoint
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Αρχικοποιεί την κλάση Presentation
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // Επανάληψη στους CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Επανάληψη στα σχόλια
>          for (IComment comment1 : author.getComments())
>          {
>              Comment comment = (Comment) comment1;
>              System.out.println("ISlide :" + comment.getSlide().getSlideNumber() + " has comment: " + comment.getText() + " with Author: " + comment.getAuthor().getName() + " posted on time :" + comment.getCreatedTime().toString() + "\n");
>          }
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to add comments and get replies to them.
>  
>  // Αρχικοποιεί την κλάση Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Προσθέτει ένα σχόλιο
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      // Προσθέτει μια απάντηση στο comment1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Προσθέτει άλλη απάντηση στο comment1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Προσθέτει μια απάντηση σε υπάρχουσα απάντηση
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // Εμφανίζει την ιεραρχία των σχολίων στην κονσόλα
>      ISlide slide = pres.getSlides().get_Item(0);
>      IComment[] comments = slide.getSlideComments(null);
>      for (int i = 0; i < comments.length; i++)
>      {
>          IComment comment = comments[i];
>          while (comment.getParentComment() != null)
>          {
>              System.out.println("\t");
>              comment = comment.getParentComment();
>          }
>          System.out.println(comments[i].getAuthor().getName() + " : " + comments[i].getText());
>      }
>      pres.save("parent_comment.pptx",SaveFormat.Pptx);
>      // Αφαιρεί το comment1 και όλες τις απαντήσεις του
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getText()](#getText--) | Επιστρέφει ή θέτει το απλό κείμενο ενός σχολίου σε διαφάνεια. |
| [setText(String value)](#setText-java.lang.String-) | Επιστρέφει ή θέτει το απλό κείμενο ενός σχολίου σε διαφάνεια. |
| [getCreatedTime()](#getCreatedTime--) | Επιστρέφει ή θέτει την ώρα δημιουργίας ενός σχολίου. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Επιστρέφει ή θέτει την ώρα δημιουργίας ενός σχολίου. |
| [getSlide()](#getSlide--) | Επιστρέφει ή θέτει τη γονική διαφάνεια ενός σχολίου. |
| [getAuthor()](#getAuthor--) | Επιστρέφει το συγγραφέα ενός σχολίου. |
| [getPosition()](#getPosition--) | Επιστρέφει ή θέτει τη θέση ενός σχολίου σε διαφάνεια. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Επιστρέφει ή θέτει τη θέση ενός σχολίου σε διαφάνεια. |
| [remove()](#remove--) | Αφαιρεί το σχόλιο και όλες τις απαντήσεις του από τη γονική συλλογή. |
| [getParentComment()](#getParentComment--) | Λαμβάνει ή θέτει το γονικό σχόλιο. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Λαμβάνει ή θέτει το γονικό σχόλιο. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```

Επιστρέφει ή θέτει το απλό κείμενο ενός σχολίου σε διαφάνεια. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Επιστρέφει ή θέτει το απλό κείμενο ενός σχολίου σε διαφάνεια. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Επιστρέφει ή θέτει την ώρα δημιουργίας ενός σχολίου. Ορισμός αυτής της ιδιότητας σε java.util.Date(Long.MIN\_VALUE) σημαίνει ότι δεν έχει οριστεί ώρα σχολίου. Ανάγνωση/εγγραφή java.util.Date.

--------------------

Η ώρα σχολίου είναι προαιρετική παράμετρος.

**Επιστρέφει:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Επιστρέφει ή θέτει την ώρα δημιουργίας ενός σχολίου. Ορισμός αυτής της ιδιότητας σε java.util.Date(Long.MIN\_VALUE) σημαίνει ότι δεν έχει οριστεί ώρα σχολίου. Ανάγνωση/εγγραφή java.util.Date.

--------------------

Η ώρα σχολίου είναι προαιρετική παράμετρος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

Επιστρέφει ή θέτει τη γονική διαφάνεια ενός σχολίου. Μόνο για ανάγνωση [ISlide](../../com.aspose.slides/islide).

**Επιστρέφει:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

Επιστρέφει το συγγραφέα ενός σχολίου. Μόνο για ανάγνωση [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Επιστρέφει:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final Point2D.Float getPosition()
```

Επιστρέφει ή θέτει τη θέση ενός σχολίου σε διαφάνεια. Ανάγνωση/εγγραφή java.awt.geom.Point2D.Float.

**Επιστρέφει:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public final void setPosition(Point2D.Float value)
```

Επιστρέφει ή θέτει τη θέση ενός σχολίου σε διαφάνεια. Ανάγνωση/εγγραφή java.awt.geom.Point2D.Float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public final void remove()
```

Αφαιρεί το σχόλιο και όλες τις απαντήσεις του από τη γονική συλλογή.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

Λαμβάνει ή θέτει το γονικό σχόλιο. Ανάγνωση/εγγραφή [IComment](../../com.aspose.slides/icomment).

**Επιστρέφει:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

Λαμβάνει ή θέτει το γονικό σχόλιο. Ανάγνωση/εγγραφή [IComment](../../com.aspose.slides/icomment).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent\_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject