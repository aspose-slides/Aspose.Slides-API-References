---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Java API 參考文件
description: 控制 SVG 形狀的生成。
type: docs
url: /zh-hant/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

控制 SVG 形狀的生成。
## 方法

| 方法 | 描述 |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | 此函數在將形狀渲染為 SVG 之前被調用，以允許使用者控制生成的 SVG。 |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```


此函數在將形狀渲染為 SVG 之前被調用，以允許使用者控制生成的 SVG。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | 用於控制 SVG 形狀生成的物件。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 來源形狀。 |