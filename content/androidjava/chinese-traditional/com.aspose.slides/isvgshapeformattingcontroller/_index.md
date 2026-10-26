---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: 控制 SVG 形狀生成。
type: docs
url: /zh-hant/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

控制 SVG 形狀生成。
## 方法

| 方法 | 說明 |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | 此函式在將形狀渲染為 SVG 之前呼叫，以允許使用者控制最終的 SVG。 |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```

此函式在將形狀渲染為 SVG 之前呼叫，以允許使用者控制最終的 SVG。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | 用於控制 SVG 形狀生成的物件。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 來源形狀。 |