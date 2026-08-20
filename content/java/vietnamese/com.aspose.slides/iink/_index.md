---
title: IInk
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một đối tượng mực trên slide.
type: docs
url: /vi/com.aspose.slides/iink/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Đại diện cho một đối tượng mực trên slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTraces()](#getTraces--) | Lấy tất cả dấu vết chứa trong phần tử IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```

Lấy tất cả dấu vết chứa trong phần tử IInk [IInkTrace](../../com.aspose.slides/iinktrace). Chỉ đọc.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
com.aspose.slides.IInkTrace[]