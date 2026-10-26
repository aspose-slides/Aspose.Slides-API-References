---
title: AdjustValue
second_title: Aspose.Slides for Android via Java API 参考
description: 表示几何形状的调整值。
type: docs
url: /zh/com.aspose.slides/adjustvalue/
---
**继承：**
java.lang.Object

**全部已实现的接口：**
[com.aspose.slides.IAdjustValue](../../com.aspose.slides/iadjustvalue)
```
public class AdjustValue implements IAdjustValue
```

表示几何形状的调整值。这些值会影响形状的形态。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getRawValue()](#getRawValue--) | 返回或设置调整值（原样）。 |
| [setRawValue(long value)](#setRawValue-long-) | 返回或设置调整值（原样）。 |
| [getAngleValue()](#getAngleValue--) | 返回或设置值，将其解释为角度（以度为单位）。 |
| [setAngleValue(float value)](#setAngleValue-float-) | 返回或设置值，将其解释为角度（以度为单位）。 |
| [getName()](#getName--) | 返回此调整值的名称。 |
| [getType()](#getType--) | 返回形状调整的类型。 |
### getRawValue() {#getRawValue--}
```
public final long getRawValue()
```

返回或设置调整值（原样）。读写 long.

**返回：**
long
### setRawValue(long value) {#setRawValue-long-}
```
public final void setRawValue(long value)
```

返回或设置调整值（原样）。读写 long.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public final float getAngleValue()
```

返回或设置值，将其解释为角度（以度为单位）。读写 float.

**返回：**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public final void setAngleValue(float value)
```

返回或设置值，将其解释为角度（以度为单位）。读写 float.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public final String getName()
```

返回此调整值的名称。只读 String.

**返回：**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```

返回形状调整的类型。只读 [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype)。

**返回：**
int