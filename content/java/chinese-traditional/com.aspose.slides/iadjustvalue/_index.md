---
title: IAdjustValue
second_title: Aspose.Slides for Java API 參考文件
description: 表示幾何形狀的調整值。
type: docs
url: /zh-hant/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

表示幾何形狀的調整值。這些值會影響形狀的外觀。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getRawValue()](#getRawValue--) | 取得或設定調整值「原樣」。 |
| [setRawValue(long value)](#setRawValue-long-) | 取得或設定調整值「原樣」。 |
| [getAngleValue()](#getAngleValue--) | 取得或設定值，將其解釋為以度數表示的角度。 |
| [setAngleValue(float value)](#setAngleValue-float-) | 取得或設定值，將其解釋為以度數表示的角度。 |
| [getName()](#getName--) | 取得此調整值的名稱。 |
| [getType()](#getType--) | 取得形狀調整的類型。 |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

取得或設定調整值「原樣」。可讀寫 long。

**傳回值:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

取得或設定調整值「原樣」。可讀寫 long。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

取得或設定值，將其解釋為以度數表示的角度。可讀寫 float。

**傳回值:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

取得或設定值，將其解釋為以度數表示的角度。可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```

取得此調整值的名稱。唯讀 String。

**傳回值:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

取得形狀調整的類型。唯讀 [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype)。

**傳回值:**
int