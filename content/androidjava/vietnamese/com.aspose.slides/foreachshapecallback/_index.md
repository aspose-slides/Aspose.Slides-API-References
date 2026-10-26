---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /vi/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## Phương thức

| Method | Description |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Callback sẽ được gọi cho mỗi [Shape](../../com.aspose.slides/shape) trong [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```

Callback sẽ được gọi cho mỗi [Shape](../../com.aspose.slides/shape) trong [Presentation](../../com.aspose.slides/presentation).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | Hình hiện tại đang được lặp |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Slide hiện tại đang được lặp |
| index | int | Chỉ mục của slide bố cục hiện tại |