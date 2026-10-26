---
title: GraphicalObjectLock
second_title: Aspose.Slides for Android에 대한 Java API 참조
description: 상위 GraphicalObject에서 사용 중지된 작업이 무엇인지 결정합니다.
type: docs
url: /ko/com.aspose.slides/graphicalobjectlock/
---
**상속:**
java.lang.Object, [com.aspose.slides.BaseShapeLock](../../com.aspose.slides/baseshapelock)

**구현된 모든 인터페이스:**
[com.aspose.slides.IGraphicalObjectLock](../../com.aspose.slides/igraphicalobjectlock)
```
public class GraphicalObjectLock extends BaseShapeLock implements IGraphicalObjectLock
```

상위 GraphicalObject에서 비활성화된 작업을 결정합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | 이 도형을 그룹에 추가하는 것이 금지된 여부를 결정합니다. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | 이 도형을 그룹에 추가하는 것이 금지된 여부를 결정합니다. |
| [getDrilldownLocked()](#getDrilldownLocked--) | 이 객체의 하위 도형 선택이 금지된 여부를 결정합니다. |
| [setDrilldownLocked(boolean value)](#setDrilldownLocked-boolean-) | 이 객체의 하위 도형 선택이 금지된 여부를 결정합니다. |
| [getSelectLocked()](#getSelectLocked--) | 이 도형을 선택하는 것이 금지된 여부를 결정합니다. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | 이 도형을 선택하는 것이 금지된 여부를 결정합니다. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | 크기 조정 시 도형이 가로세로 비율을 유지해야 하는지 여부를 결정합니다. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | 크기 조정 시 도형이 가로세로 비율을 유지해야 하는지 여부를 결정합니다. |
| [getPositionLocked()](#getPositionLocked--) | 이 도형을 이동하는 것이 금지된 여부를 결정합니다. |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | 이 도형을 이동하는 것이 금지된 여부를 결정합니다. |
| [getSizeLocked()](#getSizeLocked--) | 이 도형의 크기 조정이 금지된 여부를 결정합니다. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | 이 도형의 크기 조정이 금지된 여부를 결정합니다. |
### getGroupingLocked() {#getGroupingLocked--}
```
public boolean getGroupingLocked()
```


이 도형을 그룹에 추가하는 것이 금지된 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public void setGroupingLocked(boolean value)
```


이 도형을 그룹에 추가하는 것이 금지된 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDrilldownLocked() {#getDrilldownLocked--}
```
public boolean getDrilldownLocked()
```


이 객체의 하위 도형 선택이 금지된 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setDrilldownLocked(boolean value) {#setDrilldownLocked-boolean-}
```
public void setDrilldownLocked(boolean value)
```


이 객체의 하위 도형 선택이 금지된 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public boolean getSelectLocked()
```


이 도형을 선택하는 것이 금지된 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public void setSelectLocked(boolean value)
```


이 도형을 선택하는 것이 금지된 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public boolean getAspectRatioLocked()
```


크기 조정 시 도형이 가로세로 비율을 유지해야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public void setAspectRatioLocked(boolean value)
```


크기 조정 시 도형이 가로세로 비율을 유지해야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getPositionLocked() {#getPositionLocked--}
```
public boolean getPositionLocked()
```


이 도형을 이동하는 것이 금지된 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public void setPositionLocked(boolean value)
```


이 도형을 이동하는 것이 금지된 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public boolean getSizeLocked()
```


이 도형의 크기 조정이 금지된 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public void setSizeLocked(boolean value)
```


이 도형의 크기 조정이 금지된 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |