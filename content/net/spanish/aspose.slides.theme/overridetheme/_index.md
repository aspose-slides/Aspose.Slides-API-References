---
title: OverrideTheme
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa un tema de anulación.
type: docs
weight: 11150
url: /es/aspose.slides.theme/overridetheme/
---

## Clase OverrideTheme

Representa un tema de anulación.

```csharp
public sealed class OverrideTheme : Theme, IOverrideTheme
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [ColorScheme](../../aspose.slides.theme/overridetheme/colorscheme) { get; } | Devuelve el esquema de color. Solo lectura [`IColorScheme`](../icolorscheme). |
| override [FontScheme](../../aspose.slides.theme/overridetheme/fontscheme) { get; } | Devuelve el esquema de fuente. Solo lectura [`IFontScheme`](../ifontscheme). |
| override [FormatScheme](../../aspose.slides.theme/overridetheme/formatscheme) { get; } | Devuelve el esquema de formato de la forma. Solo lectura [`IFormatScheme`](../iformatscheme). |
| [IsEmpty](../../aspose.slides.theme/overridetheme/isempty) { get; } | Un valor verdadero significa que ColorScheme, FontScheme, FormatScheme es nulo y cualquier anulación con este objeto de tema está deshabilitada. Booleano de solo lectura. |
| [Presentation](../../aspose.slides.theme/theme/presentation) { get; } | Devuelve la presentación principal. Solo lectura [`IPresentation`](../../aspose.slides/ipresentation). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clear](../../aspose.slides.theme/overridetheme/clear)() | Establece ColorScheme, FontScheme, FormatScheme como nulos para deshabilitar cualquier anulación con este objeto de tema. |
| [GetEffective](../../aspose.slides.theme/theme/geteffective)() | Obtiene los datos del tema efectivo con la herencia aplicada. |
| [InitColorScheme](../../aspose.slides.theme/overridetheme/initcolorscheme)() | Inicializa ColorScheme con un nuevo objeto para anular el ColorScheme de InheritedTheme. |
| [InitColorSchemeFrom](../../aspose.slides.theme/overridetheme/initcolorschemefrom)(IColorScheme) | Inicializa ColorScheme con un nuevo objeto para anular el ColorScheme de InheritedTheme. |
| [InitColorSchemeFromInherited](../../aspose.slides.theme/overridetheme/initcolorschemefrominherited)() | Inicializa ColorScheme con un nuevo objeto para anular el ColorScheme de InheritedTheme. Y inicializa los datos de este nuevo objeto con los datos del ColorScheme de InheritedTheme. |
| [InitFontScheme](../../aspose.slides.theme/overridetheme/initfontscheme)() | Inicializa FontScheme con un nuevo objeto para anular el FontScheme de InheritedTheme. |
| [InitFontSchemeFrom](../../aspose.slides.theme/overridetheme/initfontschemefrom)(IFontScheme) | Inicializa FontScheme con un nuevo objeto para anular el FontScheme de InheritedTheme. |
| [InitFontSchemeFromInherited](../../aspose.slides.theme/overridetheme/initfontschemefrominherited)() | Inicializa FontScheme con un nuevo objeto para anular el FontScheme de InheritedTheme. Y inicializa los datos de este nuevo objeto con los datos del FontScheme de InheritedTheme. |
| [InitFormatScheme](../../aspose.slides.theme/overridetheme/initformatscheme)() | Inicializa FormatScheme con un nuevo objeto para anular el FormatScheme de InheritedTheme. |
| [InitFormatSchemeFrom](../../aspose.slides.theme/overridetheme/initformatschemefrom)(IFormatScheme) | Inicializa FormatScheme con un nuevo objeto para anular el FormatScheme de InheritedTheme. |
| [InitFormatSchemeFromInherited](../../aspose.slides.theme/overridetheme/initformatschemefrominherited)() | Inicializa FormatScheme con un nuevo objeto para anular el FormatScheme de InheritedTheme. Y inicializa los datos de este nuevo objeto con los datos del FormatScheme de InheritedTheme. |

### Véase también

* clase [Theme](../theme)
* interfaz [IOverrideTheme](../ioverridetheme)
* espacio de nombres [Aspose.Slides.Theme](../../aspose.slides.theme)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->