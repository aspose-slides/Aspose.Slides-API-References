---
title: AllCustomXmlParts
second_title: Aspose.Slides для .NET API Reference
description: Возвращает все пользовательские данные в презентации. Только для чтения ICustomXmlPartaspose.slides/icustomxmlpart.
type: docs
weight: 20
url: /ru/aspose.slides/presentation/allcustomxmlparts/
---

## Presentation.AllCustomXmlParts property

Возвращает все пользовательские данные в презентации. Только для чтения [`ICustomXmlPart`](../../icustomxmlpart)[].

```csharp
public ICustomXmlPart[] AllCustomXmlParts { get; }
```

### Примеры

Следующие примеры показывают, как удалить все пользовательские xml части из презентации PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation("PresentationWithCustomXml.pptx"))
{
	// Перебрать все пользовательские XML части
    foreach (ICustomXmlPart item in pres.AllCustomXmlParts)
    {
        item.Remove();
    }
    pres.Save("out.pptx", SaveFormat.Pptx);
}
```

### См. также

* интерфейс [ICustomXmlPart](../../icustomxmlpart)
* класс [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->