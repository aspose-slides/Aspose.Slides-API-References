---
title: Slides
second_title: Aspose.Slides для .NET API Reference
description: Возвращает список всех слайдов, определенных в презентации. Только для чтения ISlideCollection aspose.slides/islidecollection.
type: docs
weight: 230
url: /ru/aspose.slides/presentation/slides/
---

## Свойство Presentation.Slides

Возвращает список всех слайдов, определенных в презентации. Только для чтения [`ISlideCollection`](../../islidecollection).

```csharp
public ISlideCollection Slides { get; }
```

### Примеры

Следующий пример показывает, как установить цвет фона слайдов в презентации PowerPoint.

```csharp
[C#]
// Создание экземпляра класса Presentation, представляющего файл презентации
using (Presentation pres = new Presentation())
{
    // Установить цвет фона первого ISlide в синий
    pres.Slides[0].Background.Type = BackgroundType.OwnBackground;
    pres.Slides[0].Background.FillFormat.FillType = FillType.Solid;
    pres.Slides[0].Background.FillFormat.SolidFillColor.Color = Color.Blue;
    pres.Save("ContentBG_out.pptx", SaveFormat.Pptx);
}
```

Следующий пример показывает, как установить фоновое изображение слайдов в презентации PowerPoint.

```csharp
[C#]
// Создание экземпляра класса Presentation, представляющего файл презентации
using (Presentation pres = new Presentation("SetImageAsBackground.pptx"))
{
    // Установить фон с изображением
    pres.Slides[0].Background.Type = BackgroundType.OwnBackground;
    pres.Slides[0].Background.FillFormat.FillType = FillType.Picture;
    pres.Slides[0].Background.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;
    // Установить изображение
    System.Drawing.Image img = (System.Drawing.Image)new Bitmap(dataDir + "Tulips.jpg");
    // Добавить изображение в коллекцию изображений презентации
    IPPImage imgx = pres.Images.AddImage(img);
    pres.Slides[0].Background.FillFormat.PictureFillFormat.Picture.Image = imgx;
    // Записать презентацию на диск
    pres.Save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
}
```

Следующий пример показывает, как добавить переход слайда в презентацию.

```csharp
[C#]
// Создание экземпляра класса Presentation для загрузки исходного файла презентации
using (Presentation presentation = new Presentation("AccessSlides.pptx"))
{
    // Применить круговой переход на слайде 1
    presentation.Slides[0].SlideShowTransition.Type = TransitionType.Circle;
    // Применить переход комбо на слайде 2
    presentation.Slides[1].SlideShowTransition.Type = TransitionType.Comb;
    // Записать презентацию на диск
    presentation.Save("SampleTransition_out.pptx", SaveFormat.Pptx);
}
```

Следующий пример показывает, как добавить сложный переход слайда.

```csharp
[C#]
// Создание экземпляра класса Presentation, представляющего файл презентации
using (Presentation pres = new Presentation("BetterSlideTransitions.pptx"))
{
    // Применить круговой переход на слайде 1
    pres.Slides[0].SlideShowTransition.Type = TransitionType.Circle;
    // Установить время перехода в 3 секунды
    pres.Slides[0].SlideShowTransition.AdvanceOnClick = true;
    pres.Slides[0].SlideShowTransition.AdvanceAfterTime = 3000;
    // Применить переход комбо на слайде 2
    pres.Slides[1].SlideShowTransition.Type = TransitionType.Comb;
    // Установить время перехода в 5 секунд
    pres.Slides[1].SlideShowTransition.AdvanceOnClick = true;
    pres.Slides[1].SlideShowTransition.AdvanceAfterTime = 5000;
    // Применить зум переход на слайде 3
    pres.Slides[2].SlideShowTransition.Type = TransitionType.Zoom;
    // Установить время перехода в 7 секунд
    pres.Slides[2].SlideShowTransition.AdvanceOnClick = true;
    pres.Slides[2].SlideShowTransition.AdvanceAfterTime = 7000;
    // Записать презентацию на диск
    pres.Save("SampleTransition_out.pptx", SaveFormat.Pptx);
}
```

### Смотрите также

* интерфейс [ISlideCollection](../../islidecollection)
* класс [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)
