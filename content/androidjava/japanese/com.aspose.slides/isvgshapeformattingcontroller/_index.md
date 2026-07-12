---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Controls SVG shape generation.
type: docs
url: /ja/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

SVGシェイプの生成を制御します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | この関数は、形状をSVGにレンダリングする前に呼び出され、ユーザーが生成されるSVGを制御できるようにします。 |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```

この関数は、形状をSVGにレンダリングする前に呼び出され、ユーザーが生成されるSVGを制御できるようにします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | SVGシェイプの生成を制御するオブジェクト。 |
| shape | [IShape](../../com.aspose.slides/ishape) | ソースシェイプ。 |