---
title: AnimateTransitions
second_title: Справочник по API Aspose.Slides для .NET
description: Возвращает или устанавливает параметр анимации переходов. Чтение/записьBoolean.
type: docs
weight: 30
url: /ru/aspose.slides.export/html5options/animatetransitions/
---
## Html5Options.AnimateTransitions property

Возвращает или устанавливает параметр анимации переходов. Чтение/записьBoolean.

```csharp
public bool AnimateTransitions { get; set; }
```

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
  pres.Save("demo-animate-transitions.html", SaveFormat.Html5, new Html5Options()
  {
      AnimateTransitions = true
  });
}
```

### Смотрите также

* class [Html5Options](../../html5options)
* пространство имен [Aspose.Slides.Export](../../html5options)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
