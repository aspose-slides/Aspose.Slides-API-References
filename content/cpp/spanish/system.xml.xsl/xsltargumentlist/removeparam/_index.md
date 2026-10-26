---
title: RemoveParam()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elimina el parámetro de XsltArgumentList.
type: docs
weight: 66
url: /es/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) método

Elimina el parámetro de [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | El nombre del parámetro a eliminar. [XsltArgumentList](../) no verifica que el nombre proporcionado sea un nombre local válido; sin embargo, el nombre no puede ser **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | El URI del namespace del parámetro a eliminar. |

### Valor de retorno

El objeto del parámetro o **nullptr** si no se encontró.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [String](../../../system/string/)
* Clase [XsltArgumentList](../)
* Espacio de nombres [System::Xml::Xsl](../../)
* Biblioteca [Aspose.Slides](../../../)