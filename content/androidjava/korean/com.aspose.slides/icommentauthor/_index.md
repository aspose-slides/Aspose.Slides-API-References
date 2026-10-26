---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: 댓글 작성자를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
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
### getName() {#getName--}
```
public abstract String getName()
```

작성자의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

작성자의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

작성자의 이니셜을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

작성자의 이니셜을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

이 작성자가 만든 댓글 컬렉션을 반환합니다. 읽기 전용 [ICommentCollection](../../com.aspose.slides/icommentcollection).

**반환:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

작성자를 상위 컬렉션에서 제거합니다.