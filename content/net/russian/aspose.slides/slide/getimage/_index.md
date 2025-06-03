---
title: GetImage
second_title: Справка по API Aspose.Sildes для .NET
description: Возвращает объект миниатюры изображения с пользовательским масштабированием.
type: docs
weight: 80
url: /ru/aspose.slides/slide/getimage/
---

## ПолучитьИзображение(float, float) {#getimage_5}

Возвращает объект миниатюры изображения с пользовательским масштабированием.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| scaleX | Single | Значение, на которое необходимо масштабировать эту миниатюру в направлении оси x. |
| scaleY | Single | Значение, на которое необходимо масштабировать эту миниатюру в направлении оси y. |

### Возвращаемое значение

Объект IImage.

### Примеры

Следующий пример показывает, как генерировать миниатюры из презентации PowerPoint.

```csharp
[C#]
// Создание экземпляра класса Presentation, который представляет файл презентации
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // Доступ к первому слайду
    ISlide sld = pres.Slides[0];
    // Создание изображения в полном масштабе
    IImage bmp = sld.GetImage(1f, 1f);
    // Сохранение изображения на диск в формате JPEG
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

Следующий пример показывает, как конвертировать слайды в битмапы и сохранять изображения в формате PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Конвертирует первый слайд в презентации в объект Bitmap
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // Сохраняет изображение в формате PNG
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

Следующий пример показывает, как конвертировать PowerPoint PPT/PPTX в JPG.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// Создание изображения в полном масштабе
		IImage bmp = sld.GetImage(1f, 1f);
		// Сохранение изображения на диск в формате JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

Следующий пример показывает, как конвертировать PowerPoint PPT/PPTX в JPG с пользовательскими размерами.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Определение размеров
	int desiredX = 1200;
	int desiredY = 800;
	// Получение масштабируемых значений X и Y
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Создание изображения в полном масштабе
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Сохранение изображения на диск в формате JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### См. также

* интерфейс [IImage](../../iimage)
* класс [Slide](../../slide)
* пространство имен [Aspose.Slides](../../slide)
* сборка [Aspose.Slides](../../../)

---

## ПолучитьИзображение() {#getimage}

Возвращает объект миниатюры изображения (20% от реального размера).

```csharp
public IImage GetImage()
```

### См. также

* интерфейс [IImage](../../iimage)
* класс [Slide](../../slide)
* пространство имен [Aspose.Slides](../../slide)
* сборка [Aspose.Slides](../../../)

---

## ПолучитьИзображение(Size) {#getimage_6}

Возвращает объект миниатюры изображения с указанным размером.

```csharp
public IImage GetImage(Size imageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageSize | Size | Размер изображения, которое нужно создать. |

### Возвращаемое значение

Объект изображения.

### Примеры

Следующий пример показывает, как конвертировать слайды в изображения с пользовательскими размерами с использованием C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Конвертирует первый слайд в презентации в изображение Bitmap с указанным размером
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Сохраняет изображение в формате JPEG
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### См. также

* интерфейс [IImage](../../iimage)
* класс [Slide](../../slide)
* пространство имен [Aspose.Slides](../../slide)
* сборка [Aspose.Slides](../../../)

---

## ПолучитьИзображение(ITiffOptions) {#getimage_4}

Возвращает объект миниатюры tiff изображения с указанными параметрами.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | ITiffOptions | Параметры Tiff. |

### Возвращаемое значение

Объект изображения.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Выбрасывается, когда options.SlideLayoutOption равен NotesCommentsLayoutingOptions, и его свойство NotesPosition принимает значение NotesPositions.BottomFull. |

### См. также

* интерфейс [IImage](../../iimage)
* интерфейс [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* класс [Slide](../../slide)
* пространство имен [Aspose.Slides](../../slide)
* сборка [Aspose.Slides](../../../)

---

## ПолучитьИзображение(IRenderingOptions) {#getimage_1}

Возвращает объект миниатюры изображения.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | IRenderingOptions | Параметры рендеринга. |

### Возвращаемое значение

Объект изображения.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Выбрасывается, когда notesCommentsLayouting.NotesPosition принимает значение NotesPositions.BottomFull |

### См. также

* интерфейс [IImage](../../iimage)
* интерфейс [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* класс [Slide](../../slide)
* пространство имен [Aspose.Slides](../../slide)
* сборка [Aspose.Slides](../../../)

---

## ПолучитьИзображение(IRenderingOptions, float, float) {#getimage_2}

Возвращает объект миниатюры изображения с пользовательским масштабированием.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | IRenderingOptions | Параметры рендеринга. |
| scaleX | Single | Значение, на которое необходимо масштабировать эту миниатюру в направлении оси x. |
| scaleY | Single | Значение, на которое необходимо масштабировать эту миниатюру в направлении оси y. |

### Возвращаемое значение

Объекты Bitmap.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Выбрасывается, когда notesCommentsLayouting.NotesPosition принимает значение NotesPositions.BottomFull |

### Примеры

Следующий пример показывает, как конвертировать слайды с заметками и комментариями в изображения с использованием C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Создает параметры рендеринга
    IRenderingOptions options = new RenderingOptions();
    // Создает параметры компоновки заметок и комментариев
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Устанавливает позицию заметок на странице
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Устанавливает позицию комментариев на странице
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Устанавливает ширину области вывода комментариев
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Устанавливает цвет для области комментариев
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Устанавливает параметры компоновки для рендеринга
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Конвертирует первый слайд презентации в объект IImage
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Сохраняет изображение в формате GIF
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### См. также

* интерфейс [IImage](../../iimage)
* интерфейс [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* класс [Slide](../../slide)
* пространство имен [Aspose.Slides](../../slide)
* сборка [Aspose.Slides](../../../)

---

## ПолучитьИзображение(IRenderingOptions, Size) {#getimage_3}

Возвращает объект миниатюры изображения с указанным размером.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | IRenderingOptions | Параметры рендеринга. |
| imageSize | Size | Размер изображения, которое нужно создать. |

### Возвращаемое значение

Объект изображения.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Выбрасывается, когда options.SlideLayoutOption равен NotesCommentsLayoutingOptions, и его свойство NotesPosition принимает значение NotesPositions.BottomFull. |

### См. также

* интерфейс [IImage](../../iimage)
* интерфейс [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* класс [Slide](../../slide)
* пространство имен [Aspose.Slides](../../slide)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->