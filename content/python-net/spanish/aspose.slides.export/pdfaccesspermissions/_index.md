---
title: PdfAccessPermissions enumeration
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enumeración

Contiene un conjunto de indicadores que especifican qué permisos de acceso deben concederse cuando el documento se abre con 
            acceso de usuario.

El tipo PdfAccessPermissions expone los siguientes miembros:

## Campos

| Campo | Descripción |
| :- | :- |
| NONE | Especifica que un usuario no tiene permisos de acceso. |
| PRINT_DOCUMENT | Especifica si un usuario puede imprimir el documento (posiblemente no al nivel de máxima calidad, dependiendo de <br/>            si el bit [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/es/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) también está activado). |
| MODIFY_CONTENT | Especifica si un usuario puede modificar el contenido del documento mediante operaciones distintas a las controladas<br/>            por los bits [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/es/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/es/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/es/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT). |
| COPY_TEXT_AND_GRAPHICS | Especifica si un usuario puede copiar o extraer de otro modo texto y gráficos del documento mediante operaciones <br/>            distintas a la controlada por el bit [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/es/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS). |
| ADD_OR_MODIFY_FIELDS | Especifica si un usuario puede añadir o modificar anotaciones de texto, rellenar campos de formulario interactivo y, si el bit<br/>            [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/es/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) también está activado, crear o modificar campos de formulario interactivo (incluidos los campos de firma <br/>            ). |
| FILL_EXISTING_FIELDS | Especifica si un usuario puede rellenar campos de formulario interactivo existentes (incluidos los campos de firma), incluso si<br/>            el bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/es/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) está desactivado. |
| EXTRACT_TEXT_AND_GRAPHICS | Especifica si un usuario puede extraer texto y gráficos para apoyar la accesibilidad a usuarios con discapacidades<br/>            o para otros propósitos. |
| ASSEMBLE_DOCUMENT | Especifica si un usuario puede ensamblar el documento (insertar, rotar o eliminar páginas y crear marcadores o<br/>            imágenes en miniatura), incluso si el bit [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/es/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) está desactivado. |
| HIGH_QUALITY_PRINT | Especifica si un usuario puede imprimir el documento a una representación a partir de la cual se podría generar una copia digital fiel del<br/>            contenido PDF. Cuando este bit está desactivado (y el bit [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/es/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) está activado),<br/>            la impresión se limita a una representación de bajo nivel de la apariencia, posiblemente de calidad degradada. |

### Ver también
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)