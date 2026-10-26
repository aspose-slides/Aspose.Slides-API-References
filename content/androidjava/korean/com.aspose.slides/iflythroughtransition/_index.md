---
title: IFlyThroughTransition
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 플라이스루 슬라이드 전환 효과.
type: docs
url: /ko/com.aspose.slides/iflythroughtransition/
---
**전체 구현된 인터페이스:**  
[com.aspose.slides.ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
```
public interface IFlyThroughTransition extends ITransitionValueBase
```

플라이스루 슬라이드 전환 효과.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDirection()](#getDirection--) | 전환 방향. |
| [setDirection(int value)](#setDirection-int-) | 전환 방향. |
| [hasBounce()](#hasBounce--) | 전환 중에 프레젠테이션 슬라이드의 움직임에 바운스가 포함된다고 지정합니다. |
| [setBounce(boolean value)](#setBounce-boolean-) | 전환 중에 프레젠테이션 슬라이드의 움직임에 바운스가 포함된다고 지정합니다. |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasBounce() {#hasBounce--}
```
public abstract boolean hasBounce()
```


전환 중에 프레젠테이션 슬라이드의 움직임에 바운스가 포함된다고 지정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setBounce(boolean value) {#setBounce-boolean-}
```
public abstract void setBounce(boolean value)
```


전환 중에 프레젠테이션 슬라이드의 움직임에 바운스가 포함된다고 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |