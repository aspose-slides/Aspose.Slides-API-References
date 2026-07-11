---
title: CommonSlideViewProperties
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет общие свойства представления слайда.
type: docs
url: /ru/com.aspose.slides/commonslideviewproperties/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Представляет общие свойства представления слайда.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Создайте объект Presentation, представляющий файл презентации
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Установка свойств представления презентации
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Значение масштабирования в процентах для представления слайда
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Значение масштабирования в процентах для представления заметок
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getScale()](#getScale--) | Указывает коэффициент масштабирования представления в процентах. |
| [setScale(int value)](#setScale-int-) | Указывает коэффициент масштабирования представления в процентах. |
| [getVariableScale()](#getVariableScale--) | Указывает, что содержимое представления должно автоматически масштабироваться для оптимального соответствия текущему размеру окна. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Указывает, что содержимое представления должно автоматически масштабироваться для оптимального соответствия текущему размеру окна. |
| [getDrawingGuides()](#getDrawingGuides--) | Возвращает коллекцию направляющих черчения. |
### getScale() {#getScale--}
```
public final int getScale()
```


Указывает коэффициент масштабирования представления в процентах. Чтение/запись int.

**Возвращаемое значение:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Указывает коэффициент масштабирования представления в процентах. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```


Указывает, что содержимое представления должно автоматически масштабироваться для оптимального соответствия текущему размеру окна. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```


Указывает, что содержимое представления должно автоматически масштабироваться для оптимального соответствия текущему размеру окна. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Возвращает коллекцию направляющих черчения. Только для чтения [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Добавление новой вертикальной направляющей справа от центра слайда
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Добавление новой горизонтальной направляющей ниже центра слайда
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)