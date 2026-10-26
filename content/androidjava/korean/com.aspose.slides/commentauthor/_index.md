---
title: CommentAuthor
second_title: Java API 레퍼런스를 통한 Aspose.Slides for Android
description: 댓글 작성자를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/commentauthor/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.ICommentAuthor](../../com.aspose.slides/icommentauthor), com.aspose.slides.IDOMObject  
```
public final class CommentAuthor implements ICommentAuthor, IDOMObject
```

댓글 작성자를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getName()](#getName--) | 작성자의 이름을 반환하거나 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 작성자의 이름을 반환하거나 설정합니다. |
| [getInitials()](#getInitials--) | 작성자의 이니셜을 반환하거나 설정합니다. |
| [setInitials(String value)](#setInitials-java.lang.String-) | 작성자의 이니셜을 반환하거나 설정합니다. |
| [getComments()](#getComments--) | 이 작성자가 만든 댓글 컬렉션을 반환합니다. |
| [remove()](#remove--) | 작성자를 상위 컬렉션에서 제거합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getName() {#getName--}
```
public final String getName()
```

작성자의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

작성자의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public final String getInitials()
```

작성자의 이니셜을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**  
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public final void setInitials(String value)
```

작성자의 이니셜을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public final ICommentCollection getComments()
```

이 작성자가 만든 댓글 컬렉션을 반환합니다. 읽기 전용 [ICommentCollection](../../com.aspose.slides/icommentcollection).

**반환값:**  
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public final void remove()
```

작성자를 상위 컬렉션에서 제거합니다.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**  
com.aspose.slides.IDOMObject