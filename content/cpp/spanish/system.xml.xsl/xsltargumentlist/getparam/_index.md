---
title: GetParam()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el parámetro asociado con el nombre calificado del espacio de nombres.
type: docs
weight: 14
url: /es/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) método

Devuelve el parámetro asociado con el nombre calificado del espacio de nombres.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | El nombre del parámetro. [XsltArgumentList](../) no verifica que el nombre pasado sea un nombre local válido; sin embargo, el nombre no puede ser **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | El URI del espacio de nombres asociado con el parámetro. |

### Valor devuelto

El objeto de parámetro o **nullptr** si no se encontró.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)