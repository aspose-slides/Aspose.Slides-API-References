---
title: ColumnCount
second_title: Справочник по API Aspose.Sildes для .NET
description: Возвращает или устанавливает количество столбцов в текстовой области. Это значение должно быть положительным числом. В противном случае значение будет установлено в ноль. Значение 0 означает неопределенное значение. Чтение/запись Int32.
type: docs
weight: 50
url: /ru/aspose.slides/textframeformat/columncount/
---

## Свойство TextFrameFormat.ColumnCount

Возвращает или устанавливает количество столбцов в текстовой области. Это значение должно быть положительным числом. В противном случае значение будет установлено в ноль. Значение 0 означает неопределенное значение. Чтение/запись Int32.

```csharp
public int ColumnCount { get; set; }
```

### Примеры

Следующий пример кода показывает, как добавить столбец в текстовый фрейм внутри презентации PowerPoint.

```csharp
[C#]
string outPptxFileName = "ColumnsTest.pptx";
using (Presentation pres = new Presentation())
{
    IAutoShape shape1 = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
    TextFrameFormat format = (TextFrameFormat)shape1.TextFrame.TextFrameFormat;
    format.ColumnCount = 2;
    shape1.TextFrame.Text = "Все эти столбцы вынуждены оставаться в рамках одного текстового контейнера -- " +
                                "вы можете добавлять или удалять текст - и новый или оставшийся текст автоматически " +
                                "подстраивается, чтобы оставаться в пределах контейнера. Однако текст не может " +
                                "переливаться из одного контейнера в другой, поскольку параметры колонок для текста в PowerPoint ограничены!";
    pres.Save(outPptxFileName, SaveFormat.Pptx);
    using (Presentation test = new Presentation(outPptxFileName))
    {
        Debug.Assert(2 == ((AutoShape)test.Slides[0].Shapes[0]).TextFrame.TextFrameFormat.ColumnCount);
        Debug.Assert(double.NaN == ((AutoShape)test.Slides[0].Shapes[0]).TextFrame.TextFrameFormat.ColumnSpacing);
    }
    format.ColumnSpacing = 20;
    pres.Save(outPptxFileName, SaveFormat.Pptx);
    using (Presentation test = new Presentation(outPptxFileName))
    {
        Debug.Assert(2 == ((AutoShape)test.Slides[0].Shapes[0]).TextFrame.TextFrameFormat.ColumnCount);
        Debug.Assert(20 == ((AutoShape)test.Slides[0].Shapes[0]).TextFrame.TextFrameFormat.ColumnSpacing);
    }
    format.ColumnCount = 3;
    format.ColumnSpacing = 15;
    pres.Save(outPptxFileName, SaveFormat.Pptx);
    using (Presentation test = new Presentation(outPptxFileName))
    {
        Debug.Assert(3 == ((AutoShape)test.Slides[0].Shapes[0]).TextFrame.TextFrameFormat.ColumnCount);
        Debug.Assert(15 == ((AutoShape)test.Slides[0].Shapes[0]).TextFrame.TextFrameFormat.ColumnSpacing);
    }
}
```

### Также см.
* класс [TextFrameFormat](../../textframeformat)
* пространство имен [Aspose.Slides](../../textframeformat)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->