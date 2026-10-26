---
title: IRevealTransition
second_title: Aspose.Slides Android용 Java API 참고
description: 슬라이드 전환 효과를 표시합니다.
type: docs
url: /ko/com.aspose.slides/irevealtransition/
---
**All Implemented Interfaces:**
[com.aspose.slides.ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
```
public interface IRevealTransition extends ITransitionValueBase
```

슬라이드 전환 효과를 표시합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDirection()](#getDirection--) | 전환 방향. |
| [setDirection(int value)](#setDirection-int-) | 전환 방향. |
| [getThroughBlack()](#getThroughBlack--) | 전환이 검은 화면을 통해 페이드되는지 여부를 지정합니다. |
| [setThroughBlack(boolean value)](#setThroughBlack-boolean-) | 전환이 검은 화면을 통해 페이드되는지 여부를 지정합니다. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

전환 방향. 읽기/쓰기 [TransitionLeftRightDirectionType](../../com.aspose.slides/transitionleftrightdirectiontype).

**반환값:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

전환 방향. 읽기/쓰기 [TransitionLeftRightDirectionType](../../com.aspose.slides/transitionleftrightdirectiontype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getThroughBlack() {#getThroughBlack--}
```
public abstract boolean getThroughBlack()
```

전환이 검은 화면을 통해 페이드되는지 여부를 지정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setThroughBlack(boolean value) {#setThroughBlack-boolean-}
```
public abstract void setThroughBlack(boolean value)
```

전환이 검은 화면을 통해 페이드되는지 여부를 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |