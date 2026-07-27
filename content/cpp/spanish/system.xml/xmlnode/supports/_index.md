---
title: Supports()
second_title: Referencia de API de Aspose.Slides para C++
description: Comprueba si la implementación DOM implementa una característica específica.
type: docs
weight: 482
url: /es/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) método

Comprueba si la implementación DOM implementa una característica específica.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| feature | [String](../../../system/string/) | El nombre del paquete de la característica a probar. Este nombre no distingue entre mayúsculas y minúsculas. |
| version | [String](../../../system/string/) | El número de versión del nombre del paquete a probar. Si la versión no se especifica (null), admitir cualquier versión de la característica hace que el método devuelva true. |

### Valor de retorno

**true** si la característica está implementada en la versión especificada; de lo contrario, **false**.

## Observaciones

La tabla siguiente describe las combinaciones que devuelven **true**. 

| Característica | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlNode](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)