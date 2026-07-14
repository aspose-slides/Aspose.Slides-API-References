---
title: DrawingGuidesCollection
second_title: Aspose.Slides for Android via Java API 레퍼런스
description: 조정 가능한 그리기 가이드를 모은 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/drawingguidescollection/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)  
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

조정 가능한 그리기 가이드를 모은 컬렉션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 그리기 가이드를 반환합니다. |
| [add(byte orientation, float position)](#add-byte-float-) | 컬렉션의 끝에 그리기 가이드를 추가합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스의 그리기 가이드를 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 반복자를 반환합니다. |
| [getCount()](#getCount--) | 컬렉션의 요소 수를 반환합니다. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | 컬렉션의 모든 요소를 지정된 배열로 복사합니다. |

### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

인덱스로 그리기 가이드를 반환합니다. 읽기 전용 [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parameters:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**Returns:**  
[IDrawingGuide](../../com.aspose.slides/idrawingguide)

### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```

컬렉션의 끝에 그리기 가이드를 추가합니다.

**Parameters:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| orientation | byte | 그리기 가이드의 방향. |
| position | float | 포인트 단위의 그리기 가이드 위치. |

**Returns:**  
[IDrawingGuide](../../com.aspose.slides/idrawingguide)

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 인덱스의 그리기 가이드를 제거합니다.

**Parameters:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 삭제할 그리기 가이드의 인덱스. |

### clear() {#clear--}
```
public final void clear()
```

컬렉션의 모든 요소를 제거합니다.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

전체 컬렉션에 대한 java 반복자를 반환합니다.

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - 전체 컬렉션에 대한 java.util.Iterator.

### getCount() {#getCount--}
```
public final int getCount()
```

컬렉션의 요소 수를 반환합니다. 읽기 전용 int.

**Returns:**  
int

### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDDrawingGuide[] array, int index)
```

컬렉션의 모든 요소를 지정된 배열로 복사합니다.

**Parameters:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | 대상 배열. |
| index | int | 대상 배열의 시작 인덱스. |