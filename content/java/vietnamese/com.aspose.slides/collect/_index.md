---
title: Collect
second_title: Tham chiếu API Aspose.Slides cho Java
description: Mô tả một nhóm các phương thức nhằm thu thập các đối tượng mô hình của các loại khác nhau từ .
type: docs
url: /vi/com.aspose.slides/collect/
---
**Kế thừa:**
java.lang.Object
```
public class Collect
```

Mô tả một nhóm các phương thức nhằm thu thập các đối tượng mô hình của các loại khác nhau từ [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... thay đổi định dạng hình dạng hoặc các thuộc tính khác
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Hàm tạo

| Constructor | Description |
| --- | --- |
| [Collect()](#Collect--) |  |
## Phương thức

| Method | Description |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Thu thập tất cả các thực thể của [Shape](../../com.aspose.slides/shape) trong [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```


### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```


Thu thập tất cả các thực thể của [Shape](../../com.aspose.slides/shape) trong [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // nếu shape là AutoShape, thêm viền đen đặc
>          if (shape instanceof AutoShape)
>          {
>              AutoShape autoShape = (AutoShape)shape;
>              autoShape.getLineFormat().setStyle(LineStyle.Single);
>              autoShape.getLineFormat().setWidth(10f);
>              autoShape.getLineFormat().getFillFormat().setFillType(FillType.Solid);
>              autoShape.getLineFormat().getFillFormat().getSolidFillColor().setColor(Color.black);
>          }
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation để thu thập các hình dạng |

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Bộ sưu tập tất cả các hình dạng chứa trong bản trình bày