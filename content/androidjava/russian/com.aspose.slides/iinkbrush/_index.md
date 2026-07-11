---
title: IInkBrush
second_title: Aspose.Slides for Android via Java API Reference
description: Represents trace brush.
type: docs
url: /ru/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Представляет кисть трассировки.
## Методы

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Получает или задает цвет кисти для линии. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Получает или задает цвет кисти для линии. |
| [getSize()](#getSize--) | Получает или задает размер кисти для линии в пунктах. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Получает или задает размер кисти для линии в пунктах. |
| [getInkEffect()](#getInkEffect--) | Получает тип эффекта чернил (например, Galaxy, Gold, Silver), который определяет визуальный стиль штриха чернила. |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```


Получает или задает цвет кисти для линии.

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

**Возвращаемое значение:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```


Получает или задает цвет кисти для линии.

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

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public abstract SizeF getSize()
```


Получает или задает размер кисти для линии в пунктах.

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


**Возвращаемое значение:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public abstract void setSize(SizeF value)
```


Получает или задает размер кисти для линии в пунктах.

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

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```


Получает тип эффекта чернил (например, Galaxy, Gold, Silver), который определяет визуальный стиль штриха чернила. Значение извлекается из свойства кисти "inkEffects". Если не указан распознанный эффект, возвращается [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined).

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

**Возвращаемое значение:**
int