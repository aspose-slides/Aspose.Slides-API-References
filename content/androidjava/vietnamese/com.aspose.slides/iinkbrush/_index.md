---
title: IInkBrush
second_title: Aspose.Slides for Android via Java API Reference
description: Represents trace brush.
type: docs
url: /vi/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Đại diện cho bút vẽ dấu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getColor()](#getColor--) | Lấy hoặc đặt màu của bút cho một đường. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Lấy hoặc đặt màu của bút cho một đường. |
| [getSize()](#getSize--) | Lấy hoặc đặt kích thước bút cho một đường tính bằng điểm. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Lấy hoặc đặt kích thước bút cho một đường tính bằng điểm. |
| [getInkEffect()](#getInkEffect--) | Lấy loại hiệu ứng mực (ví dụ: Galaxy, Gold, Silver) xác định phong cách trực quan của nét mực. |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```

Lấy hoặc đặt màu của bút cho một đường.

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
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

Lấy hoặc đặt màu của bút cho một đường.

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
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public abstract SizeF getSize()
```

Lấy hoặc đặt kích thước bút cho một đường tính bằng điểm.

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

**Trả về:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public abstract void setSize(SizeF value)
```

Lấy hoặc đặt kích thước bút cho một đường tính bằng điểm.

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

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

Lấy loại hiệu ứng mực (ví dụ: Galaxy, Gold, Silver) xác định phong cách trực quan của nét mực. Giá trị được phân tích từ thuộc tính bút “inkEffects”. Nếu **không** có hiệu ứng được công nhận nào được chỉ định, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) được trả về.

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