---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Controls SVG shape generation.
type: docs
url: /vi/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

Điều khiển việc tạo hình dạng SVG.
## Phương thức

| Method | Mô tả |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | This function is called before rendering of shape to SVG to allow user to control resulting SVG. |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```


Hàm này được gọi trước khi vẽ hình dạng thành SVG để cho phép người dùng kiểm soát SVG kết quả.

**Tham số:**
| Parameter | Type | Mô tả |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | Đối tượng để điều khiển việc tạo hình dạng SVG. |
| shape | [IShape](../../com.aspose.slides/ishape) | Hình dạng nguồn. |