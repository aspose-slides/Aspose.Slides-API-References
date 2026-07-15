---
title: InkBrush
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Đại diện cho một đối tượng inkBrush.
type: docs
url: /vi/com.aspose.slides/inkbrush/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)  
```
public class InkBrush implements IInkBrush
```

Đại diện cho một đối tượng inkBrush.

## Phương thức

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Lấy hoặc đặt màu cọ cho một đường. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Lấy hoặc đặt màu cọ cho một đường. |
| [getSize()](#getSize--) | Lấy hoặc đặt kích thước cọ cho một đường tính bằng điểm. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Lấy hoặc đặt kích thước cọ cho một đường tính bằng điểm. |
| [getInkEffect()](#getInkEffect--) | Lấy kiểu hiệu ứng mực (ví dụ: Galaxy, Gold, Silver) xác định phong cách trực quan của nét mực. |

### getColor() {#getColor--}
```
public final Integer getColor()
```

Lấy hoặc đặt màu cọ cho một đường.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**  
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

Lấy hoặc đặt màu cọ cho một đường.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public final SizeF getSize()
```

Lấy hoặc đặt kích thước cọ cho một đường tính bằng điểm.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**  
[SizeF](../../com.aspose.slides.android/sizef)

### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
```

Lấy hoặc đặt kích thước cọ cho một đường tính bằng điểm.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

Lấy kiểu hiệu ứng mực (ví dụ: Galaxy, Gold, Silver) xác định phong cách trực quan của nét mực. Giá trị được phân tích từ thuộc tính brush "inkEffects". Nếu không có hiệu ứng được công nhận nào được chỉ định, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) sẽ được trả về.

**Returns:**  
int