---
title: GetImage
second_title: Aspose.Sildes для .NET API Справочник
description: Возвращает объект изображения эскиза с пользовательским масштабированием.
type: docs
weight: 80
url: /ru/aspose.slides/slide/getimage/
---

## GetImage(float, float) {#getimage_5}

Возвращает объект изображения эскиза с пользовательским масштабированием.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| scaleX | Single | Значение, на которое необходимо масштабировать этот эскиз в направлении оси X. |
| scaleY | Single | Значение, на которое необходимо масштабировать этот эскиз в направлении оси Y. |

### Возвращаемое значение

Объект IImage.

### Примеры

Следующий пример показывает, как сгенерировать эскизы из презентации PowerPoint.

```csharp
[C#]
// Создать экземпляр класса Presentation, представляющего файл презентации
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // Доступ к первому слайду
    ISlide sld = pres.Slides[0];
    // Создать изображение в полном масштабе
    IImage bmp = sld.GetImage(1f, 1f);
    // Сохранить изображение на диск в формате JPEG
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
		// Создать изображение в полном масштабе
		IImage bmp = sld.GetImage(1f, 1f);
		// Сохранить изображение на диск в формате JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

Следующий пример показывает, как конвертировать PowerPoint PPT/PPTX в JPG с настройками для пользовательских размеров.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Определить размеры
	int desiredX = 1200;
	int desiredY = 800;
	// Получить масштабируемые значения X и Y
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Создать изображение в полном масштабе
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Сохранить изображение на диск в формате JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### См. Также

* interface [IImage](../../iimage)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

Возвращает объект изображения эскиза (20% от реального размера).

```csharp
public IImage GetImage()
```

### См. Также

* interface [IImage](../../iimage)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

Возвращает объект изображения эскиза с указанным размером.

```csharp
public IImage GetImage(Size imageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageSize | Size | Размер изображения, которое необходимо создать. |

### Возвращаемое значение

Объект Image.

### Примеры

Следующий пример показывает, как конвертировать слайды в изображения с пользовательскими размерами, используя C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Конвертирует первый слайд в презентации в Bitmap с заданным размером
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Сохраняет изображение в формате JPEG
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### См. Также

* interface [IImage](../../iimage)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

Возвращает объект изображения TIFF эскиза с заданными параметрами.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | ITiffOptions | Опции для TIFF. |

### Возвращаемое значение

Объект Image.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Выбрасывается, когда options.SlideLayoutOption равно NotesCommentsLayoutingOptions, и его свойство NotesPosition принимает значение NotesPositions.BottomFull. |

### См. Также

* interface [IImage](../../iimage)
* interface [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Возвращает объект изображения эскиза.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | IRenderingOptions | Опции для отрисовки. |

### Возвращаемое значение

Объект Image.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Выбрасывается, когда notesCommentsLayouting.NotesPosition принимает значение NotesPositions.BottomFull |

### См. Также

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

Возвращает объект изображения эскиза с пользовательским масштабированием.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | IRenderingOptions | Опции для отрисовки. |
| scaleX | Single | Значение, на которое необходимо масштабировать этот эскиз в направлении оси X. |
| scaleY | Single | Значение, на которое необходимо масштабировать этот эскиз в направлении оси Y. |

### Возвращаемое значение

Объекты Bitmap.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Выбрасывается, когда notesCommentsLayouting.NotesPosition принимает значение NotesPositions.BottomFull |

### Примеры

Следующий пример показывает, как конвертировать слайды с комментариями и заметками в изображения с использованием C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Создать опции для отрисовки
    IRenderingOptions options = new RenderingOptions();
    // Создать опции для компоновки заметок и комментариев
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Установить положение заметок на странице
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Установить положение комментариев на странице
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Установить ширину области вывода комментариев
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Установить цвет области комментариев
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Установить параметры компоновки для отрисовки
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Конвертировать первый слайд презентации в объект IImage
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Сохранить изображение в формате GIF
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### См. Также

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

Возвращает объект изображения эскиза с указанным размером.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | IRenderingOptions | Опции для отрисовки. |
| imageSize | Size | Размер изображения, которое необходимо создать. |

### Возвращаемое значение

Объект Image.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Выбрасывается, когда options.SlideLayoutOption равно NotesCommentsLayoutingOptions, и его свойство NotesPosition принимает значение NotesPositions.BottomFull. |

### См. Также

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->