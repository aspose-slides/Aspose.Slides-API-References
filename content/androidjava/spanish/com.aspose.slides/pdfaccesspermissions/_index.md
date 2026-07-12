---
title: PdfAccessPermissions
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Contiene un conjunto de indicadores que especifican qué permisos de acceso deben otorgarse cuando el documento se abre con acceso de usuario.
type: docs
url: /es/com.aspose.slides/pdfaccesspermissions/
---
**Herencia:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Contiene un conjunto de indicadores que especifican qué permisos de acceso deben otorgarse cuando el documento se abre con acceso de usuario.
## Campos

| Campo | Descripción |
| --- | --- |
| [None](#None) | Especifica que un usuario no tiene permisos de acceso. |
| [PrintDocument](#PrintDocument) | Especifica si un usuario puede imprimir el documento (posiblemente no al nivel de calidad más alto, dependiendo de si el bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) también está activado). |
| [ModifyContent](#ModifyContent) | Especifica si un usuario puede modificar el contenido del documento mediante operaciones distintas a las controladas por los bits [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Especifica si un usuario puede copiar o extraer de otro modo texto y gráficos del documento mediante operaciones distintas a la controlada por el bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | Especifica si un usuario puede añadir o modificar anotaciones de texto, rellenar campos de formulario interactivo y, si el bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) también está activado, crear o modificar campos de formulario interactivo (incluidos los campos de firma). |
| [FillExistingFields](#FillExistingFields) | Especifica si un usuario puede rellenar campos de formulario interactivo existentes (incluidos los campos de firma), incluso si el bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) está desactivado. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Especifica si un usuario puede extraer texto y gráficos para apoyar la accesibilidad a usuarios con discapacidades o para otros fines. |
| [AssembleDocument](#AssembleDocument) | Especifica si un usuario puede ensamblar el documento (insertar, rotar o eliminar páginas y crear marcadores o miniaturas), incluso si el bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) está desactivado. |
| [HighQualityPrint](#HighQualityPrint) | Especifica si un usuario puede imprimir el documento a una representación a partir de la cual se podría generar una copia digital fiel del contenido PDF. |
### None {#None}
```
public static final int None
```


Especifica que un usuario no tiene permisos de acceso.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


Especifica si un usuario puede imprimir el documento (posiblemente no al nivel de calidad más alto, dependiendo de si el bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) también está activado).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


Especifica si un usuario puede modificar el contenido del documento mediante operaciones distintas a las controladas por los bits [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```


Especifica si un usuario puede copiar o extraer de otro modo texto y gráficos del documento mediante operaciones distintas a la controlada por el bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```


Especifica si un usuario puede añadir o modificar anotaciones de texto, rellenar campos de formulario interactivo y, si el bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) también está activado, crear o modificar campos de formulario interactivo (incluidos los campos de firma).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```


Especifica si un usuario puede rellenar campos de formulario interactivo existentes (incluidos los campos de firma), incluso si el bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) está desactivado.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```


Especifica si un usuario puede extraer texto y gráficos para apoyar la accesibilidad a usuarios con discapacidades o para otros fines.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


Especifica si un usuario puede ensamblar el documento (insertar, rotar o eliminar páginas y crear marcadores o miniaturas), incluso si el bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) está desactivado.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```


Especifica si un usuario puede imprimir el documento a una representación a partir de la cual se podría generar una copia digital fiel del contenido PDF. Cuando este bit está desactivado (y el bit [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) está activado), la impresión se limita a una representación de bajo nivel de la apariencia, posiblemente de calidad degradada.