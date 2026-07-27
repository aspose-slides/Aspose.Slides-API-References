---
title: GetNamespacesInScope()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una colección que contiene todos los espacios de nombres actualmente en alcance.
type: docs
weight: 716
url: /es/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) método

Devuelve una colección que contiene todos los espacios de nombres actualmente en alcance.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Un valor XmlNamespaceScope que especifica el tipo de nodos de espacio de nombres que se devolverán. |

### Valor devuelto

Un objeto IDictionary que contiene todos los espacios de nombres actuales en alcance. Si el lector no está posicionado en un elemento, se devuelve un diccionario vacío (sin espacios de nombres).

## Ver también

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IDictionary](../../../system.collections.generic/idictionary/)
* Clase [String](../../../system/string/)
* Clase [XmlTextReader](../)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)