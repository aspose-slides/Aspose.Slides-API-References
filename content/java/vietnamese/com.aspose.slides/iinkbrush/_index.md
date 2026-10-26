---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: Biểu diễn bút dấu vết.
type: docs
url: /vi/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Biểu diễn bút dấu vết.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getColor()](#getColor--) | Lấy hoặc đặt màu cọ cho một đường. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Lấy hoặc đặt màu cọ cho một đường. |
| [getSize()](#getSize--) | Lấy hoặc đặt kích thước cọ cho một đường tính bằng điểm. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Lấy hoặc đặt kích thước cọ cho một đường tính bằng điểm. |
| [getInkEffect()](#getInkEffect--) | Lấy loại hiệu ứng mực (ví dụ: Galaxy, Gold, Silver) xác định kiểu hình ảnh của nét mực. |
### getColor() {#getColor--}
```
public abstract Color getColor()
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
public abstract void setColor(Color value)
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
public abstract Dimension2D getSize()
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
public abstract void setSize(Dimension2D value)
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
public abstract int getInkEffect()
```


Lấy loại hiệu ứng mực (ví dụ: Galaxy, Gold, Silver) xác định kiểu hình ảnh của nét mực. Giá trị được phân tích từ thuộc tính "inkEffects" của cọ. Nếu không có hiệu ứng nào được công nhận, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) sẽ được trả về.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      Ink ink = (Ink) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkBrush brush = ink.getTraces()[0].getBrush();
>      System.out.println("InkEffects = " + brush.getInkEffect());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**  
int