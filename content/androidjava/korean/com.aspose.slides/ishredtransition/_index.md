---
title: IShredTransition
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: Shred 슬라이드 전환 효과.
type: docs
url: /ko/com.aspose.slides/ishredtransition/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
```
public interface IShredTransition extends ITransitionValueBase
```

Shred 슬라이드 전환 효과.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDirection()](#getDirection--) | 전환 방향. |
| [setDirection(int value)](#setDirection-int-) | 전환 방향. |
| [getPattern()](#getPattern--) | 전환 중에 사용되는 시각 효과의 모양을 지정합니다. |
| [setPattern(int value)](#setPattern-int-) | 전환 중에 사용되는 시각 효과의 모양을 지정합니다. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

전환 방향. 읽기/쓰기 [TransitionInOutDirectionType](../../com.aspose.slides/transitioninoutdirectiontype).

**반환값:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

전환 방향. 읽기/쓰기 [TransitionInOutDirectionType](../../com.aspose.slides/transitioninoutdirectiontype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getPattern() {#getPattern--}
```
public abstract int getPattern()
```

전환 중에 사용되는 시각 효과의 모양을 지정합니다. 읽기/쓰기 [TransitionShredPattern](../../com.aspose.slides/transitionshredpattern).

**반환값:**
int
### setPattern(int value) {#setPattern-int-}
```
public abstract void setPattern(int value)
```

전환 중에 사용되는 시각 효과의 모양을 지정합니다. 읽기/쓰기 [TransitionShredPattern](../../com.aspose.slides/transitionshredpattern).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |