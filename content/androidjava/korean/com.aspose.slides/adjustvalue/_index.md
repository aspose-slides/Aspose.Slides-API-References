---
title: AdjustValue
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 기하학 도형의 조정 값을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/adjustvalue/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IAdjustValue](../../com.aspose.slides/iadjustvalue)  
```
public class AdjustValue implements IAdjustValue
```

기하학적 도형의 조정값을 나타냅니다. 이러한 값은 도형의 형태에 영향을 줍니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRawValue()](#getRawValue--) | 조정값을 "as is" 반환하거나 설정합니다. |
| [setRawValue(long value)](#setRawValue-long-) | 조정값을 "as is" 반환하거나 설정합니다. |
| [getAngleValue()](#getAngleValue--) | 값을 반환하거나 설정합니다. 각도(도)로 해석합니다. |
| [setAngleValue(float value)](#setAngleValue-float-) | 값을 반환하거나 설정합니다. 각도(도)로 해석합니다. |
| [getName()](#getName--) | 이 조정값의 이름을 반환합니다. |
| [getType()](#getType--) | 도형 조정의 유형을 반환합니다. |

### getRawValue() {#getRawValue--}
```
public final long getRawValue()
```

조정값을 "as is" 반환하거나 설정합니다. 읽기/쓰기 long.

**반환:**  
long

### setRawValue(long value) {#setRawValue-long-}
```
public final void setRawValue(long value)
```

조정값을 "as is" 반환하거나 설정합니다. 읽기/쓰기 long.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public final float getAngleValue()
```

값을 반환하거나 설정합니다. 각도(도)로 해석합니다. 읽기/쓰기 float.

**반환:**  
float

### setAngleValue(float value) {#setAngleValue-float-}
```
public final void setAngleValue(float value)
```

값을 반환하거나 설정합니다. 각도(도)로 해석합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public final String getName()
```

이 조정값의 이름을 반환합니다. 읽기 전용 String.

**반환:**  
java.lang.String

### getType() {#getType--}
```
public final int getType()
```

도형 조정의 유형을 반환합니다. 읽기 전용 [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**반환:**  
int