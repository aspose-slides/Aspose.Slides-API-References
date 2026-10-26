---
title: PdfAccessPermissions
second_title: Referencia de la API de Aspose.Slides para C++
description: Contiene un conjunto de banderas que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario.
type: docs
weight: 989
url: /es/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enumeración


Contiene un conjunto de banderas que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario.

```cpp
enum class PdfAccessPermissions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | 0 | Especifica que un usuario no tiene permisos de acceso. |
| PrintDocument | 4 | Especifica si un usuario puede imprimir el documento (posiblemente no en el nivel de mayor calidad, dependiendo de si el bit [PdfAccessPermissions::HighQualityPrint](./) también está activado). |
| ModifyContent | 8 | Especifica si un usuario puede modificar el contenido del documento mediante operaciones distintas a las controladas por los bits [PdfAccessPermissions::AddOrModifyFields](./), [PdfAccessPermissions::FillExistingFields](./), [PdfAccessPermissions::AssembleDocument](./). |
| CopyTextAndGraphics | 16 | Especifica si un usuario puede copiar o extraer texto y gráficos del documento mediante operaciones distintas a la controlada por el bit [PdfAccessPermissions::ExtractTextAndGraphics](./). |
| AddOrModifyFields | 32 | Especifica si un usuario puede añadir o modificar anotaciones de texto, rellenar campos de formulario interactivos y, si el bit [PdfAccessPermissions::ModifyContent](./) también está activado, crear o modificar campos de formulario interactivos (incluidos los campos de firma). |
| FillExistingFields | 256 | Especifica si un usuario puede rellenar campos de formulario interactivos existentes (incluidos los campos de firma), incluso si el bit [PdfAccessPermissions::AddOrModifyFields](./) está desactivado. |
| ExtractTextAndGraphics | 512 | Especifica si un usuario puede extraer texto y gráficos para facilitar la accesibilidad a usuarios con discapacidades o para otros propósitos. |
| AssembleDocument | 1024 | Especifica si un usuario puede ensamblar el documento (insertar, rotar o eliminar páginas y crear marcadores o imágenes en miniatura), incluso si el bit [PdfAccessPermissions::ModifyContent](./) está desactivado. |
| HighQualityPrint | 2048 | Especifica si un usuario puede imprimir el documento a una representación de la que se pueda generar una copia digital fiel del contenido PDF. Cuando este bit está desactivado (y el bit [PdfAccessPermissions::PrintDocument](./) está activado), la impresión se limita a una representación de bajo nivel de la apariencia, posiblemente de calidad degradada. |

## Ver también

* Espacio de nombres [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)