---
title: Comment
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: แสดงถึงความคิดเห็นบนสไลด์.
type: docs
weight: 2620
url: /th/aspose.slides/comment/
---
## คลาส Comment

แสดงถึงความคิดเห็นบนสไลด์

```csharp
public class Comment : IComment
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | คืนค่าผู้เขียนของความคิดเห็น อ่านอย่างเดียว [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | คืนค่า或กำหนดเวลาการสร้างความคิดเห็น การตั้งค่าคุณสมบัตินี้เป็น MinValue หมายความว่าไม่ได้กำหนดเวลาของความคิดเห็น อ่าน/เขียน DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | รับหรือกำหนดความคิดเห็นแม่ อ่าน/เขียน [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | คืนค่าหรือกำหนดตำแหน่งของความคิดเห็นบนสไลด์ อ่าน/เขียน PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | คืนค่าหรือกำหนดสไลด์แม่ของความคิดเห็น อ่านอย่างเดียว [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | คืนค่าหรือกำหนดข้อความธรรมดาของความคิดเห็นสไลด์ อ่าน/เขียน String. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | ลบความคิดเห็นและการตอบกลับทั้งหมดจากคอลเลกชันแม่. |

### ตัวอย่าง

ตัวอย่างนี้แสดงวิธีเพิ่มความคิดเห็นไปยังสไลด์ในงานนำเสนอ PowerPoint.

```csharp
[C#]
// สร้างอินสแตนซ์ของคลาส Presentation
using (Presentation presentation = new Presentation())
{
    // เพิ่มสไลด์เปล่า
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // เพิ่มผู้เขียน
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // กำหนดตำแหน่งของความคิดเห็น
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // เพิ่มความคิดเห็นสไลด์สำหรับผู้เขียนบนสไลด์ที่ 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // เพิ่มความคิดเห็นสไลด์สำหรับผู้เขียนบนสไลด์ที่ 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// บันทึกไฟล์งานนำเสนอ PowerPoint
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

ตัวอย่างนี้แสดงวิธีเข้าถึงความคิดเห็นที่มีอยู่บนสไลด์ในงานนำเสนอ PowerPoint.

```csharp
[C#]
// สร้างอินสแตนซ์ของคลาส Presentation
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// วนซ้ำ CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// วนซ้ำ Comments
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

ตัวอย่างนี้แสดงวิธีเพิ่มความคิดเห็นและรับการตอบกลับต่อความคิดเห็นเหล่านั้น.

```csharp
[C#]
// สร้างอินสแตนซ์ของคลาส Presentation
using (Presentation pres = new Presentation())
{
    // เพิ่มความคิดเห็น
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // เพิ่มการตอบกลับให้กับ comment1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // เพิ่มการตอบกลับอีกรายการให้กับ comment1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // เพิ่มการตอบกลับให้กับการตอบกลับที่มีอยู่
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // แสดงลำดับชั้นของความคิดเห็นบนคอนโซล
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
    // ลบ comment1 และการตอบกลับทั้งหมดของมัน
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IComment](../icomment)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->