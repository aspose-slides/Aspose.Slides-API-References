---
title: IViewProperties
second_title: Aspose.Slides for Java API Reference
description: Свойства представления презентации.
type: docs
url: /ru/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Свойства представления презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getLastView()](#getLastView--) | Указывает режим просмотра, который использовался при последнем сохранении документа презентации. |
| [setLastView(int value)](#setLastView-int-) | Указывает режим просмотра, который использовался при последнем сохранении документа презентации. |
| [getShowComments()](#getShowComments--) | Указывает, должны ли отображаться комментарии к слайдам. |
| [setShowComments(byte value)](#setShowComments-byte-) | Указывает, должны ли отображаться комментарии к слайдам. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Указывает общие свойства представления, связанные с режимом просмотра слайдов. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Указывает общие свойства представления, связанные с режимом просмотра заметок. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Представляет свойства обычного представления. |
| [getGridSpacing()](#getGridSpacing--) | Возвращает или задает интервал сетки, который следует использовать для сетки, лежащей в основе документа презентации, в пунктах. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Возвращает или задает интервал сетки, который следует использовать для сетки, лежащей в основе документа презентации, в пунктах. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Указывает режим просмотра, который использовался при последнем сохранении документа презентации. Read/write [ViewType](../../com.aspose.slides/viewtype).

**Возвращаемое значение:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Указывает режим просмотра, который использовался при последнем сохранении документа презентации. Read/write [ViewType](../../com.aspose.slides/viewtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Указывает, должны ли отображаться комментарии к слайдам. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Указывает, должны ли отображаться комментарии к слайдам. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Указывает общие свойства представления, связанные с режимом просмотра слайдов. Read-only [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Возвращаемое значение:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Указывает общие свойства представления, связанные с режимом просмотра заметок. Read-only [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Возвращаемое значение:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Представляет свойства обычного представления. Обычное представление состоит из трёх областей содержимого: самого слайда, боковой области содержимого и нижней области содержимого. Read-only [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Возвращаемое значение:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Возвращает или задает интервал сетки, который следует использовать для сетки, лежащей в основе документа презентации, в пунктах. Read/write float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Значение интервала сетки должно быть положительным числом. Типичный диапазон значений — от 1 мм (2.8349607 пунктов) до 2 дюймов (144 пункта).

**Возвращаемое значение:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Возвращает или задает интервал сетки, который следует использовать для сетки, лежащей в основе документа презентации, в пунктах. Read/write float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Значение интервала сетки должно быть положительным числом. Типичный диапазон значений — от 1 мм (2.8349607 пунктов) до 2 дюймов (144 пункта).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |