---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides for Java API 레퍼런스
description: 내보낸 문서에서 노트와 주석의 레이아웃 모양을 제어하는 옵션을 제공합니다.
type: docs
url: /ko/com.aspose.slides/notescommentslayoutingoptions/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)  
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

내보낸 문서에서 노트와 주석의 레이아웃 모양을 제어하는 옵션을 제공합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | 기본 생성자. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | 작성자가 없는 주석의 표시 여부를 가져오거나 설정합니다. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | 작성자가 없는 주석의 표시 여부를 가져오거나 설정합니다. |
| [getNotesPosition()](#getNotesPosition--) | 페이지의 노트 위치를 가져오거나 설정합니다. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | 페이지의 노트 위치를 가져오거나 설정합니다. |
| [getCommentsPosition()](#getCommentsPosition--) | 페이지의 주석 위치를 가져오거나 설정합니다. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | 페이지의 주석 위치를 가져오거나 설정합니다. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | 주석 영역의 색상을 가져오거나 설정합니다(주석이 오른쪽에 표시되는 경우에만 적용됩니다). |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | 주석 영역의 색상을 가져오거나 설정합니다(주석이 오른쪽에 표시되는 경우에만 적용됩니다). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | 주석 출력 영역의 너비를 픽셀 단위로 가져오거나 설정합니다(주석이 오른쪽에 표시되는 경우에만 적용됩니다). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | 주석 출력 영역의 너비를 픽셀 단위로 가져오거나 설정합니다(주석이 오른쪽에 표시되는 경우에만 적용됩니다). |

### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

기본 생성자.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

작성자가 없는 주석의 표시 여부를 가져오거나 설정합니다. true인 경우 주석이 표시됩니다(주석이 표시되는 경우에만 적용됩니다).

--------------------

기본값은 **false**입니다.

**반환값:**  
boolean

### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

작성자가 없는 주석의 표시 여부를 가져오거나 설정합니다. true인 경우 주석이 표시됩니다(주석이 표시되는 경우에만 적용됩니다).

--------------------

기본값은 **false**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

페이지의 노트 위치를 가져오거나 설정합니다.

--------------------

기본값은 **NotesPositions.None**입니다.

**반환값:**  
int

### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

페이지의 노트 위치를 가져오거나 설정합니다.

--------------------

기본값은 **NotesPositions.None**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

페이지의 주석 위치를 가져오거나 설정합니다.

--------------------

기본값은 **CommentsPositions.None**입니다.

**반환값:**  
int

### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

페이지의 주석 위치를 가져오거나 설정합니다.

--------------------

기본값은 **CommentsPositions.None**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```

주석 영역의 색상을 가져오거나 설정합니다(주석이 오른쪽에 표시되는 경우에만 적용됩니다).

--------------------

기본값은 **Color.SkyBlue**입니다.

**반환값:**  
java.awt.Color

### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```

주석 영역의 색상을 가져오거나 설정합니다(주석이 오른쪽에 표시되는 경우에만 적용됩니다).

--------------------

기본값은 **Color.SkyBlue**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

주석 출력 영역의 너비를 픽셀 단위로 가져오거나 설정합니다(주석이 오른쪽에 표시되는 경우에만 적용됩니다).

--------------------

최소 및 기본값은 **150**입니다.

**반환값:**  
int

### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

주석 출력 영역의 너비를 픽셀 단위로 가져오거나 설정합니다(주석이 오른쪽에 표시되는 경우에만 적용됩니다).

--------------------

최소 및 기본값은 **150**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |