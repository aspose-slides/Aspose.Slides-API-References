---
title: CreateXmlDeclaration()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nodo XmlDeclaration con los valores especificados.
type: docs
weight: 378
url: /es/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String\&, const String\&, const String\&) método

Crea un nodo [XmlDeclaration](../../xmldeclaration/) con los valores especificados.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | La versión debe ser "1.0". |
| encoding | const [String](../../../system/string/)\& | El valor del atributo de codificación. Esta es la codificación que se usa cuando guardas el [XmlDocument](../) en un archivo o un flujo; por lo tanto, debe establecerse a una cadena admitida por la clase [Text::Encoding](../../../system.text/encoding/), de lo contrario "XmlDocument::Save(String)" falla. Si esto es **nullptr** o [String::Empty](../../../system/string/empty/), el [XmlDocument::Save](../save/) método no escribe un atributo de codificación en la declaración XML y, por lo tanto, se usa la codificación predeterminada, UTF-8. |
| standalone | const [String](../../../system/string/)\& | El valor debe ser "yes" o "no". Si esto es **nullptr** o [String::Empty](../../../system/string/empty/), el [XmlDocument::Save](../save/) método no escribe un atributo standalone en la declaración XML. |

### Valor de retorno

El nuevo nodo [XmlDeclaration](../../xmldeclaration/).

## Observaciones

Nota: Si el [XmlDocument](../) se guarda en un TextWriter o en un [XmlTextWriter](../../xmltextwriter/), este valor de codificación se descarta. En su lugar, se usa la codificación del TextWriter o del [XmlTextWriter](../../xmltextwriter/). Esto garantiza que el XML generado pueda leerse nuevamente con la codificación correcta.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDeclaration](../../xmldeclaration/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)