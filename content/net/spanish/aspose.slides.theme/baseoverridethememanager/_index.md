---
title: BaseOverrideThemeManager
second_title: Referencia de API de Aspose.Slides para .NET
description: Clase base para clases que proporcionan acceso a diferentes tipos de temas sobreescritos.
type: docs
weight: 10730
url: /es/aspose.slides.theme/baseoverridethememanager/
---

## Clase BaseOverrideThemeManager

Clase base para clases que proporcionan acceso a diferentes tipos de temas sobreescritos.

```csharp
public abstract class BaseOverrideThemeManager : BaseThemeManager, IOverrideThemeManager
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsOverrideThemeEnabled](../../aspose.slides.theme/baseoverridethememanager/isoverridethemeenabled) { get; } | Determina si OverrideTheme sobrescribe el tema efectivo heredado o no. Para habilitar OverrideTheme para la sobrescritura, use los métodos OverrideTheme.Init*(). Para deshabilitar OverrideTheme de la sobrescritura, use el método OverrideTheme.Clear(). Solo lectura Booleana. |
| [OverrideTheme](../../aspose.slides.theme/baseoverridethememanager/overridetheme) { get; set; } | Devuelve el objeto de tema sobrescrito. Lectura/escritura [`IOverrideTheme`](../ioverridetheme). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ApplyColorScheme](../../aspose.slides.theme/baseoverridethememanager/applycolorscheme)(IExtraColorScheme) | Aplica un esquema de color adicional a una diapositiva. |
| [CreateThemeEffective](../../aspose.slides.theme/baseoverridethememanager/createthemeeffective)() | Devuelve el objeto de tema. |

### Vea También

* clase [BaseThemeManager](../basethememanager)
* interfaz [IOverrideThemeManager](../ioverridethememanager)
* espacio de nombres [Aspose.Slides.Theme](../../aspose.slides.theme)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->