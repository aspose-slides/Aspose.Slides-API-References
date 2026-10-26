---
title: LookupNamespace()
second_title: Referencia de API de Aspose.Slides para C++
description: Resuelve un prefijo de espacio de nombres en el alcance del elemento actual.
type: docs
weight: 612
url: /es/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace(const String\&) método


Resuelve un prefijo de espacio de nombres en el alcance del elemento actual.

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | El prefijo cuyo URI de espacio de nombres desea resolver. Para coincidir con el espacio de nombres predeterminado, pase una cadena vacía. Esta cadena no tiene que estar atomizada. |

### Valor devuelto

El URI de espacio de nombres al que se asigna el prefijo o **nullptr** si no se encuentra un prefijo coincidente.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlTextReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)