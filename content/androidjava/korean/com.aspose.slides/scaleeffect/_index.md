---
title: ScaleEffect
second_title: Aspose.Slides Android용 Java API 참조
description: 애니메이션 스케일 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/scaleeffect/
---
**상속:**  
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IScaleEffect](../../com.aspose.slides/iscaleeffect)  
```
public class ScaleEffect extends Behavior implements IScaleEffect
```

애니메이션 스케일 효과를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ScaleEffect()](#ScaleEffect--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getZoomContent()](#getZoomContent--) | 콘텐츠를 확대해야 하는지 여부를 결정합니다. |
| [setZoomContent(byte value)](#setZoomContent-byte-) | 콘텐츠를 확대해야 하는지 여부를 결정합니다. |
| [getFrom()](#getFrom--) | 애니메이션을 시작할 x/y 좌표를 지정합니다(퍼센트 단위). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | 애니메이션을 시작할 x/y 좌표를 지정합니다(퍼센트 단위). |
| [getTo()](#getTo--) | 애니메이션 스케일 효과의 대상 위치를 지정합니다(퍼센트 단위). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | 애니메이션 스케일 효과의 대상 위치를 지정합니다(퍼센트 단위). |
| [getBy()](#getBy--) | 애니메이션의 상대 오프셋 값을 설명합니다(퍼센트 단위). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | 애니메이션의 상대 오프셋 값을 설명합니다(퍼센트 단위). |
### ScaleEffect() {#ScaleEffect--}
```
public ScaleEffect()
```

### getZoomContent() {#getZoomContent--}
```
public final byte getZoomContent()
```

콘텐츠를 확대해야 하는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환값:**  
byte
### setZoomContent(byte value) {#setZoomContent-byte-}
```
public final void setZoomContent(byte value)
```

콘텐츠를 확대해야 하는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getFrom() {#getFrom--}
```
public final PointF getFrom()
```

애니메이션을 시작할 x/y 좌표를 지정합니다(퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**반환값:**  
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```

애니메이션을 시작할 x/y 좌표를 지정합니다(퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```

애니메이션 스케일 효과의 대상 위치를 지정합니다(퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**반환값:**  
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```

애니메이션 스케일 효과의 대상 위치를 지정합니다(퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```

애니메이션의 상대 오프셋 값을 설명합니다(퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**반환값:**  
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```

애니메이션의 상대 오프셋 값을 설명합니다(퍼센트 단위). 읽기/쓰기 android.graphics.PointF.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | android.graphics.PointF |  |