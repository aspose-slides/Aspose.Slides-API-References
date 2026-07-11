---
title: InkBrush
second_title: Aspose.Slides для Android через справочник Java API
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
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Получает или задает цвет кисти для линии. |
| [getSize()](#getSize--) | Получает или задает размер кисти для линии в пунктах. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Получает или задает размер кисти для линии в пунктах. |
| [getInkEffect()](#getInkEffect--) | Получает тип эффекта чернил (например, Galaxy, Gold, Silver), определяющий визуальный стиль штриха. |
### getColor() {#getColor--}
```
public final Integer getColor()
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
public final void setColor(Integer value)
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
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public final SizeF getSize()
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
public final void setSize(SizeF value)
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```


Получает тип эффекта чернил (например, Galaxy, Gold, Silver), определяющий визуальный стиль штриха. Значение разбирается из свойства кисти «inkEffects». Если не указан распознанный эффект, возвращается [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined).

**Возвращаемое значение:**
int