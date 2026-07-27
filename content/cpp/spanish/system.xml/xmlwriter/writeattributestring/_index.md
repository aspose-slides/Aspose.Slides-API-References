---
title: WriteAttributeString()
second_title: Referencia de la API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, escribe un atributo con el nombre local, el URI del espacio de nombres y el valor especificados.
type: docs
weight: 131
url: /es/system.xml/xmlwriter/writeattributestring/
---
## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&) método

Cuando se sobrescribe en una clase derivada, escribe un atributo con el nombre local, el URI del espacio de nombres y el valor especificados.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &ns, const String &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | El nombre local del atributo. |
| ns | const [String](../../../system/string/)\& | El URI del espacio de nombres que se asocia con el atributo. |
| value | const [String](../../../system/string/)\& | El valor del atributo. |

## XmlWriter::WriteAttributeString(const String\&, const String\&) método

Cuando se sobrescribe en una clase derivada, escribe el atributo con el nombre local y el valor especificados.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | El nombre local del atributo. |
| value | const [String](../../../system/string/)\& | El valor del atributo. |

## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&, const String\&) método

Cuando se sobrescribe en una clase derivada, escribe el atributo con el prefijo, el nombre local, el URI del espacio de nombres y el valor especificados.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &prefix, const String &localName, const String &ns, const String &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | El prefijo del espacio de nombres del atributo. |
| localName | const [String](../../../system/string/)\& | El nombre local del atributo. |
| ns | const [String](../../../system/string/)\& | El URI del espacio de nombres del atributo. |
| value | const [String](../../../system/string/)\& | El valor del atributo. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlWriter](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)