---
title: ControlCollection
second_title: Aspose.Slides for Java API 레퍼런스
description: ActiveX 컨트롤의 컬렉션입니다.
type: docs
url: /ko/com.aspose.slides/controlcollection/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

ActiveX 컨트롤의 컬렉션입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 포함된 객체 수를 반환합니다. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | 새 컨트롤을 생성하고 컬렉션에 추가합니다. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | 컬렉션에서 ActiveX 컨트롤을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 위치에 저장된 ActiveX 컨트롤을 컬렉션에서 제거합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 컨트롤을 제거합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 위치에 있는 컨트롤을 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 전체 컬렉션을 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

컬렉션에 포함된 객체 수를 반환합니다. 읽기 전용 int.

**반환:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

새 컨트롤을 생성하고 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| controlType | int | 추가할 컨트롤의 유형입니다. |
| x | float | 도형 프레임 왼쪽 측면의 X 좌표입니다. |
| y | float | 도형 프레임 위쪽 측면의 Y 좌표입니다. |
| width | float | 도형 프레임의 너비입니다. |
| height | float | 도형 프레임의 높이입니다. |

**반환:**
[IControl](../../com.aspose.slides/icontrol) - Created control.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

컬렉션에서 ActiveX 컨트롤을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | 제거할 컨트롤입니다. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 위치에 저장된 ActiveX 컨트롤을 컬렉션에서 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 제거할 컨트롤의 인덱스입니다. |

### clear() {#clear--}
```
public final void clear()
```

컬렉션에서 모든 컨트롤을 제거합니다.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

지정된 위치에 있는 컨트롤을 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 컨트롤의 인덱스입니다. |

**반환:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

전체 컬렉션에 대한 java.util.Iterator를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - 전체 컬렉션에 대한 java.util.Iterator
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

전체 컬렉션을 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열 |
| index | int | 대상 배열의 인덱스. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. 읽기 전용 Object.

**반환:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**
com.aspose.slides.IDOMObject