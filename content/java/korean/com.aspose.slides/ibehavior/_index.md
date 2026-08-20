---
title: IBehavior
second_title: Aspose.Slides for Java API Reference
description: 효과의 기본 클래스 동작을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

효과의 기본 클래스 동작을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | 애니메이션 동작이 누적되는지 표시합니다. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | 애니메이션 동작이 누적되는지 표시합니다. |
| [getAdditive()](#getAdditive--) | 현재 애니메이션 동작이 다른 실행 중인 애니메이션과 결합되는지 표시합니다. |
| [setAdditive(int value)](#setAdditive-int-) | 현재 애니메이션 동작이 다른 실행 중인 애니메이션과 결합되는지 표시합니다. |
| [getProperties()](#getProperties--) | 동작의 속성을 나타냅니다. |
| [getTiming()](#getTiming--) | 효과 동작에 대한 타이밍 속성을 나타냅니다. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | 효과 동작에 대한 타이밍 속성을 나타냅니다. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

애니메이션 동작이 누적되는지 표시합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

애니메이션 동작이 누적되는지 표시합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

현재 애니메이션 동작이 다른 실행 중인 애니메이션과 결합되는지 표시합니다. 읽기/쓰기 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**반환:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

현재 애니메이션 동작이 다른 실행 중인 애니메이션과 결합되는지 표시합니다. 읽기/쓰기 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

동작의 속성을 나타냅니다. 읽기 전용 [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**반환:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

효과 동작에 대한 타이밍 속성을 나타냅니다. 읽기/쓰기 [ITiming](../../com.aspose.slides/itiming).

**반환:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

효과 동작에 대한 타이밍 속성을 나타냅니다. 읽기/쓰기 [ITiming](../../com.aspose.slides/itiming).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |