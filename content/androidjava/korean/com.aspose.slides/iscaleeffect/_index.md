---
title: IScaleEffect
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
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
| [getFrom()](#getFrom--) | 애니메이션을 시작할 x/y 좌표를 지정합니다 (퍼센트 단위). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | 애니메이션을 시작할 x/y 좌표를 지정합니다 (퍼센트 단위). |
| [getTo()](#getTo--) | 애니메이션 스케일 효과의 대상 위치를 지정합니다 (퍼센트 단위). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | 애니메이션 스케일 효과의 대상 위치를 지정합니다 (퍼센트 단위). |
| [getBy()](#getBy--) | 애니메이션의 상대 오프셋 값을 설명합니다 (퍼센트 단위). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | 애니메이션의 상대 오프셋 값을 설명합니다 (퍼센트 단위). |
### getZoomContent() {#getZoomContent--}
```
public abstract byte getZoomContent()
```

콘텐츠를 확대해야 하는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환값:**
byte
### setZoomContent(byte value) {#setZoomContent-byte-}
```
public abstract void setZoomContent(byte value)
```

콘텐츠를 확대해야 하는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

애니메이션을 시작할 x/y 좌표를 지정합니다 (퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**반환값:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

애니메이션을 시작할 x/y 좌표를 지정합니다 (퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

애니메이션 스케일 효과의 대상 위치를 지정합니다 (퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**반환값:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

애니메이션 스케일 효과의 대상 위치를 지정합니다 (퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

애니메이션의 상대 오프셋 값을 설명합니다 (퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**반환값:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

애니메이션의 상대 오프셋 값을 설명합니다 (퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF |  |