---
title: IAdjustValue
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a geometry shapes adjustment value.
type: docs
url: /ko/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

기하학적 도형의 조정 값을 나타냅니다. 이러한 값들은 도형의 형태에 영향을 줍니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRawValue()](#getRawValue--) | Returns or sets adjustment value "as is". |
| [setRawValue(long value)](#setRawValue-long-) | Returns or sets adjustment value "as is". |
| [getAngleValue()](#getAngleValue--) | Returns or sets value, interpreting it as angle in degrees. |
| [setAngleValue(float value)](#setAngleValue-float-) | Returns or sets value, interpreting it as angle in degrees. |
| [getName()](#getName--) | Returns a name of this adjustment value. |
| [getType()](#getType--) | Returns the type of the shape adjustment. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

조정 값을 그대로 반환하거나 설정합니다. 읽기/쓰기 long.

**반환:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

조정 값을 그대로 반환하거나 설정합니다. 읽기/쓰기 long.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

값을 반환하거나 설정하며, 각도로(도 단위) 해석합니다. 읽기/쓰기 float.

**반환:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

값을 반환하거나 설정하며, 각도로(도 단위) 해석합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```

이 조정 값의 이름을 반환합니다. 읽기 전용 String.

**반환:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

도형 조정의 유형을 반환합니다. 읽기 전용 [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**반환:**
int