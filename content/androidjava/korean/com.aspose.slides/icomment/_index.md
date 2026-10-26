---
title: IComment
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a comment on a slide.
type: docs
url: /ko/com.aspose.slides/icomment/
---```
public interface IComment
```

슬라이드에 대한 댓글을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getText()](#getText--) | 슬라이드 댓글의 일반 텍스트를 반환하거나 설정합니다. |
| [setText(String value)](#setText-java.lang.String-) | 슬라이드 댓글의 일반 텍스트를 반환하거나 설정합니다. |
| [getCreatedTime()](#getCreatedTime--) | 댓글 생성 시간을 반환하거나 설정합니다. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | 댓글 생성 시간을 반환하거나 설정합니다. |
| [getSlide()](#getSlide--) | 댓글의 상위 슬라이드를 반환하거나 설정합니다. |
| [getAuthor()](#getAuthor--) | 댓글의 작성자를 반환합니다. |
| [getPosition()](#getPosition--) | 슬라이드에서 댓글 위치를 반환하거나 설정합니다. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | 슬라이드에서 댓글 위치를 반환하거나 설정합니다. |
| [remove()](#remove--) | 댓글과 모든 응답을 상위 컬렉션에서 제거합니다. |
| [getParentComment()](#getParentComment--) | 상위 댓글을 가져오거나 설정합니다. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | 상위 댓글을 가져오거나 설정합니다. |
### getText() {#getText--}
```
public abstract String getText()
```

슬라이드 댓글의 일반 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

슬라이드 댓글의 일반 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

댓글 생성 시간을 반환하거나 설정합니다. 이 속성을 java.util.Date(Long.MIN\_VALUE) 로 설정하면 댓글 시간이 설정되지 않은 것입니다. 읽기/쓰기 java.util.Date.

--------------------

댓글 시간은 선택 매개변수입니다.

**반환값:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

댓글 생성 시간을 반환하거나 설정합니다. 이 속성을 java.util.Date(Long.MIN\_VALUE) 로 설정하면 댓글 시간이 설정되지 않은 것입니다. 읽기/쓰기 java.util.Date.

--------------------

댓글 시간은 선택 매개변수입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

댓글의 상위 슬라이드를 반환하거나 설정합니다. 읽기 전용 [ISlide](../../com.aspose.slides/islide).

**반환값:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

댓글의 작성자를 반환합니다. 읽기 전용 [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**반환값:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```

슬라이드에서 댓글 위치를 반환하거나 설정합니다. 읽기/쓰기 android.graphics.PointF.

**반환값:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

슬라이드에서 댓글 위치를 반환하거나 설정합니다. 읽기/쓰기 android.graphics.PointF.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public abstract void remove()
```

댓글과 모든 응답을 상위 컬렉션에서 제거합니다.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

상위 댓글을 가져오거나 설정합니다. 읽기/쓰기 [IComment](../../com.aspose.slides/icomment).

**반환값:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

상위 댓글을 가져오거나 설정합니다. 읽기/쓰기 [IComment](../../com.aspose.slides/icomment).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |