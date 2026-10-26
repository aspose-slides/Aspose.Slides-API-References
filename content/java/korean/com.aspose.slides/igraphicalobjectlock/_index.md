---
title: IGraphicalObjectLock
second_title: Aspose.Slides for Java API 참조
description: 부모 GraphicalObject에서 비활성화된 작업이 무엇인지 결정합니다.
type: docs
url: /ko/com.aspose.slides/igraphicalobjectlock/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IGraphicalObjectLock extends IBaseShapeLock
```

부모 GraphicalObject에서 비활성화된 작업을 결정합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | 이 도형을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | 이 도형을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. |
| [getDrilldownLocked()](#getDrilldownLocked--) | 이 객체의 하위 도형을 선택하는 것이 금지되는지 여부를 결정합니다. |
| [setDrilldownLocked(boolean value)](#setDrilldownLocked-boolean-) | 이 객체의 하위 도형을 선택하는 것이 금지되는지 여부를 결정합니다. |
| [getSelectLocked()](#getSelectLocked--) | 이 도형을 선택하는 것이 금지되는지 여부를 결정합니다. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | 이 도형을 선택하는 것이 금지되는지 여부를 결정합니다. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | 도형이 크기 조정 시 종횡비를 유지해야 하는지 여부를 결정합니다. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | 도형이 크기 조정 시 종횡비를 유지해야 하는지 여부를 결정합니다. |
| [getPositionLocked()](#getPositionLocked--) | 이 도형을 이동하는 것이 금지되는지 여부를 결정합니다. |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | 이 도형을 이동하는 것이 금지되는지 여부를 결정합니다. |
| [getSizeLocked()](#getSizeLocked--) | 이 도형의 크기 조정을 금지하는지 여부를 결정합니다. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | 이 도형의 크기 조정을 금지하는지 여부를 결정합니다. |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

이 도형을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

이 도형을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getDrilldownLocked() {#getDrilldownLocked--}
```
public abstract boolean getDrilldownLocked()
```

이 객체의 하위 도형을 선택하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setDrilldownLocked(boolean value) {#setDrilldownLocked-boolean-}
```
public abstract void setDrilldownLocked(boolean value)
```

이 객체의 하위 도형을 선택하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

이 도형을 선택하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

이 도형을 선택하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

도형이 크기 조정 시 종횡비를 유지해야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

도형이 크기 조정 시 종횡비를 유지해야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

이 도형을 이동하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

이 도형을 이동하는 것이 금지되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

이 도형의 크기 조정을 금지하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

이 도형의 크기 조정을 금지하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |