---
title: IGraphicalObjectLock
second_title: Java API 레퍼런스를 사용한 Android용 Aspose.Slides
description: 부모 GraphicalObject에서 비활성화된 작업이 무엇인지 결정합니다.
type: docs
url: /ko/com.aspose.slides/igraphicalobjectlock/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IGraphicalObjectLock extends IBaseShapeLock
```

부모 GraphicalObject에서 비활성화된 작업이 어떤 것인지 결정합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | Determines whether adding this shape to a group is forbidden. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | Determines whether adding this shape to a group is forbidden. |
| [getDrilldownLocked()](#getDrilldownLocked--) | Determines whether selecting subshapes of this object is forbidden. |
| [setDrilldownLocked(boolean value)](#setDrilldownLocked-boolean-) | Determines whether selecting subshapes of this object is forbidden. |
| [getSelectLocked()](#getSelectLocked--) | Determines whether selecting this shape is forbidden. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | Determines whether selecting this shape is forbidden. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | Determines whether shape have to preserve aspect ratio on resizing. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | Determines whether shape have to preserve aspect ratio on resizing. |
| [getPositionLocked()](#getPositionLocked--) | Determines whether moving this shape is forbidden. |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | Determines whether moving this shape is forbidden. |
| [getSizeLocked()](#getSizeLocked--) | Determines whether resizing this shape is forbidden. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | Determines whether resizing this shape is forbidden. |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```


이 모양을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
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

### getDrilldownLocked() {#getDrilldownLocked--}
```
public abstract boolean getDrilldownLocked()
```


이 객체의 하위 모양 선택이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setDrilldownLocked(boolean value) {#setDrilldownLocked-boolean-}
```
public abstract void setDrilldownLocked(boolean value)
```


이 객체의 하위 모양 선택이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```


이 모양 선택이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```


이 모양 선택이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```


크기 조정 시 모양이 종횡비를 유지해야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```


크기 조정 시 모양이 종횡비를 유지해야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```


이 모양을 이동하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
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


이 모양을 크기 조정하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```


이 모양을 크기 조정하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |