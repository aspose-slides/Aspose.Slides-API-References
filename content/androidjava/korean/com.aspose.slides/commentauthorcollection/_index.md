---
title: CommentAuthorCollection
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: 주석 작성자들의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/commentauthorcollection/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)  
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

주석 작성자들의 컬렉션을 나타냅니다.

## 메서드

| Method | Description |
| --- | --- |
| [size()](#size--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | 컬렉션의 끝에 새 작성자를 추가합니다. |
| [toArray()](#toArray--) | 모든 작성자를 포함하는 배열을 만들고 반환합니다. |
| [findByName(String name)](#findByName-java.lang.String-) | 이름으로 컬렉션에서 작성자를 찾습니다. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | 이름 및 이니셜로 컬렉션에서 작성자를 찾습니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 지정된 인덱스에 있는 작성자를 제거합니다. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | 컬렉션에서 지정된 작성자의 첫 번째 발생을 제거합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 작성자를 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 이터레이터를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |

### size() {#size--}
```
public final int size()
```

컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용 int.

**반환값:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)

### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

컬렉션의 끝에 새 작성자를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 새 작성자의 이름. |
| initials | java.lang.String | 새 작성자의 이니셜. |

**반환값:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - 새 [ICommentAuthor](../../com.aspose.slides/icommentauthor) 객체.

### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

모든 작성자를 포함하는 배열을 만들고 반환합니다.

**반환값:**
com.aspose.slides.ICommentAuthor[] - [ICommentAuthor](../../com.aspose.slides/icommentauthor) 배열

### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

이름으로 컬렉션에서 작성자를 찾습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 찾을 작성자의 이름. |

**반환값:**
com.aspose.slides.ICommentAuthor[] - 작성자 또는 null.

### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

이름 및 이니셜로 컬렉션에서 작성자를 찾습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 찾을 작성자의 이름. |
| initials | java.lang.String | 찾을 작성자의 이니셜. |

**반환값:**
com.aspose.slides.ICommentAuthor[] - 작성자 또는 null.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

컬렉션에서 지정된 인덱스에 있는 작성자를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0부터 시작하는 인덱스. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

컬렉션에서 지정된 작성자의 첫 번째 발생을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | 컬렉션에서 제거할 작성자. |

### clear() {#clear--}
```
public final void clear()
```

컬렉션에서 모든 작성자를 제거합니다.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

전체 컬렉션에 대한 java 이터레이터를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - 전체 컬렉션에 대한 java.util.Iterator.

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

컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환값:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. 읽기 전용 Object.

**반환값:**
java.lang.Object