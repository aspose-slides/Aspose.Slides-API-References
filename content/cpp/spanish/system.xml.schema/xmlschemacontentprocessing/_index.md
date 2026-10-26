---
title: XmlSchemaContentProcessing
second_title: Referencia de API de Aspose.Slides para C++
description: Proporciona información sobre el modo de validación de los reemplazos de los elementos any y anyAttribute.
type: docs
weight: 976
url: /es/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enumeración


Proporciona información sobre el modo de validación de los reemplazos de los elementos **any** y **anyAttribute**.

```cpp
enum class XmlSchemaContentProcessing
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | 0 | Los elementos del documento no se validan. |
| Skip | 1 | Los elementos del documento deben consistir en XML bien formado y no se validan mediante el esquema. |
| Lax | 2 | Si se encuentra el esquema asociado, los elementos del documento se validarán. No se generarán errores de lo contrario. |
| Strict | 3 | El procesador de esquemas debe encontrar un esquema asociado al espacio de nombres indicado para validar los elementos del documento. |

## Ver también

* Espacio de nombres [System::Xml::Schema](../)
* Biblioteca [Aspose.Slides](../../)