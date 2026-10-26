---
title: ISectionZoomFrame
second_title: Aspose.Slides для Android через справку Java API
description: Представляет объект Section Zoom в слайде.
type: docs
url: /ru/com.aspose.slides/isectionzoomframe/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Представляет объект Section Zoom на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Получает или задает объект раздела, к которому привязан объект Section Zoom. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Получает или задает объект раздела, к которому привязан объект Section Zoom. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```

Получает или задает объект раздела, к которому привязан объект Section Zoom. Чтение/запись [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Этот пример демонстрирует изменение целевого раздела и создает новое изображение для объекта Section Zoom:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```

Получает или задает объект раздела, к которому привязан объект Section Zoom. Чтение/запись [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Этот пример демонстрирует изменение целевого раздела и создает новое изображение для объекта Section Zoom:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |