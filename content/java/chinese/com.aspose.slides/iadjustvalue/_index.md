---
title: IAdjustValue
second_title: Aspose.Slides for Java API Reference
description: Represents a geometry shapes adjustment value.
type: docs
url: /zh/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

表示几何形状的调整值。这些值会影响形状的形态。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRawValue()](#getRawValue--) | 返回或设置调整值（原样）。 |
| [setRawValue(long value)](#setRawValue-long-) | 返回或设置调整值（原样）。 |
| [getAngleValue()](#getAngleValue--) | 返回或设置值，将其解释为角度（单位：度）。 |
| [setAngleValue(float value)](#setAngleValue-float-) | 返回或设置值，将其解释为角度（单位：度）。 |
| [getName()](#getName--) | 返回此调整值的名称。 |
| [getType()](#getType--) | 返回形状调整的类型。 |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```


返回或设置调整值（原样）。读取/写入 long。

**返回：**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```


返回或设置调整值（原样）。读取/写入 long。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```


返回或设置值，将其解释为角度（单位：度）。读取/写入 float。

**返回：**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```


返回或设置值，将其解释为角度（单位：度）。读取/写入 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```


返回此调整值的名称。只读 String。

**返回：**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```


返回形状调整的类型。只读 [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype)。

**返回：**
int