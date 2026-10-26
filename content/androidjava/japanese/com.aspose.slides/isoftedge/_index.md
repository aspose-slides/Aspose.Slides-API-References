---
title: ISoftEdge
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: ソフトエッジ効果を表します。
type: docs
url: /ja/com.aspose.slides/isoftedge/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface ISoftEdge extends IImageTransformOperation, IAccessiblePVIObject<ISoftEdgeEffectiveData>
```

ソフトエッジ効果を表します。シェイプのエッジはぼやけますが、塗りつぶしは影響を受けません。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRadius()](#getRadius--) | エッジに適用するぼかしの半径を指定します。 |
| [setRadius(double value)](#setRadius-double-) | エッジに適用するぼかしの半径を指定します。 |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

エッジに適用するぼかしの半径を指定します。Read/write double.

**戻り値:**
double

### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

エッジに適用するぼかしの半径を指定します。Read/write double.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |