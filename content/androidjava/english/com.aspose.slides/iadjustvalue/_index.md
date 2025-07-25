---
title: IAdjustValue
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a geometry shapes adjustment value.
type: docs
url: /com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Represents a geometry shape's adjustment value. These values affect shape's form.
## Methods

| Method | Description |
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


Returns or sets adjustment value "as is". Read/write long.

**Returns:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```


Returns or sets adjustment value "as is". Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```


Returns or sets value, interpreting it as angle in degrees. Read/write float.

**Returns:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```


Returns or sets value, interpreting it as angle in degrees. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```


Returns a name of this adjustment value. Read-only String.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```


Returns the type of the shape adjustment. Read-only [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Returns:**
int
