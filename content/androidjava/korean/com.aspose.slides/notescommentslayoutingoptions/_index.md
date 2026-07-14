---
title: NotesCommentsLayoutingOptions
second_title: Java API를 통한 Android용 Aspose.Slides 참조
description: 내보낸 문서에서 노트와 주석의 레이아웃 모양을 제어하는 옵션을 제공합니다.
type: docs
url: /ko/com.aspose.slides/notescommentslayoutingoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

노트와 주석의 레이아웃 모양을 제어하는 옵션을 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | 기본 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | 작성자가 없는 주석의 표시 여부를 가져오거나 설정합니다. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | 작성자가 없는 주석의 표시 여부를 가져오거나 설정합니다. |
| [getNotesPosition()](#getNotesPosition--) | 페이지에서 노트의 위치를 가져오거나 설정합니다. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | 페이지에서 노트의 위치를 가져오거나 설정합니다. |
| [getCommentsPosition()](#getCommentsPosition--) | 페이지에서 주석의 위치를 가져오거나 설정합니다. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | 페이지에서 주석의 위치를 가져오거나 설정합니다. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | 주석 영역의 색상을 가져오거나 설정합니다(주석이 오른쪽에 표시될 때만 적용). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | 주석 영역의 색상을 가져오거나 설정합니다(주석이 오른쪽에 표시될 때만 적용). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | 주석 출력 영역의 너비를 픽셀 단위로 가져오거나 설정합니다(주석이 오른쪽에 표시될 때만 적용). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | 주석 출력 영역의 너비를 픽셀 단위로 가져오거나 설정합니다(주석이 오른쪽에 표시될 때만 적용). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

기본 생성자.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

작성자가 없는 주석의 표시 여부를 가져오거나 설정합니다. true이면 주석이 표시됩니다. (주석이 표시될 때만 적용).

--------------------

기본값은 **false**입니다.

**반환값:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

작성자가 없는 주석의 표시 여부를 가져오거나 설정합니다. true이면 주석이 표시됩니다. (주석이 표시될 때만 적용).

--------------------

기본값은 **false**입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

페이지에서 노트의 위치를 가져오거나 설정합니다.

--------------------

기본값은 **NotesPositions.None**입니다.

**반환값:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

페이지에서 노트의 위치를 가져오거나 설정합니다.

--------------------

기본값은 **NotesPositions.None**입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |
### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

페이지에서 주석의 위치를 가져오거나 설정합니다.

--------------------

기본값은 **CommentsPositions.None**입니다.

**반환값:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

페이지에서 주석의 위치를 가져오거나 설정합니다.

--------------------

기본값은 **CommentsPositions.None**입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |
### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```

주석 영역의 색상을 가져오거나 설정합니다(주석이 오른쪽에 표시될 때만 적용).

--------------------

기본값은 **SkyBlue**입니다.

**반환값:**
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```

주석 영역의 색상을 가져오거나 설정합니다(주석이 오른쪽에 표시될 때만 적용).

--------------------

기본값은 **SkyBlue**입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

주석 출력 영역의 너비를 픽셀 단위로 가져오거나 설정합니다(주석이 오른쪽에 표시될 때만 적용).

--------------------

최소값 및 기본값은 **150**입니다.

**반환값:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

주석 출력 영역의 너비를 픽셀 단위로 가져오거나 설정합니다(주석이 오른쪽에 표시될 때만 적용).

--------------------

최소값 및 기본값은 **150**입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |