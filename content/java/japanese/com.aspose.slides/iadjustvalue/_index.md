---
title: IAdjustValue
second_title: Aspose.Slides for Java API Reference
description: Represents a geometry shapes adjustment value.
type: docs
url: /ja/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

ジオメトリ形状の調整値を表します。これらの値は形状の形状に影響します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRawValue()](#getRawValue--) | 調整値をそのまま取得または設定します。 |
| [setRawValue(long value)](#setRawValue-long-) | 調整値をそのまま取得または設定します。 |
| [getAngleValue()](#getAngleValue--) | 値を角度（度）として解釈して取得または設定します。 |
| [setAngleValue(float value)](#setAngleValue-float-) | 値を角度（度）として解釈して取得または設定します。 |
| [getName()](#getName--) | この調整値の名前を返します。 |
| [getType()](#getType--) | 形状の調整のタイプを返します。 |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```


調整値をそのまま取得または設定します。読み取り/書き込み long.

**Returns:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```


調整値をそのまま取得または設定します。読み取り/書き込み long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```


値を角度（度）として解釈して取得または設定します。読み取り/書き込み float.

**Returns:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```


値を角度（度）として解釈して取得または設定します。読み取り/書き込み float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```


この調整値の名前を返します。読み取り専用 String.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```


形状の調整のタイプを返します。読み取り専用 [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Returns:**
int