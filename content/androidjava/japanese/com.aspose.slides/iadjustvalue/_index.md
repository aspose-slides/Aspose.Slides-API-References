---
title: IAdjustValue
second_title: Aspose.Slides for Android の Java API リファレンス
description: ジオメトリ形状の調整値を表します。
type: docs
url: /ja/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

ジオメトリ形状の調整値を表します。これらの値は形状の形状に影響します。
## Methods

| メソッド | 説明 |
| --- | --- |
| [getRawValue()](#getRawValue--) | 調整値をそのまま取得または設定します。 |
| [setRawValue(long value)](#setRawValue-long-) | 調整値をそのまま取得または設定します。 |
| [getAngleValue()](#getAngleValue--) | 角度（度）として解釈し、値を取得または設定します。 |
| [setAngleValue(float value)](#setAngleValue-float-) | 角度（度）として解釈し、値を取得または設定します。 |
| [getName()](#getName--) | この調整値の名前を取得します。 |
| [getType()](#getType--) | シェイプ調整のタイプを取得します。 |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

調整値をそのまま取得または設定します。読み書き可能な long。

**戻り値:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

調整値をそのまま取得または設定します。読み書き可能な long。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

角度（度）として解釈し、値を取得または設定します。読み書き可能な float。

**戻り値:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

角度（度）として解釈し、値を取得または設定します。読み書き可能な float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```

この調整値の名前を取得します。読み取り専用の String。

**戻り値:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

シェイプ調整のタイプを取得します。読み取り専用 [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype)。

**戻り値:**
int