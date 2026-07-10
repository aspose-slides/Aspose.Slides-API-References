---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Android via Java API 参考
description: 控制 SVG 形状生成。
type: docs
url: /zh/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

控制 SVG 形状生成。
## 方法

| 方法 | 描述 |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | 在将形状渲染为 SVG 之前调用此函数，以便用户控制生成的 SVG。 |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```

在将形状渲染为 SVG 之前调用此函数，以便用户控制生成的 SVG。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | 用于控制 SVG 形状生成的对象。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 源形状。 |