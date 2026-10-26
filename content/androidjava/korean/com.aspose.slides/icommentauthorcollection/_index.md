---
title: ICommentAuthorCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 주석 작성자 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icommentauthorcollection/
---
**모든 구현된 인터페이스:**  
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

주석 작성자 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | 컬렉션의 끝에 새 작성자를 추가합니다. |
| [toArray()](#toArray--) | 모든 작성자를 포함한 배열을 생성하고 반환합니다. |
| [findByName(String name)](#findByName-java.lang.String-) | 이름으로 컬렉션에서 작성자를 찾습니다. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | 이름과 이니셜로 컬렉션에서 작성자를 찾습니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에 있는 작성자를 컬렉션에서 제거합니다. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | 컬렉션에서 지정된 작성자의 첫 번째 발생을 제거합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 작성자를 제거합니다. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)

### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```

컬렉션의 끝에 새 작성자를 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 새 작성자의 이름. |
| initials | java.lang.String | 새 작성자의 이니셜. |

**반환값:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - 새로운 [ICommentAuthor](../../com.aspose.slides/icommentauthor) 객체.

### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```

모든 작성자를 포함한 배열을 생성하고 반환합니다.

**반환값:**
com.aspose.slides.ICommentAuthor[] - [ICommentAuthor](../../com.aspose.slides/icommentauthor) 배열

### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```

이름으로 컬렉션에서 작성자를 찾습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 찾을 작성자의 이름. |

**반환값:**
com.aspose.slides.ICommentAuthor[] - 작성자 또는 null.

### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

이름과 이니셜로 컬렉션에서 작성자를 찾습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 찾을 작성자의 이름. |
| initials | java.lang.String | 찾을 작성자의 이니셜. |

**반환값:**
com.aspose.slides.ICommentAuthor[] - 작성자 또는 null.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

지정된 인덱스에 있는 작성자를 컬렉션에서 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0부터 시작하는 인덱스. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

컬렉션에서 지정된 작성자의 첫 번째 발생을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | 컬렉션에서 제거할 작성자. |

### clear() {#clear--}
```
public abstract void clear()
```

컬렉션에서 모든 작성자를 제거합니다.