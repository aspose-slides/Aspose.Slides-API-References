---
title: SlideSize
second_title: Aspose.Slides для .NET API Ссылка
description: Возвращает объект размера слайда. Только для чтения ISlideSizeaspose.slides/islidesize.
type: docs
weight: 250
url: /ru/aspose.slides/presentation/slidesize/
---

## Presentation.SlideSize свойство

Возвращает объект размера слайда. Только для чтения [`ISlideSize`](../../islidesize).

```csharp
public ISlideSize SlideSize { get; }
```

### Примеры

Следующий пример показывает, как изменить размер слайда в презентации PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx"))
{
    pres.SlideSize.SetSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
    pres.Save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
}
```

Следующий пример показывает, как установить размер слайда с учетом масштабирования содержимого для презентации PowerPoint.

```csharp
[C#]
// Создайте объект Presentation, представляющий файл презентации
using(Presentation presentation = new Presentation("AccessSlides.pptx")) {
  using(Presentation auxPresentation = new Presentation()) {
    ISlide slide = presentation.Slides[0];
    // Установите размер слайда сгенерированных презентаций такой же, как у источника
    presentation.SlideSize.SetSize(540, 720, SlideSizeScaleType.EnsureFit); // Метод SetSize используется для установки размера слайда с масштабированием содержимого для обеспечения соответствия
    presentation.SlideSize.SetSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Метод SetSize используется для установки размера слайда с максимизацией размера содержимого
    // Сохраните презентацию на диск
    auxPresentation.Save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
  }
}
```

Следующий пример показывает, как задать пользовательские размеры слайдов в презентации PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    pres.SlideSize.SetSize(780, 540, SlideSizeScaleType.DoNotScale); // Размер бумаги A4
    pres.Save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
}
```

### См. Также

* интерфейс [ISlideSize](../../islidesize)
* класс [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->