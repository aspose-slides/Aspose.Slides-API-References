---
title: Comment
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: स्लाइड पर टिप्पणी का प्रतिनिधित्व करता है।
type: docs
weight: 2620
url: /hi/aspose.slides/comment/
---
## टिप्पणी वर्ग

स्लाइड पर टिप्पणी का प्रतिनिधित्व करता है।

```csharp
public class Comment : IComment
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | टिप्पणी के लेखक को लौटाता है। केवल पढ़ने योग्य [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | टिप्पणी निर्माण का समय वापस देता है या सेट करता है। इस गुण को MinValue पर सेट करने का अर्थ है कि टिप्पणी का समय सेट नहीं है। पढ़ने/लिखने योग्य DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | पेरेंट टिप्पणी को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | स्लाइड पर टिप्पणी की स्थिति को वापस देता है या सेट करता है। पढ़ने/लिखने योग्य PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | टिप्पणी की पेरेंट स्लाइड को वापस देता है या सेट करता है। केवल पढ़ने योग्य [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | स्लाइड टिप्पणी का सामान्य पाठ वापस देता है या सेट करता है। पढ़ने/लिखने योग्य String. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | टिप्पणी और उसके सभी उत्तरों को पेरेंट संग्रह से हटाता है। |

### उदाहरण

यह उदाहरण दर्शाता है कि PowerPoint प्रस्तुति में स्लाइड पर टिप्पणी कैसे जोड़ें।

```csharp
[C#]
// Presentation क्लास का एक उदाहरण बनाता है
using (Presentation presentation = new Presentation())
{
    // एक खाली स्लाइड जोड़ता है
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // लेखक जोड़ता है
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // टिप्पणियों के लिए स्थिति सेट करता है
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // स्लाइड 1 पर लेखक के लिए स्लाइड टिप्पणी जोड़ता है
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // स्लाइड 2 पर लेखक के लिए स्लाइड टिप्पणी जोड़ता है
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// PowerPoint प्रस्तुति फ़ाइल को सहेजें
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

यह उदाहरण दर्शाता है कि PowerPoint प्रस्तुति में स्लाइड पर मौजूदा टिप्पणी कैसे एक्सेस करें।

```csharp
[C#]
// Presentation वर्ग का एक उदाहरण बनाता है
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// CommentAuthors को इटररेट करें
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Comments को इटररेट करें
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

यह उदाहरण दर्शाता है कि टिप्पणी कैसे जोड़ें और उनके उत्तर कैसे प्राप्त करें।

```csharp
[C#]
// Presentation क्लास का एक उदाहरण बनाता है
using (Presentation pres = new Presentation())
{
    // एक टिप्पणी जोड़ता है
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // comment1 के लिए उत्तर जोड़ता है
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // comment1 के लिए दूसरा उत्तर जोड़ता है
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // मौजूदा उत्तर के लिए एक उत्तर जोड़ता है
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // कंसोल पर टिप्पणियों की श्रृंखला दिखाता है
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
    // comment1 और उसके सभी उत्तरों को हटाता है
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### संबंधित देखें

* इंटरफ़ेस [IComment](../icomment)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* एसेम्बली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->