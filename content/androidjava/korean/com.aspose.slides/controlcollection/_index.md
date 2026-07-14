---
title: ControlCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: ActiveX 컨트롤의 컬렉션입니다.
type: docs
url: /ko/com.aspose.slides/controlcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

ActiveX 컨트롤의 컬렉션입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 있는 객체의 개수를 반환합니다. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | 컬렉션에 새 컨트롤을 생성하고 추가합니다. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | 컬렉션에서 ActiveX 컨트롤을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 위치에 저장된 ActiveX 컨트롤을 컬렉션에서 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 컨트롤을 제거합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 위치에 있는 컨트롤을 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 전체 컬렉션을 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 액세스가 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

컬렉션에 있는 객체의 개수를 반환합니다. Read-only int.

**반환:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

컬렉션에 새 컨트롤을 생성하고 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| controlType | int | 추가할 컨트롤의 유형. |
| x | float | shape 프레임의 왼쪽 측면에 대한 X 좌표. |
| y | float | shape 프레임의 상단 측면에 대한 Y 좌표. |
| width | float | shape 프레임의 너비. |
| height | float | shape 프레임의 높이. |

**반환:**
[IControl](../../com.aspose.slides/icontrol) - 생성된 컨트롤.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

컬렉션에서 ActiveX 컨트롤을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | 제거할 컨트롤. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 위치에 저장된 ActiveX 컨트롤을 컬렉션에서 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 컨트롤의 인덱스. |

### clear() {#clear--}
```
public final void clear()
```

컬렉션의 모든 컨트롤을 제거합니다.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

지정된 위치에 있는 컨트롤을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 컨트롤의 인덱스. |

**반환:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

컬렉션을 반복하는 열거자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - 컬렉션을 반복하는 데 사용할 수 있는 IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

전체 컬렉션에 대한 java iterator를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - 전체 컬렉션에 대한 java.util.Iterator.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

전체 컬렉션을 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열 |
| index | int | 대상 배열의 인덱스. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

컬렉션에 대한 액세스가 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. Read-only boolean.

**반환:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. Read-only Object.

**반환:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. Read-only IDOMObject.

**반환:**
com.aspose.slides.IDOMObject