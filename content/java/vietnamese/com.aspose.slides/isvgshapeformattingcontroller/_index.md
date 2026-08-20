---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Java API Reference
description: Kiểm soát việc tạo hình SVG.
type: docs
url: /vi/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

Kiểm soát việc tạo hình SVG.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | Hàm này được gọi trước khi render hình dạng sang SVG để cho phép người dùng kiểm soát SVG kết quả. |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```


Hàm này được gọi trước khi render hình dạng sang SVG để cho phép người dùng kiểm soát SVG kết quả.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | Đối tượng để kiểm soát việc tạo hình SVG. |
| shape | [IShape](../../com.aspose.slides/ishape) | Hình nguồn. |