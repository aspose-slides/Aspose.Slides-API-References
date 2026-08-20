---
title: AdjustValue
second_title: Aspose.Slides for Java API 參考
description: 表示幾何形狀的調整值。
type: docs
url: /zh-hant/com.aspose.slides/adjustvalue/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IAdjustValue](../../com.aspose.slides/iadjustvalue)
```
public class AdjustValue implements IAdjustValue
```

表示幾何形狀的調整值。這些值會影響形狀的形式。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getRawValue()](#getRawValue--) | 返回或設定調整值「原樣」。 |
| [setRawValue(long value)](#setRawValue-long-) | 返回或設定調整值「原樣」。 |
| [getAngleValue()](#getAngleValue--) | 返回或設定值，將其解讀為角度（以度為單位）。 |
| [setAngleValue(float value)](#setAngleValue-float-) | 返回或設定值，將其解讀為角度（以度為單位）。 |
| [getName()](#getName--) | 返回此調整值的名稱。 |
| [getType()](#getType--) | 返回形狀調整的類型。 |

### getRawValue() {#getRawValue--}
```
public final long getRawValue()
```

返回或設定調整值「原樣」。讀寫 long。

**返回值:**
long

### setRawValue(long value) {#setRawValue-long-}
```
public final void setRawValue(long value)
```

返回或設定調整值「原樣」。讀寫 long。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public final float getAngleValue()
```

返回或設定值，將其解讀為角度（以度為單位）。讀寫 float。

**返回值:**
float

### setAngleValue(float value) {#setAngleValue-float-}
```
public final void setAngleValue(float value)
```

返回或設定值，將其解讀為角度（以度為單位）。讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public final String getName()
```

返回此調整值的名稱。唯讀 String。

**返回值:**
java.lang.String

### getType() {#getType--}
```
public final int getType()
```

返回形狀調整的類型。唯讀 [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype)。

**返回值:**
int