---
title: InkBrush
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một đối tượng inkBrush.
type: docs
url: /vi/com.aspose.slides/inkbrush/
---
**Kế thừa:**
java.lang.Object

**Tất cả giao diện được triển khai:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Biểu diễn một đối tượng inkBrush.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getColor()](#getColor--) | Lấy hoặc đặt màu cọ cho một đường. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Lấy hoặc đặt màu cọ cho một đường. |
| [getSize()](#getSize--) | Lấy hoặc đặt kích thước cọ cho một đường tính bằng điểm. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Lấy hoặc đặt kích thước cọ cho một đường tính bằng điểm. |
| [getInkEffect()](#getInkEffect--) | Lấy kiểu hiệu ứng mực (ví dụ: Galaxy, Gold, Silver) xác định phong cách hiển thị của nét mực. |
### getColor() {#getColor--}
```
public final Color getColor()
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

**Trả về:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
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

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.awt.Color |  |
### getSize() {#getSize--}
```
public final Dimension2D getSize()
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
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public final void setSize(Dimension2D value)
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
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |
### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```


Lấy kiểu hiệu ứng mực (ví dụ: Galaxy, Gold, Silver) xác định phong cách hiển thị của nét mực. Giá trị được phân tích từ thuộc tính brush "inkEffects". Nếu không có hiệu ứng nào được công nhận, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) được trả về.

**Trả về:**
int