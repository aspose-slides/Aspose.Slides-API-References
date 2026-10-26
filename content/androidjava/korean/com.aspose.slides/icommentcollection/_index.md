---
title: ICommentCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 한 작성자의 댓글 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icommentcollection/
---
**모든 구현된 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

한 작성자의 댓글 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | 컬렉션 끝에 새 댓글을 추가합니다. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | 컬렉션 끝에 새 현대 댓글을 추가합니다. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | 지정된 인덱스에 새 댓글을 컬렉션에 삽입합니다. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | 지정된 인덱스에 새 현대 댓글을 컬렉션에 삽입합니다. |
| [toArray()](#toArray--) | 모든 댓글을 포함하는 배열을 생성하고 반환합니다. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 지정된 범위의 모든 댓글을 포함하는 배열을 생성하고 반환합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | 컬렉션에서 지정된 댓글의 첫 번째 발생을 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 댓글을 제거합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```


지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [IComment](../../com.aspose.slides/icomment).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```


컬렉션의 끝에 새 댓글을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 새 댓글의 평문 텍스트. |
| slide | [ISlide](../../com.aspose.slides/islide) | 새 댓글을 추가할 프레젠테이션의 슬라이드. |
| position | android.graphics.PointF | 새 댓글을 추가할 슬라이드상의 위치. |
| creationTime | java.util.Date | 댓글 생성 시간. |

**반환값:**
[IComment](../../com.aspose.slides/icomment) - 추가된 댓글.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


컬렉션의 끝에 새 현대 댓글을 추가합니다.

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


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 새 현대 댓글의 평문 텍스트. |
| slide | [ISlide](../../com.aspose.slides/islide) | 새 현대 댓글을 추가할 프레젠테이션의 슬라이드. |
| shape | [IShape](../../com.aspose.slides/ishape) | 새 현대 댓글이 연결된 슬라이드상의 도형. |
| position | android.graphics.PointF | 새 현대 댓글을 추가할 슬라이드상의 위치. |
| creationTime | java.util.Date | 현대 댓글 생성 시간. |

**반환값:**
[IModernComment](../../com.aspose.slides/imoderncomment) - 추가된 현대 댓글.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```


지정된 인덱스에 새 댓글을 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 댓글을 삽입할 컬렉션 내 요소의 인덱스. |
| text | java.lang.String | 새 댓글의 평문 텍스트. |
| slide | [ISlide](../../com.aspose.slides/islide) | 새 댓글을 추가할 프레젠테이션의 슬라이드. |
| position | android.graphics.PointF | 새 댓글을 추가할 슬라이드상의 위치. |
| creationTime | java.util.Date | 댓글 생성 시간. |

**반환값:**
[IComment](../../com.aspose.slides/icomment) - 삽입된 댓글.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


지정된 인덱스에 새 현대 댓글을 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 현대 댓글을 삽입할 컬렉션 내 요소의 인덱스. |
| text | java.lang.String | 새 현대 댓글의 평문 텍스트. |
| slide | [ISlide](../../com.aspose.slides/islide) | 새 현대 댓글을 추가할 프레젠테이션의 슬라이드. |
| shape | [IShape](../../com.aspose.slides/ishape) | 새 현대 댓글이 연결된 슬라이드상의 도형. |
| position | android.graphics.PointF | 새 현대 댓글을 추가할 슬라이드상의 위치. |
| creationTime | java.util.Date | 현대 댓글 생성 시간. |

**반환값:**
[IModernComment](../../com.aspose.slides/imoderncomment) - 삽입된 현대 댓글.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```


모든 댓글을 포함하는 배열을 생성하고 반환합니다.

**반환값:**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment)의 배열.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```


지정된 범위의 모든 댓글을 포함하는 배열을 생성하고 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | int | 반환할 첫 번째 댓글의 인덱스. |
| count | int | 반환할 댓글 수. |

**반환값:**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment)의 배열.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0부터 시작하는 인덱스. |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```


컬렉션에서 지정된 댓글의 첫 번째 발생을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | 컬렉션에서 제거할 댓글. |
### clear() {#clear--}
```
public abstract void clear()
```


컬렉션의 모든 댓글을 제거합니다.