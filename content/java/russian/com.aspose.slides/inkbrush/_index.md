---
title: InkBrush
second_title: Aspose.Slides для Java справочник API
description: Представляет объект inkBrush.
type: docs
url: /ru/com.aspose.slides/inkbrush/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Представляет объект inkBrush.
## Методы

| Метод | Описание |
| --- | --- |
| [getColor()](#getColor--) | Получает или задает цвет кисти для линии. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Получает или задает цвет кисти для линии. |
| [getSize()](#getSize--) | Получает или задает размер кисти для линии в пунктах. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Получает или задает размер кисти для линии в пунктах. |
| [getInkEffect()](#getInkEffect--) | Получает тип эффекта чернил (например, Galaxy, Gold, Silver), определяющий визуальный стиль штриха чернила. |
### getColor() {#getColor--}
```
public final Color getColor()
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
public final void setColor(Color value)
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
public final Dimension2D getSize()
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
public final void setSize(Dimension2D value)
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
public final int getInkEffect()
```


Получает тип эффекта чернил (например, Galaxy, Gold, Silver), определяющий визуальный стиль штриха чернила. Значение извлекается из свойства кисти "inkEffects". Если распознанный эффект не указан, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) возвращается.

**Возвращаемое значение:**
int