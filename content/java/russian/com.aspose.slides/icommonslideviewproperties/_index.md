---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Java API Reference
description: Represents common slide view properties.
type: docs
url: /ru/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Представляет общие свойства просмотра слайда.
## Методы

| Метод | Описание |
| --- | --- |
| [getScale()](#getScale--) | Указывает коэффициент масштабирования просмотра в процентах. |
| [setScale(int value)](#setScale-int-) | Указывает коэффициент масштабирования просмотра в процентах. |
| [getVariableScale()](#getVariableScale--) | Указывает, что содержимое просмотра должно автоматически масштабироваться для оптимального размещения в текущем размере окна. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Указывает, что содержимое просмотра должно автоматически масштабироваться для оптимального размещения в текущем размере окна. |
| [getDrawingGuides()](#getDrawingGuides--) | Возвращает коллекцию направляющих рисования. |

### getScale() {#getScale--}
```
public abstract int getScale()
```

Указывает коэффициент масштабирования просмотра в процентах. Чтение/запись int.

**Возвращает:**
int

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

Указывает коэффициент масштабирования просмотра в процентах. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

Указывает, что содержимое просмотра должно автоматически масштабироваться для оптимального размещения в текущем размере окна. Чтение/запись boolean.

**Возвращает:**
boolean

### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

Указывает, что содержимое просмотра должно автоматически масштабироваться для оптимального размещения в текущем размере окна. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Возвращает коллекцию направляющих рисования. Только для чтения [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Добавление новой вертикальной направляющей справа от центра слайда
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // Добавление новой горизонтальной направляющей ниже центра слайда
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)