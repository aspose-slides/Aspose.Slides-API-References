---
title: AdjustValue
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: ジオメトリ形状の調整値を表します。
type: docs
url: /ja/com.aspose.slides/adjustvalue/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IAdjustValue](../../com.aspose.slides/iadjustvalue)
```
public class AdjustValue implements IAdjustValue
```

ジオメトリ形状の調整値を表します。これらの値は形状の形に影響します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRawValue()](#getRawValue--) | 調整値を「as is」のまま取得または設定します。 |
| [setRawValue(long value)](#setRawValue-long-) | 調整値を「as is」のまま取得または設定します。 |
| [getAngleValue()](#getAngleValue--) | 角度（度）として解釈し、値を取得または設定します。 |
| [setAngleValue(float value)](#setAngleValue-float-) | 角度（度）として解釈し、値を取得または設定します。 |
| [getName()](#getName--) | この調整値の名前を取得します。 |
| [getType()](#getType--) | 形状調整のタイプを取得します。 |

### getRawValue() {#getRawValue--}
```
public final long getRawValue()
```

調整値を「as is」のまま取得または設定します。読み取り/書き込み long。

**戻り値:**
long

### setRawValue(long value) {#setRawValue-long-}
```
public final void setRawValue(long value)
```

調整値を「as is」のまま取得または設定します。読み取り/書き込み long。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public final float getAngleValue()
```

角度（度）として解釈し、値を取得または設定します。読み取り/書き込み float。

**戻り値:**
float

### setAngleValue(float value) {#setAngleValue-float-}
```
public final void setAngleValue(float value)
```

角度（度）として解釈し、値を取得または設定します。読み取り/書き込み float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public final String getName()
```

この調整値の名前を取得します。読み取り専用 String。

**戻り値:**
java.lang.String

### getType() {#getType--}
```
public final int getType()
```

形状調整のタイプを取得します。読み取り専用 [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype)。

**戻り値:**
int