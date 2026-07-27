---
title: GetNamespacesInScope()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve una colección de asignaciones de prefijo-espacio de nombres definidas que están actualmente en el alcance.
type: docs
weight: 1
url: /es/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope) método


Devuelve una colección de asignaciones de prefijo-espacio de nombres definidas que están actualmente en el alcance.

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Un valor XmlNamespaceScope que especifica el tipo de nodos de espacio de nombres que se devolverán. |

### Valor de retorno

Una colección IDictionary que contiene los espacios de nombres actuales en alcance.

## Ver también

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)