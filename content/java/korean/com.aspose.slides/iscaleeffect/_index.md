---
title: IScaleEffect
second_title: Aspose.Slides for Java API 레퍼런스
description: 애니메이션 스케일 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iscaleeffect/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IScaleEffect extends IBehavior
```

애니메이션 스케일 효과를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getZoomContent()](#getZoomContent--) | 콘텐츠를 확대해야 하는지 여부를 결정합니다. |
| [setZoomContent(byte value)](#setZoomContent-byte-) | 콘텐츠를 확대해야 하는지 여부를 결정합니다. |
| [getFrom()](#getFrom--) | 애니메이션 시작 위치를 지정하는 x/y 좌표를 퍼센트 단위로 지정합니다. |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | 애니메이션 시작 위치를 지정하는 x/y 좌표를 퍼센트 단위로 지정합니다. |
| [getTo()](#getTo--) | 애니메이션 스케일 효과의 목표 위치를 퍼센트 단위로 지정합니다. |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | 애니메이션 스케일 효과의 목표 위치를 퍼센트 단위로 지정합니다. |
| [getBy()](#getBy--) | 애니메이션의 상대적인 오프셋 값을 퍼센트 단위로 설명합니다. |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | 애니메이션의 상대적인 오프셋 값을 퍼센트 단위로 설명합니다. |
### getZoomContent() {#getZoomContent--}
```
public abstract byte getZoomContent()
```

콘텐츠를 확대해야 하는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**  
byte
### setZoomContent(byte value) {#setZoomContent-byte-}
```
public abstract void setZoomContent(byte value)
```

콘텐츠를 확대해야 하는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

애니메이션 시작 위치를 지정하는 x/y 좌표를 퍼센트 단위로 지정합니다. 읽기/쓰기 java.awt.geom.Point2D.Float.

**반환:**  
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

애니메이션 시작 위치를 지정하는 x/y 좌표를 퍼센트 단위로 지정합니다. 읽기/쓰기 java.awt.geom.Point2D.Float.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

애니메이션 스케일 효과의 목표 위치를 퍼센트 단위로 지정합니다. 읽기/쓰기 java.awt.geom.Point2D.Float.

**반환:**  
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

애니메이션 스케일 효과의 목표 위치를 퍼센트 단위로 지정합니다. 읽기/쓰기 java.awt.geom.Point2D.Float.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

애니메이션의 상대적인 오프셋 값을 퍼센트 단위로 설명합니다. 읽기/쓰기 java.awt.geom.Point2D.Float.

**반환:**  
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

애니메이션의 상대적인 오프셋 값을 퍼센트 단위로 설명합니다. 읽기/쓰기 java.awt.geom.Point2D.Float.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |