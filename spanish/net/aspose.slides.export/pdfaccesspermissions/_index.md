---
title: PdfAccessPermissions
second_title: Referencia de la API de Aspose.Slides para .NET
description: Contiene un conjunto de indicadores que especifican qué permisos de acceso se deben otorgar cuando el documento se abre con acceso de usuario .
type: docs
weight: 3910
url: /es/net/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enumeration

Contiene un conjunto de indicadores que especifican qué permisos de acceso se deben otorgar cuando el documento se abre con acceso de usuario .

```csharp
[Flags]
public enum PdfAccessPermissions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | Especifica que un usuario no tiene permisos de acceso. |
| PrintDocument | `4` | Especifica si un usuario puede imprimir el documento (posiblemente no con el nivel de calidad más alto, dependiendo de si el bitHighQualityPrint también está configurado). |
| ModifyContent | `8` | Especifica si un usuario puede modificar el contenido del documento mediante operaciones distintas a las controladas por bitsAddOrModifyFields ,FillExistingFields ,AssembleDocument . |
| CopyTextAndGraphics | `10` | Especifica si un usuario puede copiar o extraer texto y gráficos del documento mediante operaciones distintas a las controladas por bitExtractTextAndGraphics . |
| AddOrModifyFields | `20` | Especifica si un usuario puede agregar o modificar anotaciones de texto, completar campos de formulario interactivo y, si bit ModifyContent también se establece, cree o modifique campos de formulario interactivos (incluidos los campos de firma ). |
| FillExistingFields | `100` | Especifica si un usuario puede completar los campos de formulario interactivo existentes (incluidos los campos de firma), incluso si bitAddOrModifyFields está claro. |
| ExtractTextAndGraphics | `200` | Especifica si un usuario puede extraer texto y gráficos en apoyo de la accesibilidad para usuarios con discapacidades o para otros fines. |
| AssembleDocument | `400` | Especifica si un usuario puede ensamblar el documento (insertar, rotar o eliminar páginas y crear marcadores o imágenes en miniatura), incluso si es bitModifyContent está claro. |
| HighQualityPrint | `800` | Especifica si un usuario puede imprimir el documento en una representación a partir de la cual se podría generar una copia digital fiel de el contenido del PDF. Cuando este bit está claro (y bitPrintDocument está configurado), la impresión se limita a una representación de bajo nivel de la apariencia, posiblemente de calidad degradada. |

### Ver también

* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->