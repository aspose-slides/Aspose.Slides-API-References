---
title: InkTrace
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет объект Trace.
type: docs
url: /ru/com.aspose.slides/inktrace/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

Представляет объект Trace. Элемент Trace используется для записи данных, полученных от дигитайзера. Он содержит последовательность точек, закодированных в соответствии со спецификацией, предоставленной объектом InkTraceFormat.

## Методы

| Метод | Описание |
| --- | --- |
| [getBrush()](#getBrush--) | Получает Brush для IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) только для чтения. |
| [getPoints()](#getPoints--) | Получает точки для IInkLine android.graphics.PointF только для чтения. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```

Получает Brush для IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) только для чтения.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public final PointF[] getPoints()
```

Получает точки для IInkLine android.graphics.PointF только для чтения.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      android.graphics.PointF[] points = traces[0].getPoints();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
android.graphics.PointF[]