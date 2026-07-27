---
title: LookupNamespace()
second_title: Referencia de API de Aspose.Slides para C++
description: Resuelve un prefijo de espacio de nombres en el ámbito del elemento actual.
type: docs
weight: 547
url: /es/system.xml/xmlvalidatingreader/lookupnamespace/
---
## XmlValidatingReader::LookupNamespace(const String\&) método


Resuelve un prefijo de espacio de nombres en el alcance del elemento actual.

```cpp
String System::Xml::XmlValidatingReader::LookupNamespace(const String &prefix) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | El prefijo cuyo Identificador Uniforme de Recurso (URI) del espacio de nombres desea resolver. Para coincidir con el espacio de nombres predeterminado, pase una cadena vacía. |

### Valor de retorno

El URI del espacio de nombres al que corresponde el prefijo o **nullptr** si no se encuentra un prefijo coincidente.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlValidatingReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)