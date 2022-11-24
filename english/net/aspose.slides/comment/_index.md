---
title: Comment
second_title: Aspose.Sildes for .NET API Reference
description: Represents a comment on a slide.
type: docs
weight: 2490
url: /net/aspose.slides/comment/
---
## Comment class

Represents a comment on a slide.

```csharp
public class Comment : IComment
```

## Properties

| Name | Description |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Returns the author of a comment. Read-only [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Returns or sets the time of a comment creation. Setting this property to MinValue means no comment time is set. Read/write DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Gets or sets parent comment. Read/write [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Returns or sets the position of a comment on a slide. Read/write PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Returns or sets the parent slide of a comment. Read-only [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Returns or sets the plain text of a slide comment. Read/write String. |

## Methods

| Name | Description |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Removes comment and all its replies from the parent collection. |

## Examples

This example shows you how to add a comment to a slide in a PowerPoint presentation.

```csharp
[C#]
// Instantiates the Presentation class
using (Presentation presentation = new Presentation())
{
    // Adds an empty slide
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);

    // Adds an author
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");

    // Sets the position for comments
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;

    // Adds slide comment for an author on slide 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);

    // Adds slide comment for an author on slide 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	
	// Save the PowerPoint Presentation file
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);

}
```

This example shows you how to access an existing comment on a slide in a PowerPoint presentation.

```csharp
[C#]
// Instantiates the Presentation class
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Iterate CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Iterate Comments
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

This example shows you how to add comments and get replies to them.

```csharp
[C#]
// Instantiates the Presentation class
using (Presentation pres = new Presentation())
{
    // Adds a comment
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);

    // Adds a reply to comment1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;

    // Adds another reply to comment1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;

    // Adds a reply to existing reply
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;

    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);

    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;

    // Displays the comments hierarchy on console
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

    // Removes comment1 and all replies to it
    comment1.Remove();

    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [IComment](../icomment)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
