---
title: Comment
second_title: Java API リファレンスによる Aspose.Slides for Android
description: スライド上のコメントを表します。
type: docs
url: /ja/com.aspose.slides/comment/
---
**継承:**
java.lang.Object

**実装インターフェイス:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

スライド上のコメントを表します。

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Presentation クラスのインスタンスを作成します
>  Presentation presentation = new Presentation();
>  try {
>     // 空のスライドを追加します
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // 作成者を追加します
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // コメントの位置を設定します
>      android.graphics.PointF point = new android.graphics.PointF();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // スライド 1 の作成者に対してスライドコメントを追加します
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // スライド 2 の作成者に対してスライドコメントを追加します
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// PowerPoint プレゼンテーションファイルを保存します
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Presentation クラスのインスタンスを作成します
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // CommentAuthors を列挙します
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Comments を列挙します
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
>  // Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation();
>  try {
>     // コメントを追加します
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      // comment1 に対する返信を追加します
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // comment1 に対する別の返信を追加します
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // 既存の返信に対する返信を追加します
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // コンソールにコメント階層を表示します
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
>      // comment1 とそれへのすべての返信を削除します
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getText()](#getText--) | スライドコメントのプレーンテキストを取得または設定します。 |
| [setText(String value)](#setText-java.lang.String-) | スライドコメントのプレーンテキストを取得または設定します。 |
| [getCreatedTime()](#getCreatedTime--) | コメント作成時刻を取得または設定します。 |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | コメント作成時刻を取得または設定します。 |
| [getSlide()](#getSlide--) | コメントの親スライドを取得または設定します。 |
| [getAuthor()](#getAuthor--) | コメントの作成者を取得します。 |
| [getPosition()](#getPosition--) | スライド上のコメントの位置を取得または設定します。 |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | スライド上のコメントの位置を取得または設定します。 |
| [remove()](#remove--) | コメントとそのすべての返信を親コレクションから削除します。 |
| [getParentComment()](#getParentComment--) | 親コメントを取得または設定します。 |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | 親コメントを取得または設定します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```

スライドコメントのプレーンテキストを取得または設定します。読み取り/書き込み String.

**戻り値:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

スライドコメントのプレーンテキストを取得または設定します。読み取り/書き込み String.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

コメント作成時刻を取得または設定します。このプロパティを java.util.Date(Long.MIN_VALUE) に設定すると、コメント時刻が設定されていないことを意味します。読み取り/書き込み java.util.Date.

--------------------

コメント時間はオプションのパラメータです。

**戻り値:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

コメント作成時刻を取得または設定します。このプロパティを java.util.Date(Long.MIN_VALUE) に設定すると、コメント時刻が設定されていないことを意味します。読み取り/書き込み java.util.Date.

--------------------

コメント時間はオプションのパラメータです。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

コメントの親スライドを取得または設定します。読み取り専用 [ISlide](../../com.aspose.slides/islide).

**戻り値:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

コメントの作成者を取得します。読み取り専用 [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**戻り値:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final PointF getPosition()
```

スライド上のコメントの位置を取得または設定します。読み取り/書き込み android.graphics.PointF.

**戻り値:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```

スライド上のコメントの位置を取得または設定します。読み取り/書き込み android.graphics.PointF.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public final void remove()
```

コメントとそのすべての返信を親コレクションから削除します。

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

親コメントを取得または設定します。読み取り/書き込み [IComment](../../com.aspose.slides/icomment).

**戻り値:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

親コメントを取得または設定します。読み取り/書き込み [IComment](../../com.aspose.slides/icomment).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを取得します。読み取り専用 IDOMObject.

**戻り値:**
com.aspose.slides.IDOMObject