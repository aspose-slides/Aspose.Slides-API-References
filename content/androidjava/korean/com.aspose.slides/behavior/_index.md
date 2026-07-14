---
title: Behavior
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 효과의 기본 클래스 동작을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/behavior/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject  
```
public abstract class Behavior implements IBehavior, IDOMObject
```

효과의 기본 클래스 동작을 나타냅니다.

## Methods

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | 애니메이션 동작이 누적되는지 여부를 나타냅니다. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | 애니메이션 동작이 누적되는지 여부를 나타냅니다. |
| [getAdditive()](#getAdditive--) | 현재 애니메이션 동작이 다른 실행 중인 애니메이션과 결합되는지 여부를 나타냅니다. |
| [setAdditive(int value)](#setAdditive-int-) | 현재 애니메이션 동작이 다른 실행 중인 애니메이션과 결합되는지 여부를 나타냅니다. |
| [getProperties()](#getProperties--) | 동작의 속성을 나타냅니다. |
| [getTiming()](#getTiming--) | 효과 동작의 타이밍 속성을 나타냅니다. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | 효과 동작의 타이밍 속성을 나타냅니다. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**Returns:**  
com.aspose.slides.IDOMObject

### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

애니메이션 동작이 누적되는지 여부를 나타냅니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**  
byte

### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

애니메이션 동작이 누적되는지 여부를 나타냅니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

현재 애니메이션 동작이 다른 실행 중인 애니메이션과 결합되는지 여부를 나타냅니다. 읽기/쓰기 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Returns:**  
int

### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

현재 애니메이션 동작이 다른 실행 중인 애니메이션과 결합되는지 여부를 나타냅니다. 읽기/쓰기 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

동작의 속성을 나타냅니다. 읽기 전용 [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Returns:**  
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

효과 동작의 타이밍 속성을 나타냅니다. 읽기/쓰기 [ITiming](../../com.aspose.slides/itiming).

**Returns:**  
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

효과 동작의 타이밍 속성을 나타냅니다. 읽기/쓰기 [ITiming](../../com.aspose.slides/itiming).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |