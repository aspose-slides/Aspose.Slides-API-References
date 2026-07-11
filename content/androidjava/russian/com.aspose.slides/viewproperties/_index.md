---
title: ViewProperties
second_title: Aspose.Slides для Android через Java API
description: Свойства представления на уровне всей презентации.
type: docs
url: /ru/com.aspose.slides/viewproperties/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Свойства представления на уровне всей презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getLastView()](#getLastView--) | Указывает режим просмотра, использованный при последнем сохранении документа презентации. |
| [setLastView(int value)](#setLastView-int-) | Указывает режим просмотра, использованный при последнем сохранении документа презентации. |
| [getShowComments()](#getShowComments--) | Указывает, следует ли отображать комментарии к слайдам. |
| [setShowComments(byte value)](#setShowComments-byte-) | Указывает, следует ли отображать комментарии к слайдам. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Представляет свойства обычного просмотра. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Указывает общие свойства просмотра, связанные с режимом просмотра слайдов. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Указывает общие свойства просмотра, связанные с режимом просмотра заметок. |
| [getGridSpacing()](#getGridSpacing--) | Возвращает или задает интервал сетки, который следует использовать для сетки, лежащей в основе документа презентации, в пунктах. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Возвращает или задает интервал сетки, который следует использовать для сетки, лежащей в основе документа презентации, в пунктах. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```


Указывает режим просмотра, использованный при последнем сохранении документа презентации. Чтение/запись [ViewType](../../com.aspose.slides/viewtype).

**Возвращает:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```


Указывает режим просмотра, использованный при последнем сохранении документа презентации. Чтение/запись [ViewType](../../com.aspose.slides/viewtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```


Указывает, следует ли отображать комментарии к слайдам. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```


Указывает, следует ли отображать комментарии к слайдам. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```


Представляет свойства обычного просмотра. Обычный просмотр состоит из трех областей содержимого: самого слайда, боковой области содержимого и нижней области содержимого. Только для чтения [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Возвращает:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```


Указывает общие свойства просмотра, связанные с режимом просмотра слайдов. Только для чтения [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Возвращает:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```


Указывает общие свойства просмотра, связанные с режимом просмотра заметок. Только для чтения [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Возвращает:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```


Возвращает или задает интервал сетки, который следует использовать для сетки, лежащей в основе документа презентации, в пунктах. Чтение/запись float.

--------------------

> ```
> Следующий пример кода показывает, как изменить интервал сетки в презентации PowerPoint.
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

Значение интервала сетки должно быть положительным числом. Типичный диапазон значений — от 1 мм (2,8349607 пункта) до 2 дюймов (144 пункта).

**Возвращает:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```


Возвращает или задает интервал сетки, который следует использовать для сетки, лежащей в основе документа презентации, в пунктах. Чтение/запись float.

--------------------

> ```
> Следующий пример кода показывает, как изменить интервал сетки в презентации PowerPoint.
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

Значение интервала сетки должно быть положительным числом. Типичный диапазон значений — от 1 мм (2,8349607 пункта) до 2 дюймов (144 пункта).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращает:**
com.aspose.slides.IDOMObject