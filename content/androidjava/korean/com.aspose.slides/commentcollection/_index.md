---
title: CommentCollection
second_title: Aspose.Slides for Android Java API 참조
description: 한 저자의 댓글 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/commentcollection/
---
**상속:**
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

한 저자의 댓글 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | 컬렉션 끝에 새 댓글을 추가합니다. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | 컬렉션 끝에 새 최신 댓글을 추가합니다. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | 지정된 인덱스에 새 댓글을 컬렉션에 삽입합니다. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | 지정된 인덱스에 새 최신 댓글을 컬렉션에 삽입합니다. |
| [toArray()](#toArray--) | 모든 댓글을 포함하는 배열을 생성하고 반환합니다. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 지정된 범위의 모든 댓글을 포함하는 배열을 생성하고 반환합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 지정된 인덱스의 요소를 제거합니다. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | 컬렉션에서 지정된 댓글의 첫 번째 발생을 제거합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 댓글을 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | 인덱스로 컬렉션에서 댓글을 찾습니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되는지를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
### size() {#size--}
```
public final int size()
```

컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용  int .

**반환:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [Comment](../../com.aspose.slides/comment).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

컬렉션 끝에 새 댓글을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 새 댓글의 일반 텍스트. |
| slide | [ISlide](../../com.aspose.slides/islide) | 새 댓글을 추가할 프레젠테이션의 슬라이드. |
| position | android.graphics.PointF | 새 댓글을 추가할 슬라이드상의 위치. |
| creationTime | java.util.Date | 댓글 생성 시간. |

**반환:**
[IComment](../../com.aspose.slides/icomment) - 추가된 댓글.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

컬렉션 끝에 새 최신 댓글을 추가합니다.

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
| text | java.lang.String | 새 최신 댓글의 일반 텍스트. |
| slide | [ISlide](../../com.aspose.slides/islide) | 새 최신 댓글을 추가할 프레젠테이션의 슬라이드. |
| shape | [IShape](../../com.aspose.slides/ishape) | 새 최신 댓글이 연결된 슬라이드의 도형. |
| position | android.graphics.PointF | 새 최신 댓글을 추가할 슬라이드상의 위치. |
| creationTime | java.util.Date | 최신 댓글 생성 시간. |

**반환:**
[IModernComment](../../com.aspose.slides/imoderncomment) - 추가된 최신 댓글.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

지정된 인덱스에 새 댓글을 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 댓글이 삽입될 컬렉션 내 요소의 인덱스. |
| text | java.lang.String | 새 댓글의 일반 텍스트. |
| slide | [ISlide](../../com.aspose.slides/islide) | 새 댓글을 추가할 프레젠테이션의 슬라이드. |
| position | android.graphics.PointF | 새 댓글을 추가할 슬라이드상의 위치. |
| creationTime | java.util.Date | 댓글 생성 시간. |

**반환:**
[IComment](../../com.aspose.slides/icomment) - 삽입된 댓글.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

지정된 인덱스에 새 최신 댓글을 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 최신 댓글이 삽입될 컬렉션 내 요소의 인덱스. |
| text | java.lang.String | 새 최신 댓글의 일반 텍스트. |
| slide | [ISlide](../../com.aspose.slides/islide) | 새 최신 댓글을 추가할 프레젠테이션의 슬라이드. |
| shape | [IShape](../../com.aspose.slides/ishape) | 새 최신 댓글이 연결된 슬라이드의 도형. |
| position | android.graphics.PointF | 새 최신 댓글을 추가할 슬라이드상의 위치. |
| creationTime | java.util.Date | 최신 댓글 생성 시간. |

**반환:**
[IModernComment](../../com.aspose.slides/imoderncomment) - 삽입된 최신 댓글.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```

모든 댓글을 포함하는 배열을 생성하고 반환합니다.

**반환:**
com.aspose.slides.IComment[] - [Comment](../../com.aspose.slides/comment)의 배열.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

지정된 범위의 모든 댓글을 포함하는 배열을 생성하고 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | int | 반환할 첫 번째 댓글의 인덱스. |
| count | int | 반환할 댓글 수. |

**반환:**
com.aspose.slides.IComment[] - [Comment](../../com.aspose.slides/comment)의 배열.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

컬렉션에서 지정된 인덱스의 요소를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0부터 시작하는 인덱스. |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

컬렉션에서 지정된 댓글의 첫 번째 발생을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | 컬렉션에서 제거할 댓글. |
### clear() {#clear--}
```
public final void clear()
```

컬렉션에서 모든 댓글을 제거합니다.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

전체 컬렉션에 대한 java iterator를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - 전체 컬렉션에 대한 java.util.Iterator.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

인덱스로 컬렉션에서 댓글을 찾습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| idx | int | 찾을 댓글의 고유 인덱스 int . |

**반환:**
[IComment](../../com.aspose.slides/icomment) - 찾은 댓글 또는 null [IComment](../../com.aspose.slides/icomment).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열의 시작 인덱스. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

컬렉션에 대한 접근이 동기화(스레드 안전)되는지를 나타내는 값을 반환합니다. 읽기 전용  boolean .

**반환:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. 읽기 전용  Object .

**반환:**
java.lang.Object