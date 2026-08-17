---
title: ShapeElement
second_title: Aspose.Slides for Java API リファレンス
description: 同じ輪郭と塗りつぶしプロパティを持つシェイプの一部を表します。
type: docs
url: /ja/com.aspose.slides/shapeelement/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

同じ輪郭と塗りつぶしプロパティを持つシェイプの一部を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getParentShape()](#getParentShape--) | 要素が作成された Shape_PPT を返します。 |
| [getPathPoints()](#getPathPoints--) | 要素のパスのジオメトリを定義するポイントの配列を取得します。 |
| [getPathTypes()](#getPathTypes--) | 要素のパス内の各ポイントのタイプを指定するバイト値の配列を取得します。 |
| [getFillSource()](#getFillSource--) | 要素の塗りつぶし方法に関する情報を返します。 |
| [getStrokeSource()](#getStrokeSource--) | 要素のストローク方法に関する情報を返します。 |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```


要素が作成された Shape_PPT を返します。 読み取り専用 [Shape](../../com.aspose.slides/shape)。

**戻り値:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```


要素のパスのジオメトリを定義するポイントの配列を取得します。

**戻り値:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```


要素のパス内の各ポイントのタイプを指定するバイト値の配列を取得します。

**0** ポイントが図形の開始点であることを示します。

**1** ポイントが直線の端点のいずれかであることを示します。

**3** ポイントが三次ベジエスプラインの端点または制御点であることを示します。

**7** 低位3ビット以外のすべてのビットをマスクします。これらのビットはポイントタイプを示します。

**16** 対応するセグメントが破線であることを示します。

**32** ポイントがマーカーであることを示します。

**128** ポイントが閉じたサブパス（図形）の最後のポイントであることを示します。

**129** データポイントが直線セグメントの端点であり、かつ閉じたサブパスの最後のポイントであることを示します。

**戻り値:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```


要素の塗りつぶし方法に関する情報を返します。 読み取り専用 [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource)。

**戻り値:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```


要素のストローク方法に関する情報を返します。 読み取り専用 [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource)。

**戻り値:**
byte