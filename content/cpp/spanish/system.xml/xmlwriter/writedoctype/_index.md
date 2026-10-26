---
title: WriteDocType()
second_title: Referencia de API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, escribe la declaración DOCTYPE con el nombre especificado y atributos opcionales.
type: docs
weight: 79
url: /es/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) método


When overridden in a derived class, writes the DOCTYPE declaration with the specified name and optional attributes.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | El nombre del DOCTYPE. No debe estar vacío. |
| pubid | const [String](../../../system/string/)\& | Si no es nulo, también escribe PUBLIC \"pubid\" \"sysid\" donde **pubid** y **sysid** son reemplazados por el valor de los argumentos proporcionados. |
| sysid | const [String](../../../system/string/)\& | Si **pubid** es **nullptr** y **sysid** no es nulo, escribe SYSTEM \"sysid\" donde **sysid** es reemplazado por el valor de este argumento. |
| subset | const [String](../../../system/string/)\& | Si no es nulo, escribe [subset] donde subset es reemplazado por el valor de este argumento. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlWriter](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)