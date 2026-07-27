---
title: LookupNamespace()
second_title: Referencia de la API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, resuelve un prefijo de espacio de nombres en el ámbito del elemento actual.
type: docs
weight: 729
url: /es/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) método


Cuando se sobrescribe en una clase derivada, resuelve un prefijo de espacio de nombres en el ámbito del elemento actual.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | El prefijo cuyo URI de espacio de nombres desea resolver. Para coincidir con el espacio de nombres predeterminado, pase una cadena vacía. |

### Valor devuelto

El URI de espacio de nombres al que pertenece el prefijo o **nullptr** si no se encuentra un prefijo coincidente.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)