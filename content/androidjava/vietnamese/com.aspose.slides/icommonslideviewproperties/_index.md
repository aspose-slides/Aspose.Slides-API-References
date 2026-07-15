---
title: ICommonSlideViewProperties
second_title: Aspose.Slides cho Android thông qua Java API Reference
description: Đại diện cho các thuộc tính chế độ xem slide chung.
type: docs
url: /vi/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Đại diện cho các thuộc tính chế độ xem slide chung.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getScale()](#getScale--) | Xác định tỷ lệ phóng đại của chế độ xem theo phần trăm. |
| [setScale(int value)](#setScale-int-) | Xác định tỷ lệ phóng đại của chế độ xem theo phần trăm. |
| [getVariableScale()](#getVariableScale--) | Xác định rằng nội dung chế độ xem nên tự động thu phóng để vừa nhất với kích thước cửa sổ hiện tại. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Xác định rằng nội dung chế độ xem nên tự động thu phóng để vừa nhất với kích thước cửa sổ hiện tại. |
| [getDrawingGuides()](#getDrawingGuides--) | Trả về tập hợp của các hướng dẫn vẽ. |
### getScale() {#getScale--}
```
public abstract int getScale()
```

Xác định tỷ lệ phóng đại của chế độ xem theo phần trăm. Đọc/ghi int.

**Trả về:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

Xác định tỷ lệ phóng đại của chế độ xem theo phần trăm. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

Xác định rằng nội dung chế độ xem nên tự động thu phóng để vừa nhất với kích thước cửa sổ hiện tại. Đọc/ghi boolean.

**Trả về:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

Xác định rằng nội dung chế độ xem nên tự động thu phóng để vừa nhất với kích thước cửa sổ hiện tại. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Trả về tập hợp của các hướng dẫn vẽ. Chỉ đọc [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Thêm hướng dẫn vẽ dọc mới vào phía bên phải trung tâm slide
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // Thêm hướng dẫn vẽ ngang mới vào phía dưới trung tâm slide
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)