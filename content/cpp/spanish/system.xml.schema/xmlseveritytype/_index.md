---
title: XmlSeverityType
second_title: Referencia de API de Aspose.Slides para C++
description: Representa la gravedad del evento de validación.
type: docs
weight: 1080
url: /es/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType enumeración

Representa la gravedad del evento de validación.

```cpp
enum class XmlSeverityType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Error | 0 | Indica que se produjo un error de validación al validar el documento de instancia. Esto se aplica a las definiciones de tipo de documento (DTDs) y a los esquemas de lenguaje de definición XML [Schema](../) (XSD). Las restricciones de validez del Consorcio World Wide [Web](../../system.web/) (W3C) se consideran errores. Si no se ha creado un manejador de eventos de validación, los errores lanzan una excepción. |
| Warning | 1 | Indica que se produjo un evento de validación que no es un error. Normalmente se emite una advertencia cuando no hay DTD, o XML [Schema](../) para validar un elemento o atributo específico. A diferencia de los errores, las advertencias no lanzan una excepción si no hay un manejador de eventos de validación. |

## Ver también

* Espacio de nombres [System::Xml::Schema](../)
* Biblioteca [Aspose.Slides](../../)