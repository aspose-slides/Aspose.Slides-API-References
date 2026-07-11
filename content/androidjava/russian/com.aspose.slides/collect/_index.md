---
title: Collect
second_title: Aspose.Slides для Android через Java API
description: Представляет группу методов, предназначенных для сбора объектных моделей разных типов из .
type: docs
url: /ru/com.aspose.slides/collect/
---
**Наследование:**
java.lang.Object
```
public class Collect
```

Представляет группу методов, предназначенных для сбора объектных моделей разных типов из [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... изменить форматирование фигуры или другие свойства
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Collect()](#Collect--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Собирает все экземпляры [Shape](../../com.aspose.slides/shape) в [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```

### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```

Собирает все экземпляры [Shape](../../com.aspose.slides/shape) в [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // если фигура является AutoShape, добавить черную сплошную рамку
>          if (shape instanceof AutoShape)
>          {
>              AutoShape autoShape = (AutoShape)shape;
>              autoShape.getLineFormat().setStyle(LineStyle.Single);
>              autoShape.getLineFormat().setWidth(10f);
>              autoShape.getLineFormat().getFillFormat().setFillType(FillType.Solid);
>              autoShape.getLineFormat().getFillFormat().getSolidFillColor().setColor(Color.black);
>          }
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Презентация для сбора фигур |

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Коллекция всех фигур, содержащихся в презентации