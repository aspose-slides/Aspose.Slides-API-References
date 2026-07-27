---
title: HasFeature()
second_title: Aspose.Slides para C++ Referencia de API
description: Prueba si la implementación del Modelo de Objetos del Documento (DOM) implementa una característica específica.
type: docs
weight: 14
url: /es/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) método

Prueba si la implementación del Documento [Object](../../../system/object/) Modelo (DOM) implementa una característica específica.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | El nombre del paquete de la característica a probar. Este nombre no distingue entre mayúsculas y minúsculas. |
| strVersion | const [String](../../../system/string/)\& | Este es el número de versión del nombre del paquete a probar. Si la versión no se especifica (**nullptr**), admitir cualquier versión de la característica hace que el método devuelva **true**. |

### Valor de retorno

**true** si la característica está implementada en la versión especificada; de lo contrario, **false**.

## Observaciones

La tabla siguiente muestra las combinaciones que hacen que **HasFeature** devuelva **true**.

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlImplementation](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)