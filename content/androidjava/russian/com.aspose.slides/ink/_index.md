---
title: Ink
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет объект чернил на слайде.
type: docs
url: /ru/com.aspose.slides/ink/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Представляет объект чернил на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [getTraces()](#getTraces--) | Получает все следы, содержащиеся в элементе IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | Получает коллекцию пользовательских изображений, используемых для имитации визуальных эффектов кистей чернил. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```


Получает все следы, содержащиеся в элементе IInk [IInkTrace](../../com.aspose.slides/iinktrace). Только для чтения.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращает:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```


Получает коллекцию пользовательских изображений, используемых для имитации визуальных эффектов кистей чернил. Эти изображения используются при рендеринге чернил с определёнными значениями [InkEffectType](../../com.aspose.slides/inkeffecttype), например Galaxy, Rainbow и т.д. Предоставив свои собственные изображения, вы можете контролировать, как выглядит каждый эффект чернила.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```

--------------------

Это свойство позволяет заменять текстуры эффектов чернил по умолчанию пользовательскими, что особенно полезно, когда стандартные ресурсы ограничены лицензией или недоступны во время выполнения. Каждая запись в словаре должна связывать значение [InkEffectType](../../com.aspose.slides/inkeffecttype) с соответствующим объектом [IImage](../../com.aspose.slides/iimage) (например, Bitmap или интерфейс изображения Aspose).

**Возвращает:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>