---
title: Comment
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αναπαριστά ένα σχόλιο σε μια διαφάνεια.
type: docs
weight: 2640
url: /el/aspose.slides/comment/
---
## Κλάση Comment

Αναπαριστά ένα σχόλιο σε μια διαφάνεια.

```csharp
public class Comment : IComment
```

## Ιδιότητες

| Name | Description |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Επιστρέφει τον συγγραφέα ενός σχολίου. Μόνο ανάγνωση [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Επιστρέφει ή ορίζει την ώρα δημιουργίας ενός σχολίου. Ορισμός αυτής της ιδιότητας σε MinValue σημαίνει ότι δεν έχει οριστεί ώρα σχολίου. Ανάγνωση/εγγραφή DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Παίρνει ή ορίζει το γονικό σχόλιο. Ανάγνωση/εγγραφή [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Επιστρέφει ή ορίζει τη θέση ενός σχολίου σε μια διαφάνεια. Ανάγνωση/εγγραφή PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Επιστρέφει ή ορίζει τη γονική διαφάνεια ενός σχολίου. Μόνο ανάγνωση [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Επιστρέφει ή ορίζει το καθαρό κείμενο ενός σχολίου διαφάνειας. Ανάγνωση/εγγραφή String. |

## Μέθοδοι

| Name | Description |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Αφαιρεί το σχόλιο και όλες τις απαντήσεις του από τη γονική συλλογή. |

### Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να προσθέσετε ένα σχόλιο σε μια διαφάνεια σε παρουσίαση PowerPoint.

```csharp
[C#]
// Δημιουργεί αντικείμενο της κλάσης Presentation
using (Presentation presentation = new Presentation())
{
    // Προσθέτει μια κενή διαφάνεια
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // Προσθέτει έναν συγγραφέα
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // Ορίζει τη θέση για τα σχόλια
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // Προσθέτει σχόλιο διαφάνειας για έναν συγγραφέα στη διαφάνεια 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Προσθέτει σχόλιο διαφάνειας για έναν συγγραφέα στη διαφάνεια 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// Αποθηκεύει το αρχείο παρουσίασης PowerPoint
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Αυτό το παράδειγμα δείχνει πώς να αποκτήσετε πρόσβαση σε ένα υπάρχον σχόλιο σε μια διαφάνεια σε παρουσίαση PowerPoint.

```csharp
[C#]
// Δημιουργεί αντικείμενο της κλάσης Presentation
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Επανάληψη στους CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Επανάληψη στα Comments
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Αυτό το παράδειγμα δείχνει πώς να προσθέσετε σχόλια και να λάβετε απαντήσεις σε αυτά.

```csharp
[C#]
// Δημιουργεί αντικείμενο της κλάσης Presentation
using (Presentation pres = new Presentation())
{
    // Προσθέτει ένα σχόλιο
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Προσθέτει απάντηση στο comment1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Προσθέτει άλλη απάντηση στο comment1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Προσθέτει απάντηση σε υπάρχουσα απάντηση
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Εμφανίζει την ιεραρχία των σχολίων στην κονσόλα
    ISlide slide = pres.Slides[0];
    var comments = slide.GetSlideComments(null);
    for (int i = 0; i < comments.Length; i++)
    {
        IComment comment = comments[i];
        while (comment.ParentComment != null)
        {
            Console.Write("\t");
            comment = comment.ParentComment;
        }
        Console.Write("{0} : {1}", comments[i].Author.Name, comments[i].Text);
        Console.WriteLine();
    }
    pres.Save("parent_comment.pptx",SaveFormat.Pptx);
    // Αφαιρεί το comment1 και όλες τις απαντήσεις του
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Δείτε επίσης

* Διεπαφή [IComment](../icomment)
* Χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* Συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->