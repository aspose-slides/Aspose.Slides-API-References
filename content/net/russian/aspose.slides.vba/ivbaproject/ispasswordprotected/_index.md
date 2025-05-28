---
title: IsPasswordProtected
second_title: Справка по API Aspose.Slides для .NET
description: Указывает, защищен ли VBAProject паролем для просмотра свойств проекта. Только для чтения логическое значение.
type: docs
weight: 10
url: /ru/aspose.slides.vba/ivbaproject/ispasswordprotected/
---

## IVbaProject.IsPasswordProtected свойство

Указывает, защищен ли VBAProject паролем для просмотра свойств проекта. Только для чтения логическое значение.

```csharp
public bool IsPasswordProtected { get; }
```

### Примеры

```csharp
[C#]
using (var presentation = new Presentation(path + "demo.pptm"))
{
    if (presentation.VbaProject.IsPasswordProtected)
        Console.WriteLine("VBAProject '" + presentation.VbaProject.Name + 
            "' защищен паролем для просмотра свойств проекта.");
}
```

### См. также

* интерфейс [IVbaProject](../../ivbaproject)
* пространство имен [Aspose.Slides.Vba](../../ivbaproject)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->