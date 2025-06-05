---
title: GetEffective
second_title: Aspose.Slides para .NET Referencia de API
description: Obtiene datos de tema efectivos con la herencia aplicada.
type: docs
weight: 50
url: /es/aspose.slides.theme/theme/geteffective/
---

## Método Theme.GetEffective

Obtiene datos de tema efectivos con la herencia aplicada.

```csharp
public IThemeEffectiveData GetEffective()
```

### Valor de Retorno

Un [`IThemeEffectiveData`](../../ithemeeffectivedata).

### Ejemplos

Este ejemplo demuestra cómo obtener propiedades efectivas del tema.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
	IThemeEffectiveData effectiveTheme  = pres.Slides[0].ThemeManager.OverrideTheme.GetEffective();

	Console.WriteLine("Nombre del esquema de fuente: " + effectiveTheme.FontScheme.Name);
	Console.WriteLine("Fuente latina principal: " + effectiveTheme.FontScheme.Major.LatinFont.FontName);
	Console.WriteLine("Fuente latina secundaria: " + effectiveTheme.FontScheme.Minor.LatinFont.FontName);
}
```

### Ver También

* interfaz [IThemeEffectiveData](../../ithemeeffectivedata)
* clase [Theme](../../theme)
* espacio de nombres [Aspose.Slides.Theme](../../theme)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->