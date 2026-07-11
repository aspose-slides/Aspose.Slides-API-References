---
title: IInk
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет объект чернил на слайде.
type: docs
url: /ru/com.aspose.slides/iink/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Представляет объект чернил на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [getTraces()](#getTraces--) | Получает все трассы, содержащиеся в элементе IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```


Получает все трассы, содержащиеся в элементе IInk [IInkTrace](../../com.aspose.slides/iinktrace). Только для чтения.

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


**Возвращаемое значение:**
com.aspose.slides.IInkTrace[]