---
title: Collect
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đại diện cho một nhóm các phương thức nhằm thu thập các đối tượng mô hình của các loại khác nhau từ .
type: docs
url: /vi/com.aspose.slides/collect/
---
**Kế thừa:**
java.lang.Object
```
public class Collect
```

Đại diện cho một nhóm các phương thức nhằm thu thập các đối tượng mô hình của các loại khác nhau từ [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... thay đổi định dạng shape hoặc các thuộc tính khác
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [Collect()](#Collect--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Thu thập tất cả các thể hiện của [Shape](../../com.aspose.slides/shape) trong [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```

### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```

Thu thập tất cả các thể hiện của [Shape](../../com.aspose.slides/shape) trong [Presentation](../../com.aspose.slides/presentation).

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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bản trình chiếu để thu thập các shape |

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Bộ sưu tập tất cả các shape có trong bản trình chiếu