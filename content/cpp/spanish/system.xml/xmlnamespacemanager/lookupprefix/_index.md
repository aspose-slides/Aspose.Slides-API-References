---
title: LookupPrefix()
second_title: Referencia de la API de Aspose.Slides para C++
description: Busca el prefijo declarado para el URI del espacio de nombres dado.
type: docs
weight: 131
url: /es/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix(const String\&) método

Busca el prefijo declarado para el URI de espacio de nombres dado.

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | El espacio de nombres para resolver el prefijo. |

### Valor devuelto

El prefijo coincidente. Si no hay ningún prefijo asignado, el método devuelve [String::Empty](../../../system/string/empty/). Si se proporciona un valor nulo, se devuelve **nullptr**.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlNamespaceManager](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)