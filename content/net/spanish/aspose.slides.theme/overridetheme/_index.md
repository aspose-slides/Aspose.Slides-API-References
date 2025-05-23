---
title: OverrideTheme
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa un tema primordial.
type: docs
weight: 10650
url: /es/aspose.slides.theme/overridetheme/
---
## OverrideTheme class

Representa un tema primordial.

```csharp
public class OverrideTheme : Theme, IOverrideTheme
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [ColorScheme](../../aspose.slides.theme/overridetheme/colorscheme) { get; } | Devuelve el esquema de color. Solo lectura[`IColorScheme`](../icolorscheme) . |
| override [FontScheme](../../aspose.slides.theme/overridetheme/fontscheme) { get; } | Devuelve el esquema de fuente. Solo lectura[`IFontScheme`](../ifontscheme) . |
| override [FormatScheme](../../aspose.slides.theme/overridetheme/formatscheme) { get; } | Devuelve el esquema de formato de forma. Solo lectura[`IFormatScheme`](../iformatscheme) . |
| [IsEmpty](../../aspose.slides.theme/overridetheme/isempty) { get; } | El valor verdadero significa que ColorScheme, FontScheme, FormatScheme es nulo y cualquier anulación con este objeto de tema está deshabilitada. Solo lecturaBoolean . |
| [Presentation](../../aspose.slides.theme/theme/presentation) { get; } | Devuelve la presentación principal. Solo lectura[`IPresentation`](../../aspose.slides/ipresentation) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clear](../../aspose.slides.theme/overridetheme/clear)() | Establezca ColorScheme, FontScheme, FormatScheme en nulo para deshabilitar cualquier anulación con este objeto de tema. |
| [GetEffective](../../aspose.slides.theme/theme/geteffective)() | Obtiene datos de temas efectivos con la herencia aplicada. |
| [InitColorScheme](../../aspose.slides.theme/overridetheme/initcolorscheme)() | Inicializar ColorScheme con un nuevo objeto para anular ColorScheme de InheritedTheme. |
| [InitColorSchemeFrom](../../aspose.slides.theme/overridetheme/initcolorschemefrom)(IColorScheme) | Inicializar ColorScheme con un nuevo objeto para anular ColorScheme de InheritedTheme. |
| [InitColorSchemeFromInherited](../../aspose.slides.theme/overridetheme/initcolorschemefrominherited)() | Inicie ColorScheme con un nuevo objeto para anular ColorScheme de InheritedTheme. E inicialice los datos de este nuevo objeto con los datos del ColorScheme de InheritedTheme. |
| [InitFontScheme](../../aspose.slides.theme/overridetheme/initfontscheme)() | Inicializar FontScheme con un nuevo objeto para anular FontScheme de InheritedTheme. |
| [InitFontSchemeFrom](../../aspose.slides.theme/overridetheme/initfontschemefrom)(IFontScheme) | Inicializar FontScheme con un nuevo objeto para anular FontScheme de InheritedTheme. |
| [InitFontSchemeFromInherited](../../aspose.slides.theme/overridetheme/initfontschemefrominherited)() | Inicializar FontScheme con un nuevo objeto para anular FontScheme de InheritedTheme. E inicialice los datos de este nuevo objeto con los datos del FontScheme de InheritedTheme. |
| [InitFormatScheme](../../aspose.slides.theme/overridetheme/initformatscheme)() | Init FormatScheme con un nuevo objeto para anular FormatScheme de InheritedTheme. |
| [InitFormatSchemeFrom](../../aspose.slides.theme/overridetheme/initformatschemefrom)(IFormatScheme) | Init FormatScheme con un nuevo objeto para anular FormatScheme de InheritedTheme. |
| [InitFormatSchemeFromInherited](../../aspose.slides.theme/overridetheme/initformatschemefrominherited)() | Init FormatScheme con un nuevo objeto para anular FormatScheme de InheritedTheme. E inicialice los datos de este nuevo objeto con datos del FormatScheme de InheritedTheme. |

### Ver también

* class [Theme](../theme)
* interface [IOverrideTheme](../ioverridetheme)
* espacio de nombres [Aspose.Slides.Theme](../../aspose.slides.theme)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
