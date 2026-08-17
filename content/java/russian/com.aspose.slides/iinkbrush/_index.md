---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: Представляет кисть для трассировки.
type: docs
url: /ru/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Представляет кисть для трассировки.
## Методы

| Метод | Описание |
| --- | --- |
| [getColor()](#getColor--) | Получает или задает цвет кисти для линии. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Получает или задает цвет кисти для линии. |
| [getSize()](#getSize--) | Получает или задает размер кисти для линии в пунктах. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Получает или задает размер кисти для линии в пунктах. |
| [getInkEffect()](#getInkEffect--) | Получает тип эффекта чернил (например, Galaxy, Gold, Silver), определяющий визуальный стиль штриха. |
### getColor() {#getColor--}
```
public abstract Color getColor()
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
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.Color |  |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
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
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**  
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
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
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**  
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |
### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

Получает тип эффекта чернил (например, Galaxy, Gold, Silver), определяющий визуальный стиль штриха. Значение извлекается из свойства кисти "inkEffects". Если не указан распознанный эффект, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) возвращается.

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