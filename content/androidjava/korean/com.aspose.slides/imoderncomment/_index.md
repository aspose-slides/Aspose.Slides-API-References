---
title: IModernComment
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 슬라이드에 대한 주석을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imoderncomment/
---
**All Implemented Interfaces:**  
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

슬라이드에 대한 주석을 나타냅니다.

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
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getShape()](#getShape--) | 주석과 연결된 모양을 반환합니다. |
| [getTextSelectionStart()](#getTextSelectionStart--) | 주석이 AutoShape와 연결된 경우 텍스트 프레임에서 텍스트 선택의 시작 위치를 반환하거나 설정합니다. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | 주석이 AutoShape와 연결된 경우 텍스트 프레임에서 텍스트 선택의 시작 위치를 반환하거나 설정합니다. |
| [getTextSelectionLength()](#getTextSelectionLength--) | 주석이 AutoShape와 연결된 경우 텍스트 프레임에서 텍스트 선택 길이를 반환하거나 설정합니다. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | 주석이 AutoShape와 연결된 경우 텍스트 프레임에서 텍스트 선택 길이를 반환하거나 설정합니다. |
| [getStatus()](#getStatus--) | 주석의 상태를 반환하거나 설정합니다. |
| [setStatus(byte value)](#setStatus-byte-) | 주석의 상태를 반환하거나 설정합니다. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```

주석과 연결된 모양을 반환합니다. 읽기 전용 [IShape](../../com.aspose.slides/ishape).

**반환값:**  
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

주석이 AutoShape와 연결된 경우 텍스트 프레임에서 텍스트 선택의 시작 위치를 반환하거나 설정합니다. 읽기/쓰기 int.

**반환값:**  
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

주석이 AutoShape와 연결된 경우 텍스트 프레임에서 텍스트 선택의 시작 위치를 반환하거나 설정합니다. 읽기/쓰기 int.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

주석이 AutoShape와 연결된 경우 텍스트 프레임에서 텍스트 선택 길이를 반환하거나 설정합니다. 읽기/쓰기 int.

**반환값:**  
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```

주석이 AutoShape와 연결된 경우 텍스트 프레임에서 텍스트 선택 길이를 반환하거나 설정합니다. 읽기/쓰기 int.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

주석의 상태를 반환하거나 설정합니다. 읽기/쓰기 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**반환값:**  
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

주석의 상태를 반환하거나 설정합니다. 읽기/쓰기 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |