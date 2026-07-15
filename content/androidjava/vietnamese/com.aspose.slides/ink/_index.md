---
title: Ink
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một đối tượng mực trên một slide.
type: docs
url: /vi/com.aspose.slides/ink/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Biểu diễn một đối tượng mực trên một slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTraces()](#getTraces--) | Lấy tất cả các dấu vết có trong phần tử IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | Lấy bộ sưu tập các hình ảnh tùy chỉnh dùng để mô phỏng hiệu ứng hình ảnh cho bút mực. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

Lấy tất cả các dấu vết có trong phần tử IInk [IInkTrace](../../com.aspose.slides/iinktrace). Chỉ đọc.

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
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```

Lấy bộ sưu tập các hình ảnh tùy chỉnh dùng để mô phỏng hiệu ứng hình ảnh cho bút mực. Những hình ảnh này được sử dụng khi kết xuất mực với các giá trị [InkEffectType](../../com.aspose.slides/inkeffecttype) cụ thể, chẳng hạn như Galaxy, Rainbow, v.v. Bằng cách cung cấp hình ảnh của riêng bạn, bạn có thể kiểm soát cách mỗi hiệu ứng mực hiển thị.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```

--------------------

Thuộc tính này cho phép thay thế các texture hiệu ứng mực mặc định bằng các texture do người dùng định nghĩa, điều này đặc biệt hữu ích khi các tài sản mặc định bị hạn chế bởi giấy phép hoặc không khả dụng tại thời gian chạy. Mỗi mục trong từ điển phải liên kết một giá trị [InkEffectType](../../com.aspose.slides/inkeffecttype) với một đối tượng [IImage](../../com.aspose.slides/iimage) tương ứng (ví dụ, Bitmap, hoặc một giao diện hình ảnh Aspose).

**Trả về:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>