---
title: Comment
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: स्लाइड पर एक टिप्पणी का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/comment/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

स्लाइड पर एक टिप्पणी का प्रतिनिधित्व करता है।

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Presentation क्लास का उदाहरण बनाता है
>  Presentation presentation = new Presentation();
>  try {
>     // एक खाली स्लाइड जोड़ता है
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // एक लेखक जोड़ता है
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // टिपण्णियों के लिए स्थिति सेट करता है
>      android.graphics.PointF point = new android.graphics.PointF();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // स्लाइड 1 पर लेखक के लिए स्लाइड टिप्पणी जोड़ता है
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // स्लाइड 2 पर लेखक के लिए स्लाइड टिप्पणी जोड़ता है
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// PowerPoint Presentation फ़ाइल सहेजें
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Presentation क्लास का उदाहरण बनाता है
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // CommentAuthors पर इटरेट करें
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // टिप्पणियों पर इटरेट करें
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
>  // Presentation क्लास का उदाहरण बनाता है
>  Presentation pres = new Presentation();
>  try {
>     // एक टिप्पणी जोड़ता है
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      // comment1 के लिए उत्तर जोड़ता है
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // comment1 के लिए दूसरा उत्तर जोड़ता है
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // मौज़ूदा उत्तर के लिए उत्तर जोड़ता है
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // कंसोल पर टिप्पणी पदानुक्रम प्रदर्शित करता है
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
>      // comment1 और सभी उत्तर हटाता है
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getText()](#getText--) | स्लाइड टिप्पणी का साधारण पाठ लौटाता या सेट करता है। |
| [setText(String value)](#setText-java.lang.String-) | स्लाइड टिप्पणी का साधारण पाठ लौटाता या सेट करता है। |
| [getCreatedTime()](#getCreatedTime--) | टिप्पणी निर्माण का समय लौटाता या सेट करता है। |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | टिप्पणी निर्माण का समय लौटाता या सेट करता है। |
| [getSlide()](#getSlide--) | टिप्पणी का मूल स्लाइड लौटाता या सेट करता है। |
| [getAuthor()](#getAuthor--) | टिप्पणी के लेखक को लौटाता है। |
| [getPosition()](#getPosition--) | स्लाइड पर टिप्पणी की स्थिति लौटाता या सेट करता है। |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | स्लाइड पर टिप्पणी की स्थिति लौटाता या सेट करता है। |
| [remove()](#remove--) | टिप्पणी और उसकी सभी प्रतिक्रियाओं को मूल संग्रह से हटाता है। |
| [getParentComment()](#getParentComment--) | मूल टिप्पणी को प्राप्त या सेट करता है। |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | मूल टिप्पणी को प्राप्त या सेट करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```


स्लाइड टिप्पणी का साधारण पाठ लौटाता या सेट करता है। पढ़ने/लिखने योग्य String।

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


स्लाइड टिप्पणी का साधारण पाठ लौटाता या सेट करता है। पढ़ने/लिखने योग्य String।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```


टिप्पणी निर्माण का समय लौटाता या सेट करता है। इस प्रॉपर्टी को java.util.Date(Long.MIN_VALUE) पर सेट करने का अर्थ है कोई टिप्पणी समय निर्धारित नहीं है। पढ़ने/लिखने योग्य java.util.Date।

--------------------

टिप्पणी समय एक वैकल्पिक पैरामीटर है।

**Returns:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


टिप्पणी निर्माण का समय लौटाता या सेट करता है। इस प्रॉपर्टी को java.util.Date(Long.MIN_VALUE) पर सेट करने का अर्थ है कोई टिप्पणी समय निर्धारित नहीं है। पढ़ने/लिखने योग्य java.util.Date।

--------------------

टिप्पणी समय एक वैकल्पिक पैरामीटर है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```


टिप्पणी के मूल स्लाइड को लौटाता या सेट करता है। केवल-पढ़ने योग्य [ISlide](../../com.aspose.slides/islide)।

**Returns:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```


टिप्पणी के लेखक को लौटाता है। केवल-पढ़ने योग्य [ICommentAuthor](../../com.aspose.slides/icommentauthor)।

**Returns:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final PointF getPosition()
```


स्लाइड पर टिप्पणी की स्थिति लौटाता या सेट करता है। पढ़ने/लिखने योग्य android.graphics.PointF।

**Returns:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```


स्लाइड पर टिप्पणी की स्थिति लौटाता या सेट करता है। पढ़ने/लिखने योग्य android.graphics.PointF।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public final void remove()
```


टिप्पणी और उसकी सभी प्रतिक्रियाओं को मूल संग्रह से हटाता है।

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```


मूल टिप्पणी को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य [IComment](../../com.aspose.slides/icomment)।

**Returns:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```


मूल टिप्पणी को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य [IComment](../../com.aspose.slides/icomment)।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**Returns:**
com.aspose.slides.IDOMObject