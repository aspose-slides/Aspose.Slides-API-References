---
title: GetEffective
second_title: Справочник по API Aspose.Slides для .NET
description: Получает действующие данные темы с применением наследования.
type: docs
weight: 50
url: /ru/net/aspose.slides.theme/theme/geteffective/
---
## Theme.GetEffective method

Получает действующие данные темы с применением наследования.

```csharp
public IThemeEffectiveData GetEffective()
```

### Возвращаемое значение

А[`IThemeEffectiveData`](../../ithemeeffectivedata).

### Примеры

Этот пример демонстрирует получение эффективных свойств темы.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
	IThemeEffectiveData effectiveTheme  = pres.Slides[0].ThemeManager.OverrideTheme.GetEffective();

	Console.WriteLine("Font scheme name: " + effectiveTheme.FontScheme.Name);
	Console.WriteLine("Major latin font: " + effectiveTheme.FontScheme.Major.LatinFont.FontName);
	Console.WriteLine("Minor latin font: " + effectiveTheme.FontScheme.Minor.LatinFont.FontName);
}
```

### Смотрите также

* interface [IThemeEffectiveData](../../ithemeeffectivedata)
* class [Theme](../../theme)
* пространство имен [Aspose.Slides.Theme](../../theme)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
