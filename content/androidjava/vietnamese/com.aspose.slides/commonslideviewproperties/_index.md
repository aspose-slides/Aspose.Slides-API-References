---
title: CommonSlideViewProperties
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu thị các thuộc tính chế độ xem slide chung.
type: docs
url: /vi/com.aspose.slides/commonslideviewproperties/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Biểu thị các thuộc tính chế độ xem slide chung.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Tạo một đối tượng Presentation đại diện cho một tệp trình chiếu
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Đặt thuộc tính chế độ xem của Presentation
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Giá trị phóng to tính bằng phần trăm cho chế độ xem slide
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Giá trị phóng to tính bằng phần trăm cho chế độ xem ghi chú
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getScale()](#getScale--) | Xác định tỷ lệ phóng to của chế độ xem tính bằng phần trăm. |
| [setScale(int value)](#setScale-int-) | Xác định tỷ lệ phóng to của chế độ xem tính bằng phần trăm. |
| [getVariableScale()](#getVariableScale--) | Xác định rằng nội dung chế độ xem sẽ tự động co giãn để phù hợp nhất với kích thước cửa sổ hiện tại. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Xác định rằng nội dung chế độ xem sẽ tự động co giãn để phù hợp nhất với kích thước cửa sổ hiện tại. |
| [getDrawingGuides()](#getDrawingGuides--) | Trả về bộ sưu tập các hướng dẫn vẽ. |
### getScale() {#getScale--}
```
public final int getScale()
```

Xác định tỷ lệ phóng to của chế độ xem tính bằng phần trăm. Đọc/ghi int.

**Trả về:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

Xác định tỷ lệ phóng to của chế độ xem tính bằng phần trăm. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

Xác định rằng nội dung chế độ xem sẽ tự động co giãn để phù hợp nhất với kích thước cửa sổ hiện tại. Đọc/ghi boolean.

**Trả về:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

Xác định rằng nội dung chế độ xem sẽ tự động co giãn để phù hợp nhất với kích thước cửa sổ hiện tại. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Trả về bộ sưu tập các hướng dẫn vẽ. Chỉ đọc [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Thêm hướng dẫn vẽ dọc mới vào bên phải trung tâm slide
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Thêm hướng dẫn vẽ ngang mới vào bên dưới trung tâm slide
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)