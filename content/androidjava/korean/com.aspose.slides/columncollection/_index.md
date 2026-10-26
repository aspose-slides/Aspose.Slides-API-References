---
title: ColumnCollection
second_title: Aspose.Slides for Android Java API 레퍼런스
description: 테이블에서 열의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/columncollection/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)  
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

테이블에서 열의 컬렉션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 있는 열의 수를 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 열을 반환합니다. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | 지정된 템플릿 행의 복사본을 만들고 테이블 하단에 삽입합니다. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | 지정된 템플릿 열의 복사본을 만들고 테이블의 지정된 위치에 삽입합니다. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | 테이블에서 지정된 위치에 있는 열을 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 액세스가 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |

### size() {#size--}
```
public final int size()
```

컬렉션에 있는 열의 수를 반환합니다. 읽기 전용 int.

**반환값:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

지정된 인덱스의 열을 반환합니다. 읽기 전용 [Column](../../com.aspose.slides/column).

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**  
[IColumn](../../com.aspose.slides/icolumn)

### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

지정된 템플릿 행의 복사본을 만들고 테이블 하단에 삽입합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 템플릿으로 사용되는 열. |
| withAttachedColumns | boolean | 템플릿 행에 연결된 모든 열도 복사하려면 true. |

**반환값:**  
com.aspose.slides.IColumn[] - 추가된 열.

### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

지정된 템플릿 열의 복사본을 만들고 테이블의 지정된 위치에 삽입합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int | 새 열의 인덱스. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 템플릿으로 사용되는 열. |
| withAttachedColumns | boolean | 템플릿 열에 연결된 모든 열도 복사하려면 true. |

**반환값:**  
com.aspose.slides.IColumn[] - 삽입된 열.

### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

테이블에서 지정된 위치에 있는 열을 제거합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| firstColumnIndex | int | 삭제할 열의 인덱스. |
| withAttachedRows | boolean | 연결된 모든 열도 삭제하려면 true. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

컬렉션을 반복하는 열거자를 반환합니다.

**반환값:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - 컬렉션을 반복하는 데 사용할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

전체 컬렉션에 대한 java iterator를 반환합니다.

**반환값:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - 전체 컬렉션에 대한 java.util.Iterator.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열의 시작 인덱스. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

컬렉션에 대한 액세스가 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환값:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. 읽기 전용 Object.

**반환값:**  
java.lang.Object