---
title: IGroupShapeLock
second_title: Aspose.Slides for Java API 레퍼런스
description: 부모 GroupShape에서 비활성화된 작업을 결정합니다.
type: docs
url: /ko/com.aspose.slides/igroupshapelock/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IGroupShapeLock extends IBaseShapeLock
```

부모 GroupShape에서 비활성화된 작업을 결정합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | 이 shape을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | 이 shape을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. |
| [getUngroupingLocked()](#getUngroupingLocked--) | 이 groupshape을 분할하는 것이 금지되는지 여부를 결정합니다. |
| [setUngroupingLocked(boolean value)](#setUngroupingLocked-boolean-) | 이 groupshape을 분할하는 것이 금지되는지 여부를 결정합니다. |
| [getSelectLocked()](#getSelectLocked--) | 이 shape을 선택하는 것이 금지되는지 여부를 결정합니다. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | 이 shape을 선택하는 것이 금지되는지 여부를 결정합니다. |
| [getRotationLocked()](#getRotationLocked--) | 이 shape의 회전 각도를 변경하는 것이 금지되는지 여부를 결정합니다. |
| [setRotationLocked(boolean value)](#setRotationLocked-boolean-) | 이 shape의 회전 각도를 변경하는 것이 금지되는지 여부를 결정합니다. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | 이 shape이 크기 조정 시 가로 세로 비율을 유지해야 하는지 여부를 결정합니다. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | 이 shape이 크기 조정 시 가로 세로 비율을 유지해야 하는지 여부를 결정합니다. |
| [getPositionLocked()](#getPositionLocked--) | 이 shape을 이동하는 것이 금지되는지 여부를 결정합니다. |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | 이 shape을 이동하는 것이 금지되는지 여부를 결정합니다. |
| [getSizeLocked()](#getSizeLocked--) | 이 shape을 크기 조정하는 것이 금지되는지 여부를 결정합니다. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | 이 shape을 크기 조정하는 것이 금지되는지 여부를 결정합니다. |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

이 shape을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

이 shape을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getUngroupingLocked() {#getUngroupingLocked--}
```
public abstract boolean getUngroupingLocked()
```

이 groupshape을 분할하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setUngroupingLocked(boolean value) {#setUngroupingLocked-boolean-}
```
public abstract void setUngroupingLocked(boolean value)
```

이 groupshape을 분할하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

이 shape을 선택하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

이 shape을 선택하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getRotationLocked() {#getRotationLocked--}
```
public abstract boolean getRotationLocked()
```

이 shape의 회전 각도를 변경하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setRotationLocked(boolean value) {#setRotationLocked-boolean-}
```
public abstract void setRotationLocked(boolean value)
```

이 shape의 회전 각도를 변경하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

이 shape이 크기 조정 시 가로 세로 비율을 유지해야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

이 shape이 크기 조정 시 가로 세로 비율을 유지해야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

이 shape을 이동하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

이 shape을 이동하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

이 shape을 크기 조정하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

이 shape을 크기 조정하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |