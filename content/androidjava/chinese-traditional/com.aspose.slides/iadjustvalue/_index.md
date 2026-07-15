---
title: IAdjustValue
second_title: Aspose.Slides for Android via Java API Reference
description: 代表幾何形狀的調整值。
type: docs
url: /zh-hant/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

代表幾何形狀的調整值。這些值會影響形狀的形態。
## 方法

| Method | Description |
| --- | --- |
| [getRawValue()](#getRawValue--) | 返回或設定調整值「原樣」。 |
| [setRawValue(long value)](#setRawValue-long-) | 返回或設定調整值「原樣」。 |
| [getAngleValue()](#getAngleValue--) | 返回或設定值，將其解讀為角度（度）。 |
| [setAngleValue(float value)](#setAngleValue-float-) | 返回或設定值，將其解讀為角度（度）。 |
| [getName()](#getName--) | 返回此調整值的名稱。 |
| [getType()](#getType--) | 返回形狀調整的類型。 |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

返回或設定調整值「原樣」。讀寫 long。

**返回：**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

返回或設定調整值「原樣」。讀寫 long。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

返回或設定值，將其解讀為角度（度）。讀寫 float。

**返回：**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

返回或設定值，將其解讀為角度（度）。讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```

返回此調整值的名稱。唯讀 String。

**返回：**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

返回形狀調整的類型。唯讀 [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype)。

**返回：**
int