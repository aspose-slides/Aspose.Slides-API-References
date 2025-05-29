---
title: AddTextFrame
second_title: Aspose.Slides для .NET API Справочник
description: Добавляет новый TextFrame к форме. Если форма уже имеет TextFrame, то просто изменяет его текст.
type: docs
weight: 60
url: /ru/aspose.slides/autoshape/addtextframe/
---

## AutoShape.AddTextFrame метод

Добавляет новый TextFrame к форме. Если форма уже имеет TextFrame, то просто изменяет его текст.

```csharp
public ITextFrame AddTextFrame(string text)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | String | Значение текста по умолчанию для нового TextFrame. |

### Примеры

Следующий пример кода показывает, как добавить текст водяного знака в презентацию PowerPoint.

```csharp
[C#]
	using (var presentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 150, 50);
		ITextFrame watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
	}
```

Следующий пример показывает, как создать текстовое поле на слайде.

```csharp
[C#]
// Инициализирует презентацию
using (Presentation pres = new Presentation())
{
    // Получает первый слайд в презентации
    ISlide sld = pres.Slides[0];
    // Добавляет AutoShape с типом, установленным как Прямоугольник
    IAutoShape ashp = sld.Shapes.AddAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
    // Добавляет TextFrame к Прямоугольнику
    ashp.AddTextFrame(" ");
    // Получает текстовый фрейм
    ITextFrame txtFrame = ashp.TextFrame;
    // Создает объект Параграфа для текстового фрейма
    IParagraph para = txtFrame.Paragraphs[0];
    // Создает объект Portion для параграфа
    IPortion portion = para.Portions[0];
    // Устанавливает текст
    portion.Text = "Aspose TextBox";
    // Сохраняет презентацию на диск
    pres.Save("TextBox_out.pptx", Aspose.Slides.Export.SaveFormat.Pptx);
}
```

Следующий пример показывает, как добавить столбец в текстовое поле.

```csharp
[C#]
using (Presentation presentation = new Presentation())
{
	// Получает первый слайд в презентации
	ISlide slide = presentation.Slides[0];
	// Добавляет AutoShape с типом, установленным как Прямоугольник
	IAutoShape aShape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
	// Добавляет TextFrame к Прямоугольнику
	aShape.AddTextFrame("Все эти столбцы ограничены одним текстовым контейнером -- " +
	"вы можете добавлять или удалять текст, и новый или оставшийся текст автоматически подстраивается " +
	"под него. Однако текст не может течь из одного контейнера в другой -- мы говорили вам, что варианты столбцов в PowerPoint для текста ограничены!");
	// Получает формат текста TextFrame
	ITextFrameFormat format = aShape.TextFrame.TextFrameFormat;
	// Устанавливает количество столбцов в TextFrame
	format.ColumnCount = 3;
	// Устанавливает расстояние между столбцами
	format.ColumnSpacing = 10;
	// Сохраняет презентацию
	presentation.Save("ColumnCount.pptx", SaveFormat.Pptx);
}
```

### Смотрите также

* интерфейс [ITextFrame](../../itextframe)
* класс [AutoShape](../../autoshape)
* пространство имен [Aspose.Slides](../../autoshape)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->