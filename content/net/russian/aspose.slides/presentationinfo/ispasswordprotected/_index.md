---
title: IsPasswordProtected
second_title: Справочник по API Aspose.Slides для .NET
description: Получает значение, указывающее, защищена ли связанная презентация паролем для открытия.
type: docs
weight: 20
url: /ru/aspose.slides/presentationinfo/ispasswordprotected/
---

## PresentationInfo.IsPasswordProtected свойство

Получает значение, указывающее, защищена ли связанная презентация паролем для открытия.

```csharp
public bool IsPasswordProtected { get; }
```

### Примеры

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo(presentationFilePath);
if (info.IsPasswordProtected)
{
    Console.WriteLine("Презентация '" + presentationFilePath + "' защищена паролем для открытия.");
}
```

### Также смотри

* класс [PresentationInfo](../../presentationinfo)
* пространство имен [Aspose.Slides](../../presentationinfo)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->