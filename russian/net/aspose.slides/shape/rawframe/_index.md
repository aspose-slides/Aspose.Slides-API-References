---
title: RawFrame
second_title: Справочник по API Aspose.Slides для .NET
description: Возвращает или устанавливает свойства необработанного фрейма формы. Чтение/записьIShapeFrameaspose.slides/ishapeframe.
type: docs
weight: 220
url: /ru/net/aspose.slides/shape/rawframe/
---
## Shape.RawFrame property

Возвращает или устанавливает свойства необработанного фрейма формы. Чтение/запись[`IShapeFrame`](../../ishapeframe).

```csharp
public IShapeFrame RawFrame { get; set; }
```

### Примеры

Код, который пытается назначить неопределенный кадр IShape.Frame в общем случае не имеет смысла ( особенно в случае, когда родительский GroupShape многократно вложен в другие GroupShape-ы). Например: или &lt;code&gt; slide.Shapes.AddAutoShape(ShapeType.RoundCornerRectangle, float.NaN, float .NaN, float.NaN, float.NaN); &lt;/code&gt; Такой код может привести к непонятным ситуациям. Поэтому были добавлены ограничения на использование неопределенных значений для IShape.Frame. Значения x, y, width, height, flipH, flipV и rotateAngle должны быть определены (не float.NaN или NullableBool.NotDefined). Приведенный выше пример кода теперь вызывает исключение ArgumentException. Это относится к следующим вариантам использования: &lt;code&gt; IShape shape = ...; shape.Frame = ...; // не может быть неопределенным IShapeCollection shape = ...; // параметры x, y, width, height не могут быть float.NaN: { shape.AddAudioFrameCD(...); shape.AddAudioFrameEmbedded(...); shape.AddAudioFrameLinked(...); shape.AddAutoShape(...); shape.AddChart(...); shape.AddConnector(...); shape.AddOleObjectFrame(...); shape.AddPictureFrame(...); shape.AddSmartArt(...); shape.AddTable(...); shape.AddVideoFrame(...); shape.InsertAudioFrameEmbedded(...); shape.InsertAudioFrameLinked(...); shape.InsertAutoShape(...); shape.InsertChart(...); shape.InsertConnector(...); shape.InsertOleObjectFrame(...); shape.InsertPictureFrame(...); shape.InsertTable(...); shape.InsertVideoFrame(...); } &lt;/code&gt; Но свойства фрейма IShape.RawFrame могут быть неопределенными. Это имеет смысл, когда форма связана с заполнителем. Затем неопределенные значения фрейма формы переопределяются из родительской формы-заполнителя. Если для этой фигуры нет родительской фигуры-заполнителя, эта фигура использует значения по умолчанию при оценке эффективного кадра на основе своего IShape.RawFrame. Значения по умолчанию — 0 и NullableBool.False для x, y, ширины, высоты, flipH, flipV и угла поворота. Например: &lt;code&gt; IShape shape = ...; // фигура связана с заполнителем shape.RawFrame = new ShapeFrame(float.NaN, float.NaN, 100, float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0); // теперь фигура наследует значения x, y, height, flipH, flipV от заполнителя и переопределяет ширину = 100 и угол поворота = 0. &lt;/code&gt;

```csharp
IShape shape = ...;
shape.Frame = new ShapeFrame(float.NaN, float.NaN, float.NaN, float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, float.NaN);
```

### Смотрите также

* interface [IShapeFrame](../../ishapeframe)
* class [Shape](../../shape)
* пространство имен [Aspose.Slides](../../shape)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->