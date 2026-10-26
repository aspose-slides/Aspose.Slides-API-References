---
title: ModernComment
second_title: Aspose.Slides for Java API 레퍼런스
description: 슬라이드에 대한 주석을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/moderncomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**All Implemented Interfaces:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

슬라이드에 대한 주석을 나타냅니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getShape()](#getShape--) | 주석과 연결된 도형을 반환합니다. |
| [getTextSelectionStart()](#getTextSelectionStart--) | 자동 도형과 연결된 주석의 경우 텍스트 프레임에서 텍스트 선택 시작 위치를 가져오거나 설정합니다. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | 자동 도형과 연결된 주석의 경우 텍스트 프레임에서 텍스트 선택 시작 위치를 가져오거나 설정합니다. |
| [getTextSelectionLength()](#getTextSelectionLength--) | 자동 도형과 연결된 주석의 경우 텍스트 프레임에서 텍스트 선택 길이를 가져오거나 설정합니다. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | 자동 도형과 연결된 주석의 경우 텍스트 프레임에서 텍스트 선택 길이를 가져오거나 설정합니다. |
| [getStatus()](#getStatus--) | 주석의 상태를 가져오거나 설정합니다. |
| [setStatus(byte value)](#setStatus-byte-) | 주석의 상태를 가져오거나 설정합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```


주석과 연결된 도형을 반환합니다. 읽기 전용 [IShape](../../com.aspose.slides/ishape).

**반환:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```


자동 도형과 연결된 주석의 경우 텍스트 프레임에서 텍스트 선택 시작 위치를 가져오거나 설정합니다. 읽기/쓰기 int.

**반환:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```


자동 도형과 연결된 주석의 경우 텍스트 프레임에서 텍스트 선택 시작 위치를 가져오거나 설정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```


자동 도형과 연결된 주석의 경우 텍스트 프레임에서 텍스트 선택 길이를 가져오거나 설정합니다. 읽기/쓰기 int.

**반환:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```


자동 도형과 연결된 주석의 경우 텍스트 프레임에서 텍스트 선택 길이를 가져오거나 설정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```


주석의 상태를 가져오거나 설정합니다. 읽기/쓰기 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**반환:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```


주석의 상태를 가져오거나 설정합니다. 읽기/쓰기 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate 개체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**
com.aspose.slides.IDOMObject