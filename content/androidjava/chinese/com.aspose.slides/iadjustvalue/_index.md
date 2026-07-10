---
title: IAdjustValue
second_title: Aspose.Slides for Android via Java API Reference
description: 表示几何形状的调整值。
type: docs
url: /zh/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

表示几何形状的调整值。这些值会影响形状的形态。

## 方法

| 方法 | 描述 |
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

返回或设置调整值“原样”。读/写 long.

**返回:**  
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

返回或设置调整值“原样”。读/写 long.

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

返回或设置值，将其解释为以度为单位的角度。读/写 float.

**返回:**  
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

返回或设置值，将其解释为以度为单位的角度。读/写 float.

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```

返回此调整值的名称。只读 String。

**返回:**  
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

返回形状调整的类型。只读 [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype)。

**返回:**  
int