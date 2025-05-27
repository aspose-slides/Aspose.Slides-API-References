---
title: PdfAccessPermissions
second_title: Aspose.Sildes para .NET Referencia de API
description: Contiene un conjunto de flags que especifican qué permisos de acceso deben ser otorgados cuando el documento se abre con acceso de usuario.
type: docs
weight: 4120
url: /es/aspose.slides.export/pdfaccesspermissions/
---

## Enumeración PdfAccessPermissions

Contiene un conjunto de flags que especifican qué permisos de acceso deben ser otorgados cuando el documento se abre con acceso de usuario.

```csharp
[Flags]
public enum PdfAccessPermissions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | Especifica que un usuario no tiene permisos de acceso. |
| PrintDocument | `4` | Especifica si un usuario puede imprimir el documento (posiblemente no en el nivel de calidad más alto, dependiendo de si el bit HighQualityPrint también está establecido). |
| ModifyContent | `8` | Especifica si un usuario puede modificar el contenido del documento mediante operaciones distintas de aquellas controladas por los bits AddOrModifyFields, FillExistingFields, AssembleDocument. |
| CopyTextAndGraphics | `10` | Especifica si un usuario puede copiar o extraer texto y gráficos del documento mediante operaciones distintas de las controladas por el bit ExtractTextAndGraphics. |
| AddOrModifyFields | `20` | Especifica si un usuario puede agregar o modificar anotaciones de texto, completar campos de formularios interactivos y, si el bit ModifyContent también está establecido, crear o modificar campos de formularios interactivos (incluyendo campos de firma). |
| FillExistingFields | `100` | Especifica si un usuario puede completar campos de formularios interactivos existentes (incluyendo campos de firma), incluso si el bit AddOrModifyFields está claro. |
| ExtractTextAndGraphics | `200` | Especifica si un usuario puede extraer texto y gráficos en apoyo de la accesibilidad para usuarios con discapacidades u otros propósitos. |
| AssembleDocument | `400` | Especifica si un usuario puede ensamblar el documento (insertar, rotar o eliminar páginas y crear marcadores o imágenes en miniatura), incluso si el bit ModifyContent está claro. |
| HighQualityPrint | `800` | Especifica si un usuario puede imprimir el documento a una representación de la cual se podría generar una copia digital fiel del contenido PDF. Cuando este bit está claro (y el bit PrintDocument está establecido), la impresión está limitada a una representación de bajo nivel de la apariencia, posiblemente de calidad degradada. |

### Véase También

* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->