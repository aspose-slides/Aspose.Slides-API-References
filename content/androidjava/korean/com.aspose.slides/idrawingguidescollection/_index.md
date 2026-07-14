---
title: IDrawingGuidesCollection
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 조정 가능한 그리기 가이드의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/idrawingguidescollection/
---
**구현된 모든 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

조정 가능한 그리기 가이드의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 그리기 가이드를 반환합니다. |
| [add(byte orientation, float position)](#add-byte-float-) | 컬렉션의 끝에 그리기 가이드를 추가합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스의 그리기 가이드를 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
| [getCount()](#getCount--) | 컬렉션의 모든 요소 수를 가져옵니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

인덱스로 그리기 가이드를 반환합니다. 읽기 전용 [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```

컬렉션의 끝에 그리기 가이드를 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| orientation | byte | 그리기 가이드의 방향. |
| position | float | 그리기 가이드의 위치(포인트 단위). |

**반환값:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

지정된 인덱스의 그리기 가이드를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 삭제할 그리기 가이드의 인덱스. |

### clear() {#clear--}
```
public abstract void clear()
```

컬렉션의 모든 요소를 제거합니다.

### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션의 모든 요소 수를 가져옵니다. 읽기 전용 int.

**반환값:**
int