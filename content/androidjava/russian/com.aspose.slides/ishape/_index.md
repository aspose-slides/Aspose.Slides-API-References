---
title: IShape
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет форму на слайде.
type: docs
url: /ru/com.aspose.slides/ishape/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Представляет форму на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Определяет, является ли форма TextHolder. |
| [getPlaceholder()](#getPlaceholder--) | Возвращает заполнитель для формы. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Добавляет новый заполнитель, если его нет, и задает свойства заполнителя указанному. |
| [removePlaceholder()](#removePlaceholder--) | Определяет, что эта форма не является заполнителем. |
| [getCustomData()](#getCustomData--) | Возвращает пользовательские данные формы. |
| [getRawFrame()](#getRawFrame--) | Возвращает или задает свойства необработанного кадра формы. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Возвращает или задает свойства необработанного кадра формы. |
| [getFrame()](#getFrame--) | Возвращает или задает свойства кадра формы. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Возвращает или задает свойства кадра формы. |
| [getLineFormat()](#getLineFormat--) | Возвращает объект LineFormat, содержащий свойства форматирования линий для формы. |
| [getThreeDFormat()](#getThreeDFormat--) | Возвращает объект ThreeDFormat, содержащий свойства форматирования линий для формы. |
| [getEffectFormat()](#getEffectFormat--) | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применённые к форме. |
| [getFillFormat()](#getFillFormat--) | Возвращает объект FillFormat, содержащий свойства заливки формы. |
| [getImage()](#getImage--) | Возвращает миниатюру формы. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Возвращает миниатюру формы. |
| [getHidden()](#getHidden--) | Определяет, скрыта ли форма. |
| [setHidden(boolean value)](#setHidden-boolean-) | Определяет, скрыта ли форма. |
| [getZOrderPosition()](#getZOrderPosition--) | Возвращает позицию формы в порядке z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Возвращает количество точек соединения на форме. |
| [getRotation()](#getRotation--) | Возвращает или задает количество градусов, на которое указанная форма повернута вокруг оси z. |
| [setRotation(float value)](#setRotation-float-) | Возвращает или задает количество градусов, на которое указанная форма повернута вокруг оси z. |
| [getX()](#getX--) | Получает или задает координату x верхнего левого угла формы, измеряемую в пунктах. |
| [setX(float value)](#setX-float-) | Получает или задает координату x верхнего левого угла формы, измеряемую в пунктах. |
| [getY()](#getY--) | Получает или задает координату y верхнего левого угла формы, измеряемую в пунктах. |
| [setY(float value)](#setY-float-) | Получает или задает координату y верхнего левого угла формы, измеряемую в пунктах. |
| [getWidth()](#getWidth--) | Получает или задает ширину формы, измеряемую в пунктах. |
| [setWidth(float value)](#setWidth-float-) | Получает или задает ширину формы, измеряемую в пунктах. |
| [getHeight()](#getHeight--) | Получает или задает высоту формы, измеряемую в пунктах. |
| [setHeight(float value)](#setHeight-float-) | Получает или задает высоту формы, измеряемую в пунктах. |
| [getAlternativeText()](#getAlternativeText--) | Возвращает или задает альтернативный текст, связанный с формой. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Возвращает или задает альтернативный текст, связанный с формой. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Возвращает или задает заголовок альтернативного текста, связанный с формой. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Возвращает или задает заголовок альтернативного текста, связанный с формой. |
| [getName()](#getName--) | Возвращает или задает имя формы. |
| [setName(String value)](#setName-java.lang.String-) | Возвращает или задает имя формы. |
| [isDecorative()](#isDecorative--) | Получает или задает параметр 'Mark as decorative' (boolean) чтение/запись. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Получает или задает параметр 'Mark as decorative' (boolean) чтение/запись. |
| [getShapeLock()](#getShapeLock--) | Возвращает блокировки формы. |
| [getUniqueId()](#getUniqueId--) | Возвращает внутренний идентификатор, ограниченный презентацией, предназначенный для использования надстройками или другим кодом. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Возвращает уникальный идентификатор, ограниченный слайдом, который остаётся постоянным в течение жизни формы и позволяет PowerPoint или коду interop надёжно ссылаться на форму из любой части документа. |
| [isGrouped()](#isGrouped--) | Определяет, сгруппирована ли форма. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Свойство определяет, как форма будет отображаться в черно-белом режиме. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Свойство определяет, как форма будет отображаться в черно-белом режиме. |
| [getParentGroup()](#getParentGroup--) | Возвращает объект родительской группы GroupShape, если форма сгруппирована. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Сохраняет содержимое формы в файл SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Сохраняет содержимое формы в файл SVG. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Возвращает базовую форму-заполнитель (форму из макета и/или слайда-шаблона, от которой наследуется текущая форма). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Определяет, является ли форма TextHolder. Только для чтения boolean.

**Возвращает:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Возвращает заполнитель для формы. Только для чтения [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Возвращает:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Добавляет новый заполнитель, если его нет, и задает свойства заполнителя указанному.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Заполнитель, из которого копировать содержимое. |

**Возвращает:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Определяет, что эта форма не является заполнителем.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Возвращает пользовательские данные формы. Только для чтения [ICustomData](../../com.aspose.slides/icustomdata).

**Возвращает:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Возвращает или задает свойства необработанного кадра формы. Чтение/запись [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //или
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Такой код может привести к неясным ситуациям. Поэтому были добавлены ограничения на использование неопределённых значений для IShape.getFrame(). Значения x, y, width, height, flipH, flipV и rotationAngle должны быть определены (не Float.NaN и не NullableBool.NotDefined). Приведённый выше пример кода теперь бросает исключение ArgumentException.
>  //Это применимо к следующим случаям:
>  IShape shape = ...;
>  shape.setFrame(...); // не может быть неопределённым
>  IShapeCollection shapes = ...;
>  // параметры x, y, width, height не могут быть Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // форма связана с заполнителем
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // теперь форма наследует значения x, y, height, flipH, flipV из заполнителя и переопределяет width=100 и rotationAngle=0.
```

**Возвращает:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Возвращает или задает свойства необработанного кадра формы. Чтение/запись [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //или
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Такой код может привести к неясным ситуациям. Поэтому были добавлены ограничения на использование неопределённых значений для IShape.getFrame(). Значения x, y, width, height, flipH, flipV и rotationAngle должны быть определены (не Float.NaN и не NullableBool.NotDefined). Приведённый выше пример кода теперь бросает исключение ArgumentException.
>  //Это применимо к следующим случаям:
>  IShape shape = ...;
>  shape.setFrame(...); // не может быть неопределённым
>  IShapeCollection shapes = ...;
>  // параметры x, y, width, height не могут быть Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // форма связана с заполнителем
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // теперь форма наследует значения x, y, height, flipH, flipV из заполнителя и переопределяет width=100 и rotationAngle=0.
```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Возвращает или задает свойства кадра формы. Чтение/запись [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Значение каждого свойства возвращённого экземпляра IShapeFrame не является неопределённым (не NaN и не NotDefined). Значение каждого свойства присвоенного экземпляра IShapeFrame должно быть определённым (не NaN и не NotDefined). Для свойств экземпляра RawFrame можно устанавливать неопределённые значения.

**Возвращает:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Возвращает или задает свойства кадра формы. Чтение/запись [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Значение каждого свойства возвращённого экземпляра IShapeFrame не является неопределённым (не NaN и не NotDefined). Значение каждого свойства присвоенного экземпляра IShapeFrame должно быть определённым (не NaN и не NotDefined). Для свойств экземпляра RawFrame можно устанавливать неопределённые значения.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Возвращает объект LineFormat, содержащий свойства форматирования линий для формы. Только для чтения [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращает:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Возвращает объект ThreeDFormat, содержащий свойства форматирования линий для формы. Только для чтения [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Возвращает:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Возвращает объект EffectFormat, содержащий пиксельные эффекты, применённые к форме. Только для чтения [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Возвращает:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Возвращает объект FillFormat, содержащий свойства заливки формы. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращает:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Возвращает миниатюру формы. По умолчанию используется тип границ ShapeThumbnailBounds.Shape.

**Возвращает:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Возвращает миниатюру формы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bounds | int | Тип границ миниатюры формы. |
| scaleX | float | Масштаб по X |
| scaleY | float | Масштаб по Y |

**Возвращает:**
[IImage](../../com.aspose.slides/iimage) - Миниатюра формы или null, если используется ShapeThumbnailBounds.Appearance и у формы нет видимых элементов.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Определяет, скрыта ли форма. Чтение/запись boolean.

**Возвращает:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Определяет, скрыта ли форма. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Возвращает позицию формы в порядке z. Shapes[0] возвращает форму в задней части порядка z, а Shapes[Shapes.Count - 1] возвращает форму в передней части порядка z. Только для чтения int.

**Возвращает:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Возвращает количество точек соединения на форме. Только для чтения int.

**Возвращает:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Возвращает или задает количество градусов, на которое указанная форма повернута вокруг оси z. Положительное значение означает вращение по часовой стрелке; отрицательное — против часовой стрелки. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено (не Float.NaN). Присвоенное значение должно быть определённым (не Float.NaN). Для свойств экземпляра RawFrame можно устанавливать неопределённые значения.

**Возвращает:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Возвращает или задает количество градусов, на которое указанная форма повернута вокруг оси z. Положительное значение означает вращение по часовой стрелке; отрицательное — против часовой стрелки. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено (не Float.NaN). Присвоенное значение должно быть определённым (не Float.NaN). Для свойств экземпляра RawFrame можно устанавливать неопределённые значения.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Получает или задает координату x верхнего левого угла формы, измеряемую в пунктах. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено и никогда не равно Float.NaN. Присвоенное значение также должно быть определённым; присваивайте Float.NaN только свойствам экземпляра RawFrame.

**Возвращает:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Получает или задает координату x верхнего левого угла формы, измеряемую в пунктах. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено и никогда не равно Float.NaN. Присвоенное значение также должно быть определённым; присваивайте Float.NaN только свойствам экземпляра RawFrame.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Получает или задает координату y верхнего левого угла формы, измеряемую в пунктах. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено и никогда не равно Float.NaN. Присвоенное значение также должно быть определённым; присваивайте Float.NaN только свойствам экземпляра RawFrame.

**Возвращает:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Получает или задает координату y верхнего левого угла формы, измеряемую в пунктах. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено и никогда не равно Float.NaN. Присвоенное значение также должно быть определённым; присваивайте Float.NaN только свойствам экземпляра RawFrame.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Получает или задает ширину формы, измеряемую в пунктах. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено и никогда не равно Float.NaN. Присвоенное значение также должно быть определённым; присваивайте Float.NaN только свойствам экземпляра RawFrame.

**Возвращает:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Получает или задает ширину формы, измеряемую в пунктах. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено и никогда не равно Float.NaN. Присвоенное значение также должно быть определённым; присваивайте Float.NaN только свойствам экземпляра RawFrame.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Получает или задает высоту формы, измеряемую в пунктах. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено и никогда не равно Float.NaN. Присвоенное значение также должно быть определённым; присваивайте Float.NaN только свойствам экземпляра RawFrame.

**Возвращает:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Получает или задает высоту формы, измеряемую в пунктах. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено и никогда не равно Float.NaN. Присвоенное значение также должно быть определённым; присваивайте Float.NaN только свойствам экземпляра RawFrame.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Возвращает или задает альтернативный текст, связанный с формой. Чтение/запись String.

**Возвращает:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Возвращает или задает альтернативный текст, связанный с формой. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Возвращает или задает заголовок альтернативного текста, связанный с формой. Чтение/запись String.

**Возвращает:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Возвращает или задает заголовок альтернативного текста, связанный с формой. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Возвращает или задает имя формы. Чтение/запись String.

**Возвращает:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Возвращает или задает имя формы. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Получает или задает параметр 'Mark as decorative' (boolean) чтение/запись.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```

Получает или задает параметр 'Mark as decorative' (boolean) чтение/запись.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

Возвращает блокировки формы. Только для чтения [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Возвращает:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

Возвращает внутренний идентификатор, ограниченный презентацией, предназначенный для использования надстройками или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя считать постоянным уникальным ключом. Только для чтения long. См. также \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Возвращает:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

Возвращает уникальный идентификатор, ограниченный слайдом, который остаётся постоянным в течение жизни формы и позволяет PowerPoint или коду interop надёжно ссылаться на форму из любой части документа. Только для чтения long. См. также \#getUniqueId.getUniqueId.

**Возвращает:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Определяет, сгруппирована ли форма. Только для чтения boolean.

Свойство \#getParentGroup.getParentGroup возвращает объект родительской группы GroupShape, если форма сгруппирована.

**Возвращает:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Свойство определяет, как форма будет отображаться в черно-белом режиме. Чтение/запись [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Возвращает:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Свойство определяет, как форма будет отображаться в черно-белом режиме. Чтение/запись [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Возвращает объект родительской группы GroupShape, если форма сгруппирована. В противном случае возвращает null. Только для чтения [IGroupShape](../../com.aspose.slides/igroupshape).

Свойство \#isGrouped.isGrouped определяет, сгруппирована ли форма.

**Возвращает:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Сохраняет содержимое формы в файл SVG.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Целевой поток |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Сохраняет содержимое формы в файл SVG.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Целевой поток |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Параметры генерации SVG |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

Возвращает базовую форму-заполнитель (форму из макета и/или слайда-шаблона, от которой наследуется текущая форма).

--------------------

> ```
> // получить все (master/layout/slide) анимированные эффекты заполнителя формы
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape = slide.getShapes().get_Item(0);
>      IEffect[] shapeEffects = slide.getTimeline().getMainSequence().getEffectsByShape(shape);
>      IShape layoutShape = shape.getBasePlaceholder();
>      IEffect[] layoutShapeEffects = slide.getLayoutSlide().getTimeline().getMainSequence().getEffectsByShape(layoutShape);
>      IShape masterShape = layoutShape.getBasePlaceholder();
>      IEffect[] masterShapeEffects = slide.getLayoutSlide().getMasterSlide().getTimeline().getMainSequence().getEffectsByShape(masterShape);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Возвращается null, если текущая форма не наследуется.

**Возвращает:**
[IShape](../../com.aspose.slides/ishape)