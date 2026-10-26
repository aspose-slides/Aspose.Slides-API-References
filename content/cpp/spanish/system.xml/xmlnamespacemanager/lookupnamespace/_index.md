---
title: LookupNamespace()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el URI del espacio de nombres para el prefijo especificado.
type: docs
weight: 118
url: /es/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) método

Devuelve el URI del espacio de nombres para el prefijo especificado.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | El prefijo cuyo URI del espacio de nombres desea resolver. Para coincidir con el espacio de nombres predeterminado, pase [String::Empty](../../../system/string/empty/). |

### Valor de retorno

El URI del espacio de nombres para **prefix** o **nullptr** si no hay un espacio de nombres asignado. La cadena devuelta está atomizada. Para obtener más información sobre cadenas atomizadas, vea la clase [XmlNameTable](../../xmlnametable/).

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlNamespaceManager](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)