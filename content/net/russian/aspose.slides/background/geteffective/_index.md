---
title: GetEffective
second_title: Aspose.Sildes для справки по API .NET
description: Получает эффективные данные фона с примененным наследованием.
type: docs
weight: 80
url: /ru/aspose.slides/background/geteffective/
---

## Background.GetEffective метод

Получает эффективные данные фона с примененным наследованием.

```csharp
public IBackgroundEffectiveData GetEffective()
```

### Возвращаемое значение

[`IBackgroundEffectiveData`](../../ibackgroundeffectivedata).

### Примеры

Этот пример демонстрирует получение эффективных свойств фона.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
	IBackgroundEffectiveData effectiveBackground = pres.Slides[0].Background.GetEffective();

	Console.WriteLine("Тип заливки фона: " + effectiveBackground.FillFormat.FillType);
	Console.WriteLine("Применены ли какие-либо эффекты: " + !effectiveBackground.EffectFormat.IsNoEffects);
}
```

### Смотрите также

* interface [IBackgroundEffectiveData](../../ibackgroundeffectivedata)
* class [Background](../../background)
* namespace [Aspose.Slides](../../background)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
