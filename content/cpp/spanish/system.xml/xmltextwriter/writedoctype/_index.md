---
title: WriteDocType()
second_title: Referencia de la API de Aspose.Slides para C++
description: Escribe la declaración DOCTYPE con el nombre especificado y atributos opcionales.
type: docs
weight: 222
url: /es/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) método

Escribe la declaración DOCTYPE con el nombre especificado y atributos opcionales.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | El nombre del DOCTYPE. Debe no estar vacío. |
| pubid | const [String](../../../system/string/)\& | Si no es nulo, también escribe PUBLIC \"pubid\" \"sysid\" donde **pubid** y **sysid** se sustituyen por el valor de los argumentos proporcionados. |
| sysid | const [String](../../../system/string/)\& | Si **pubid** es nulo y **sysid** no es nulo, escribe SYSTEM \"sysid\" donde **sysid** se sustituye por el valor de este argumento. |
| subset | const [String](../../../system/string/)\& | Si no es nulo, escribe [subset] donde subset se sustituye por el valor de este argumento. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlTextWriter](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)