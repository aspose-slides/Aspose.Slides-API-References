---
title: MasterTheme
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa un tema maestro.
type: docs
weight: 11120
url: /es/aspose.slides.theme/mastertheme/
---

## Clase MasterTheme

Representa un tema maestro.

```csharp
public sealed class MasterTheme : Theme, IMasterTheme
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [ColorScheme](../../aspose.slides.theme/mastertheme/colorscheme) { get; } | Devuelve el esquema de color. Solo lectura [`IColorScheme`](../icolorscheme). |
| [ExtraColorSchemes](../../aspose.slides.theme/mastertheme/extracolorschemes) { get; } | Devuelve la colección de esquemas de color adicionales. Estos esquemas no afectan la apariencia de la presentación, pueden seleccionarse como el esquema de color principal para una diapositiva. Solo lectura [`IExtraColorSchemeCollection`](../iextracolorschemecollection). |
| override [FontScheme](../../aspose.slides.theme/mastertheme/fontscheme) { get; } | Devuelve el esquema de fuente. Solo lectura [`IFontScheme`](../ifontscheme). |
| override [FormatScheme](../../aspose.slides.theme/mastertheme/formatscheme) { get; } | Devuelve el esquema de formato de forma. Solo lectura [`IFormatScheme`](../iformatscheme). |
| [Name](../../aspose.slides.theme/mastertheme/name) { get; set; } | Devuelve el nombre de un tema. Lectura/escritura String. |
| [Presentation](../../aspose.slides.theme/theme/presentation) { get; } | Devuelve la presentación padre. Solo lectura [`IPresentation`](../../aspose.slides/ipresentation). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetEffective](../../aspose.slides.theme/theme/geteffective)() | Obtiene los datos del tema efectivo con la herencia aplicada. |

### Véase también

* clase [Theme](../theme)
* interfaz [IMasterTheme](../imastertheme)
* espacio de nombres [Aspose.Slides.Theme](../../aspose.slides.theme)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->