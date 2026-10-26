---
title: IConnectorLock
second_title: Aspose.Slides for Java API 레퍼런스
description: 부모 Connector에서 사용이 비활성화된 작업을 결정합니다.
type: docs
url: /ko/com.aspose.slides/iconnectorlock/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IConnectorLock extends IBaseShapeLock
```

부모 Connector에서 사용이 비활성화된 작업을 결정합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | 이 모양을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | 이 모양을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. |
| [getSelectLocked()](#getSelectLocked--) | 이 모양을 선택하는 것이 금지되는지 여부를 결정합니다. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | 이 모양을 선택하는 것이 금지되는지 여부를 결정합니다. |
| [getRotateLocked()](#getRotateLocked--) | 이 모양의 회전 각도를 변경하는 것이 금지되는지 여부를 결정합니다. |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | 이 모양의 회전 각도를 변경하는 것이 금지되는지 여부를 결정합니다. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | 크기를 조정할 때 이 모양이 종횡비를 유지해야 하는지 여부를 결정합니다. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | 크기를 조정할 때 이 모양이 종횡비를 유지해야 하는지 여부를 결정합니다. |
| [getPositionMove()](#getPositionMove--) | 이 모양을 이동하는 것이 금지되는지 여부를 결정합니다. |
| [setPositionMove(boolean value)](#setPositionMove-boolean-) | 이 모양을 이동하는 것이 금지되는지 여부를 결정합니다. |
| [getSizeLocked()](#getSizeLocked--) | 이 모양의 크기를 조정하는 것이 금지되는지 여부를 결정합니다. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | 이 모양의 크기를 조정하는 것이 금지되는지 여부를 결정합니다. |
| [getEditPointsLocked()](#getEditPointsLocked--) | 이 모양의 윤곽을 직접 변경하는 것이 금지되는지 여부를 결정합니다. |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | 이 모양의 윤곽을 직접 변경하는 것이 금지되는지 여부를 결정합니다. |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | 조정 값을 변경하는 것이 금지되는지 여부를 결정합니다. |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | 조정 값을 변경하는 것이 금지되는지 여부를 결정합니다. |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | 화살표 머리를 변경하는 것이 금지되는지 여부를 결정합니다. |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | 화살표 머리를 변경하는 것이 금지되는지 여부를 결정합니다. |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | 모양 유형을 변경하는 것이 금지되는지 여부를 결정합니다. |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | 모양 유형을 변경하는 것이 금지되는지 여부를 결정합니다. |

### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

이 모양을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

이 모양을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

이 모양을 선택하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

이 모양을 선택하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getRotateLocked() {#getRotateLocked--}
```
public abstract boolean getRotateLocked()
```

이 모양의 회전 각도를 변경하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public abstract void setRotateLocked(boolean value)
```

이 모양의 회전 각도를 변경하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

크기를 조정할 때 이 모양이 종횡비를 유지해야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

크기를 조정할 때 이 모양이 종횡비를 유지해야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getPositionMove() {#getPositionMove--}
```
public abstract boolean getPositionMove()
```

이 모양을 이동하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setPositionMove(boolean value) {#setPositionMove-boolean-}
```
public abstract void setPositionMove(boolean value)
```

이 모양을 이동하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

이 모양의 크기를 조정하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

이 모양의 크기를 조정하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

이 모양의 윤곽을 직접 변경하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

이 모양의 윤곽을 직접 변경하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

조정 값을 변경하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

조정 값을 변경하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

화살표 머리를 변경하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

화살표 머리를 변경하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

모양 유형을 변경하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

모양 유형을 변경하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |