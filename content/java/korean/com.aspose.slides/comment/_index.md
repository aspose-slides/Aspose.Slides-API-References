---
title: Comment
second_title: Aspose.Slides Java API 레퍼런스
description: 슬라이드에 대한 주석을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/comment/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

슬라이드에 대한 주석을 나타냅니다.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Presentation 클래스를 인스턴스화합니다
>  Presentation presentation = new Presentation();
>  try {
>     // 빈 슬라이드를 추가합니다
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // 작성자를 추가합니다
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // 주석 위치를 설정합니다
>      Point2D.Float point = new Point2D.Float();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // 슬라이드 1에 작성자를 위한 슬라이드 주석을 추가합니다
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // 슬라이드 2에 작성자를 위한 슬라이드 주석을 추가합니다
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// PowerPoint 프레젠테이션 파일을 저장합니다
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Presentation 클래스를 인스턴스화합니다
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // CommentAuthors 를 순회합니다
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Comments 를 순회합니다
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
>  // Presentation 클래스를 인스턴스화합니다
>  Presentation pres = new Presentation();
>  try {
>     // 주석을 추가합니다
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      // comment1에 대한 답글을 추가합니다
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // comment1에 대한 또 다른 답글을 추가합니다
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // 기존 답글에 대한 답글을 추가합니다
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // 콘솔에 주석 계층 구조를 표시합니다
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
>      // comment1 및 그 모든 답글을 삭제합니다
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getText()](#getText--) | 슬라이드 주석의 일반 텍스트를 반환하거나 설정합니다. |
| [setText(String value)](#setText-java.lang.String-) | 슬라이드 주석의 일반 텍스트를 반환하거나 설정합니다. |
| [getCreatedTime()](#getCreatedTime--) | 주석 생성 시간을 반환하거나 설정합니다. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | 주석 생성 시간을 반환하거나 설정합니다. |
| [getSlide()](#getSlide--) | 주석의 상위 슬라이드를 반환하거나 설정합니다. |
| [getAuthor()](#getAuthor--) | 주석의 작성자를 반환합니다. |
| [getPosition()](#getPosition--) | 슬라이드에서 주석의 위치를 반환하거나 설정합니다. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | 슬라이드에서 주석의 위치를 반환하거나 설정합니다. |
| [remove()](#remove--) | 주석과 그 모든 답글을 상위 컬렉션에서 삭제합니다. |
| [getParentComment()](#getParentComment--) | 상위 주석을 가져오거나 설정합니다. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | 상위 주석을 가져오거나 설정합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getText() {#getText--}
```
public final String getText()
```

슬라이드 주석의 일반 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

슬라이드 주석의 일반 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

주석 생성 시간을 반환하거나 설정합니다. 이 속성을 java.util.Date(Long.MIN\_VALUE) 로 설정하면 주석 시간이 설정되지 않은 것입니다. 읽기/쓰기 java.util.Date.

--------------------

주석 시간은 선택적 매개변수입니다.

**반환값:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

주석 생성 시간을 반환하거나 설정합니다. 이 속성을 java.util.Date(Long.MIN\_VALUE) 로 설정하면 주석 시간이 설정되지 않은 것입니다. 읽기/쓰기 java.util.Date.

--------------------

주석 시간은 선택적 매개변수입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

주석의 상위 슬라이드를 반환하거나 설정합니다. 읽기 전용 [ISlide](../../com.aspose.slides/islide).

**반환값:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

주석의 작성자를 반환합니다. 읽기 전용 [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**반환값:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final Point2D.Float getPosition()
```

슬라이드에서 주석의 위치를 반환하거나 설정합니다. 읽기/쓰기 java.awt.geom.Point2D.Float.

**반환값:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public final void setPosition(Point2D.Float value)
```

슬라이드에서 주석의 위치를 반환하거나 설정합니다. 읽기/쓰기 java.awt.geom.Point2D.Float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public final void remove()
```

주석과 그 모든 답글을 상위 컬렉션에서 삭제합니다.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

상위 주석을 가져오거나 설정합니다. 읽기/쓰기 [IComment](../../com.aspose.slides/icomment).

**반환값:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

상위 주석을 가져오거나 설정합니다. 읽기/쓰기 [IComment](../../com.aspose.slides/icomment).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject