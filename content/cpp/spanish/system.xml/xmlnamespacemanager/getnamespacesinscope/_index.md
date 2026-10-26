---
title: GetNamespacesInScope()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una colección de nombres de espacio de nombres indexados por prefijo que pueden usarse para enumerar los espacios de nombres que están actualmente en alcance.
type: docs
weight: 105
url: /es/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope) método

Devuelve una colección de nombres de espacio de nombres indexados por prefijo que pueden usarse para enumerar los espacios de nombres que están actualmente en alcance.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Un valor de enumeración que especifica el tipo de nodos de espacio de nombres a devolver. |

### Valor de retorno

Una colección de pares de espacio de nombres y prefijo que están actualmente en alcance.

## Ver también

* Enumeración [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IDictionary](../../../system.collections.generic/idictionary/)
* Clase [String](../../../system/string/)
* Clase [XmlNamespaceManager](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)