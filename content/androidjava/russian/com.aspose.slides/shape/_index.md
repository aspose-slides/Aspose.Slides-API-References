---
title: Shape
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет фигуру на слайде.
type: docs
url: /ru/com.aspose.slides/shape/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

Представляет фигуру на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Определяет, является ли фигура TextHolder_PPT. |
| [getPlaceholder()](#getPlaceholder--) | Возвращает заполнитель для фигуры. |
| [removePlaceholder()](#removePlaceholder--) | Определяет, что данная фигура не является заполнителем. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Добавляет новый заполнитель, если его нет, и задает свойства заполнителя указанному. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Возвращает базовую фигуру-заполнитель (фигуру из макета и/или шаблона слайда, от которой наследуется текущая фигура). |
| [getCustomData()](#getCustomData--) | Возвращает пользовательские данные фигуры. |
| [getRawFrame()](#getRawFrame--) | Возвращает или задает свойства необработанной рамки фигуры. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Возвращает или задает свойства необработанной рамки фигуры. |
| [getFrame()](#getFrame--) | Возвращает или задает свойства рамки фигуры. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Возвращает или задает свойства рамки фигуры. |
| [getLineFormat()](#getLineFormat--) | Возвращает объект LineFormat, содержащий свойства форматирования линий для фигуры. |
| [getThreeDFormat()](#getThreeDFormat--) | Возвращает объект ThreeDFormat, содержащий свойства 3d-эффекта для фигуры. |
| [getEffectFormat()](#getEffectFormat--) | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применённые к фигуре. |
| [getFillFormat()](#getFillFormat--) | Возвращает объект FillFormat, содержащий свойства заполнения для фигуры. |
| [getImage()](#getImage--) | Возвращает эскиз фигуры. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Возвращает эскиз фигуры. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Сохраняет содержимое фигуры в файл SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Сохраняет содержимое фигуры в файл SVG. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Возвращает или задает гиперссылку, определенную для щелчка мышью. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Возвращает или задает гиперссылку, определенную для щелчка мышью. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Возвращает или задает гиперссылку, определенную для наведения мышью. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Возвращает или задает гиперссылку, определенную для наведения мышью. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Возвращает менеджер гиперссылок. |
| [getHidden()](#getHidden--) | Определяет, скрыта ли фигура. |
| [setHidden(boolean value)](#setHidden-boolean-) | Определяет, скрыта ли фигура. |
| [getZOrderPosition()](#getZOrderPosition--) | Возвращает позицию фигуры в порядке Z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Возвращает количество точек подключения на фигуре. |
| [getRotation()](#getRotation--) | Возвращает или задает количество градусов, на которое указанная фигура вращается вокруг оси Z. |
| [setRotation(float value)](#setRotation-float-) | Возвращает или задает количество градусов, на которое указанная фигура вращается вокруг оси Z. |
| [getX()](#getX--) | Получает или задает координату X верхнего левого угла фигуры в пунктах. |
| [setX(float value)](#setX-float-) | Получает или задает координату X верхнего левого угла фигуры в пунктах. |
| [getY()](#getY--) | Получает или задает координату Y верхнего левого угла фигуры в пунктах. |
| [setY(float value)](#setY-float-) | Получает или задает координату Y верхнего левого угла фигуры в пунктах. |
| [getWidth()](#getWidth--) | Получает или задает ширину фигуры в пунктах. |
| [setWidth(float value)](#setWidth-float-) | Получает или задает ширину фигуры в пунктах. |
| [getHeight()](#getHeight--) | Получает или задает высоту фигуры в пунктах. |
| [setHeight(float value)](#setHeight-float-) | Получает или задает высоту фигуры в пунктах. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Свойство определяет, как фигура будет отображаться в режиме чёрно-белого отображения. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Свойство определяет, как фигура будет отображаться в режиме чёрно-белого отображения. |
| [getUniqueId()](#getUniqueId--) | Возвращает внутренний идентификатор, ограниченный презентацией, предназначенный для использования дополнениями или другим кодом. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Возвращает уникальный идентификатор, ограниченный слайдом, который остаётся постоянным в течение жизни фигуры и позволяет PowerPoint или коду взаимодействия надёжно ссылаться на фигуру из любого места документа. |
| [getAlternativeText()](#getAlternativeText--) | Возвращает или задает альтернативный текст, связанный с фигурой. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Возвращает или задает альтернативный текст, связанный с фигурой. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Возвращает или задает заголовок альтернативного текста, связанного с фигурой. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Возвращает или задает заголовок альтернативного текста, связанный с фигурой. |
| [getName()](#getName--) | Возвращает или задает имя фигуры. |
| [setName(String value)](#setName-java.lang.String-) | Возвращает или задает имя фигуры. |
| [isDecorative()](#isDecorative--) | Получает или задает параметр «Отметить как декоративный» (Чтение/запись, boolean). |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Получает или задает параметр «Отметить как декоративный» (Чтение/запись, boolean). |
| [getShapeLock()](#getShapeLock--) | Возвращает блокировки фигуры. |
| [isGrouped()](#isGrouped--) | Определяет, сгруппирована ли фигура. |
| [getParentGroup()](#getParentGroup--) | Возвращает объект родительской группы, если фигура сгруппирована. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Получает визуальные границы фигуры, рассчитанные на основе её отрисованного содержимого. |
| [getSlide()](#getSlide--) | Возвращает родительский слайд фигуры. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию слайда. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Определяет, является ли фигура TextHolder_PPT. Только для чтения  boolean .

**Возвращает:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Возвращает заполнитель для фигуры. Возвращает null, если у фигуры нет заполнителя. Только для чтения [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Создает экземпляр класса Presentation
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Получает первый слайд
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Перебирает фигуры, чтобы найти заполнитель
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Изменяет текст в каждом заполнителе
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Сохраняет презентацию на диск
>      pres.save("output_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set Prompt Text in Placeholder.
>  
>  Presentation pres = new Presentation("Presentation2.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      for (IShape shape : slide.getSlide().getShapes()) // Перебирает слайд
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint отображает "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Добавляет субтитр
>              {
>                  text = "Add Subtitle";
>              }
>              ((IAutoShape)shape).getTextFrame().setText(text);
>              System.out.println("Placeholder with text: " + text);
>          }
>      }
>      pres.save("Placeholders_PromptText.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Определяет, что данная фигура не является заполнителем.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Добавляет новый заполнитель, если его нет, и задает свойства заполнителя указанному.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Заполнитель, из которого копировать содержимое. |

**Возвращает:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Новый #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Возвращает базовую фигуру-заполнитель (фигуру из макета и/или шаблона слайда, от которой наследуется текущая фигура).

--------------------

> ```
> // получить все (master/layout/slide) анимированные эффекты фигуры-заполнителя
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

--------------------

Возвращает null, если текущая фигура не наследуется.

**Возвращает:**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Возвращает пользовательские данные фигуры. Только для чтения [ICustomData](../../com.aspose.slides/icustomdata).

**Возвращает:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Возвращает или задает свойства необработанной рамки фигуры. Чтение/запись [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //или
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Такой код может привести к неясным ситуациям. Поэтому были добавлены ограничения на использование неопределённых значений для IShape.getFrame(). Значения x, y, width, height, flipH, flipV и rotationAngle должны быть определены (не Float.NaN и не NullableBool.NotDefined). Пример кода выше теперь бросает исключение ArgumentException exception.
>  //Это относится к следующим случаям:
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
>  //Но свойства кадра IShape.RawFrame могут быть неопределёнными. Это имеет смысл, когда фигура связана с заполнителем. Тогда неопределённые значения кадра фигуры переопределяются из родительской фигуры-заполнителя. Если для этой фигуры нет родительского заполнителя, то она использует значения по умолчанию при вычислении эффективного кадра на основе IShape.RawFrame. Значения по умолчанию: 0 и NullableBool.False для x, y, width, height, flipH, flipV и rotationAngle. Например:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // теперь фигура наследует x, y, height, flipH, flipV значения из заполнителя и переопределяет width=100 и rotationAngle=0.{code}
> ```


**Возвращает:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Возвращает или задает свойства необработанной рамки фигуры. Чтение/запись [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //или
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Такой код может привести к неясным ситуациям. Поэтому были введены ограничения на использование неопределённых значений для IShape.getFrame(). Значения x, y, width, height, flipH, flipV и rotationAngle должны быть определены (не Float.NaN и не NullableBool.NotDefined). Пример выше теперь бросает ArgumentException exception.
>  //Это относится к следующим случаям:
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
>  //Но свойства кадра IShape.RawFrame могут быть неопределёнными. Это имеет смысл, когда фигура связана с заполнителем. Тогда неопределённые значения кадра фигуры переопределяются родительским заполнителем. Если для этой фигуры нет родительского заполнителя, то она использует значения по умолчанию при вычислении эффективного кадра на основе IShape.RawFrame. Значения по умолчанию: 0 и NullableBool.False для x, y, width, height, flipH, flipV и rotationAngle. Например:
>  IShape shape = ...; // фигура связана с заполнителем
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // теперь фигура наследует значения x, y, height, flipH, flipV из заполнителя и переопределяет width=100 и rotationAngle=0.{code}
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Возвращает или задает свойства рамки фигуры. Чтение/запись [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Значение каждого свойства возвращаемого экземпляра IShapeFrame определено (не NaN и не NotDefined). Значение каждого свойства присваиваемого экземпляра IShapeFrame также должно быть определено (не NaN и не NotDefined). Можно задавать неопределённые значения для свойств экземпляра RawFrame.

**Возвращает:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Возвращает или задает свойства рамки фигуры. Чтение/запись [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Значение каждого свойства возвращаемого экземпляра IShapeFrame определено (не NaN и не NotDefined). Значение каждого свойства присваиваемого экземпляра IShapeFrame также должно быть определено (не NaN и не NotDefined). Можно задавать неопределённые значения для свойств экземпляра RawFrame.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Возвращает объект LineFormat, содержащий свойства форматирования линий для фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств линии. Только для чтения [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращает:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Возвращает объект ThreeDFormat, содержащий свойства 3d-эффекта для фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет 3d-свойств. Только для чтения [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Возвращает:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Возвращает объект EffectFormat, содержащий пиксельные эффекты, применённые к фигуре. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств эффекта. Только для чтения [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Возвращает:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Возвращает объект FillFormat, содержащий свойства заполнения для фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств заполнения. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

--------------------

> ```
> The following example shows how to change the accent color for a theme of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      shape.getFillFormat().setFillType(FillType.Solid);
>      shape.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example demonstrates how to obtain palette colors from the main theme color and then used in shapes.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Акцент 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Акцент 4, светлее 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Акцент 4, светлее 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Акцент 4, светлее 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Акцент 4, темнее 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Акцент 4, темнее 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

Возвращает эскиз фигуры. По умолчанию используется тип ShapeThumbnailBounds.Shape.

**Возвращает:**
[IImage](../../com.aspose.slides/iimage) - Эскиз фигуры.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Возвращает эскиз фигуры.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bounds | int | Тип границ эскиза фигуры. |
| scaleX | float | Масштаб по оси X |
| scaleY | float | Масштаб по оси Y |

**Возвращает:**
[IImage](../../com.aspose.slides/iimage) - Эскиз фигуры или null, если используется ShapeThumbnailBounds.Appearance и у фигуры нет видимых элементов.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Сохраняет содержимое фигуры в файл SVG.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Целевой поток |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Сохраняет содержимое фигуры в файл SVG.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Целевой поток |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Параметры генерации SVG |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Возвращает или задает гиперссылку, определенную для щелчка мышью. Чтение/запись [IHyperlink](../../com.aspose.slides/ihyperlink).

**Возвращает:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Возвращает или задает гиперссылка, определенную для щелчка мышью. Чтение/запись [IHyperlink](../../com.aspose.slides/ihyperlink).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Возвращает или задает гиперссылку, определенную для наведения мышью. Чтение/запись [IHyperlink](../../com.aspose.slides/ihyperlink).

**Возвращает:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Возвращает или задает гиперссылку, определенную для наведения мышью. Чтение/запись [IHyperlink](../../com.aspose.slides/ihyperlink).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Возвращает менеджер гиперссылок. Только для чтения [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Возвращает:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Определяет, скрыта ли фигура. Чтение/запись  boolean .

**Возвращает:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Определяет, скрыта ли фигура. Чтение/запись  boolean .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Возвращает позицию фигуры в порядке Z. Shapes[0] возвращает фигуру, находящуюся сзади в порядке Z, а Shapes[Shapes.Count - 1] — фигур��, находящуюся спереди. Только для чтения  int .

**Возвращает:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Возвращает количество точек подключения на фигуре. Только для чтения  int .

**Возвращает:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Возвращает или задает количество градусов, на которое указанная фигура вращается вокруг оси Z. Положительное значение — вращение по часовой стрелке; отрицательное — против часовой стрелки. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено (не Float.NaN). Присваиваемое значение должно быть определено (не Float.NaN). Можно задавать неопределённые значения для свойств экземпляра RawFrame.

**Возвращает:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

Возвращает или задает количество градусов, на которое указанная фигура вращается вокруг оси Z. Положительное значение — вращение по часовой стрелке; отрицательное — против часовой стрелки. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено (не Float.NaN). Присваиваемое значение должно быть определено (не Float.NaN). Можно задавать неопределённые значения для свойств экземпляра RawFrame.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Получает или задает координату X верхнего левого угла фигуры в пунктах. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено и никогда не является Float.NaN. Присваиваемое значение также должно быть определено; Float.NaN задаётся только свойствам экземпляра RawFrame.

**Возвращает:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Получает или задает координату X верхнего левого угла фигуры в пунктах. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено и никогда не является Float.NaN. Присваиваемое значение также должно быть определено; Float.NaN задаётся только свойствам экземпляра RawFrame.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Получает или задает координату Y верхнего левого угла фигуры в пунктах. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено и никогда не является Float.NaN. Присваиваемое значение также должно быть определено; Float.NaN задаётся только свойствам экземпляра RawFrame.

**Возвращает:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Получает или задает координату Y верхнего левого угла фигуры в пунктах. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено и никогда не является Float.NaN. Присваиваемое значение также должно быть определено; Float.NaN задаётся только свойствам экземпляра RawFrame.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Получает или задает ширину фигуры в пунктах. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено и никогда не является Float.NaN. Присваиваемое значение также должно быть определено; Float.NaN задаётся только свойствам экземпляра RawFrame.

**Возвращает:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Получает или задает ширину фигуры в пунктах. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено и никогда не является Float.NaN. Присваиваемое значение также должно быть определено; Float.NaN задаётся только свойствам экземпляра RawFrame.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Получает или задает высоту фигуры в пунктах. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено и никогда не является Float.NaN. Присваиваемое значение также должно быть определено; Float.NaN задаётся только свойствам экземпляра RawFrame.

**Возвращает:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Получает или задает высоту фигуры в пунктах. Чтение/запись float.

--------------------

Возвращаемое значение всегда определено и никогда не является Float.NaN. Присваиваемое значение также должно быть определено; Float.NaN задаётся только свойствам экземпляра RawFrame.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

Свойство определяет, как фигура будет отображаться в режиме чёрно-белого отображения. Чтение/запись [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Возвращает:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

Свойство определяет, как фигура будет отображаться в режиме чёрно-белого отображения. Чтение/запись [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Возвращает внутренний идентификатор, ограниченный презентацией, предназначенный для использования дополнениями или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя использовать как постоянный уникальный ключ. Только для чтения long. См. также #getOfficeInteropShapeId.getOfficeInteropShapeId.

**Возвращает:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Возвращает уникальный идентификатор, ограниченный слайдом, который остаётся постоянным в течение жизни фигуры и позволяет PowerPoint или коду взаимодействия надёжно ссылаться на фигуру из любого места документа. Только для чтения long. См. также #getUniqueId.getUniqueId.

**Возвращает:**
long

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Возвращает или задает альтернативный текст, связанный с фигурой. Чтение/запись String.

**Возвращает:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Возвращает или задает альтернативный текст, связанный с фигурой. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Возвращает или задает заголовок альтернативного текста, связанный с фигурой. Чтение/запись String.

**Возвращает:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Возвращает или задает заголовок альтернативного текста, связанный с фигурой. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Возвращает или задает имя фигуры. Должно быть не null. При необходимости используйте пустую строку. Чтение/запись String.

**Возвращает:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Возвращает или задает имя фигуры. Должно быть не null. При необходимости используйте пустую строку. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Получает или задает параметр «Отметить как декоративный» (Чтение/запись, boolean).

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
public final void setDecorative(boolean value)
```

Получает или задает параметр «Отметить как декоративный» (Чтение/запись, boolean).

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
public IBaseShapeLock getShapeLock()
```

Возвращает блокировки фигуры. Только для чтения [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Возвращает:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Определяет, сгруппирована ли фигура. Только для чтения boolean.

--------------------

Свойство #getParentGroup.getParentGroup возвращает объект родительской группы, если фигура сгруппирована.

**Возвращает:**
boolean

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Возвращает объект родительской группы, если фигура сгруппирована. В противном случае возвращает null. Только для чтения [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Свойство #isGrouped.isGrouped определяет, сгруппирована ли фигура.

**Возвращает:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращает:**
com.aspose.slides.IDOMObject

### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

Получает визуальные границы фигуры, рассчитанные на основе её отрисованного содержимого.

**Возвращает:**
android.graphics.RectF - объект android.graphics.RectF, представляющий визуальные границы фигуры в координатах слайда.

--------------------

Возвращаемый прямоугольник представляет оси-выравненные границы всего содержимого, создаваемого фигурой во время отрисовки в пространстве координат слайда. Эти границы могут отличаться от модельных границ фигуры #getX.getX/#setX(float).setX(float), #getY.getY/#setY(float).setY(float), #getWidth.getWidth/#setWidth(float).setWidth(float), #getHeight.getHeight/#setHeight(float).setHeight(float) и могут содержать отрицательные координаты, если отрисованное содержимое выходит за пределы начала слайда. В визуальные границы учитываются такие аспекты отрисовки, как трансформации (например, вращение), ширина и соединения штрихов, компоновка и переполнение текста, геометрия SmartArt и другие эффекты компоновки, влияющие на окончательный вид фигуры. Возвращаемые границы не обрезаются до прямоугольника слайда.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает родительский слайд фигуры. Только для чтения [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Возвращает:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает родительскую презентацию слайда. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращает:**
[IPresentation](../../com.aspose.slides/ipresentation)