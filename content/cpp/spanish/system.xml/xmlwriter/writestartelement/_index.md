---
title: WriteStartElement()
second_title: Referencia de la API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, escribe la etiqueta de inicio especificada y la asocia con el espacio de nombres proporcionado.
type: docs
weight: 92
url: /es/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) método

Cuando se sobrescribe en una clase derivada, escribe la etiqueta de inicio especificada y la asocia con el espacio de nombres proporcionado.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | El nombre local del elemento. |
| ns | const [String](../../../system/string/)\& | El URI del espacio de nombres que se asociará con el elemento. Si este espacio de nombres ya está en alcance y tiene un prefijo asociado, el escritor escribe automáticamente también ese prefijo. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) método

Cuando se sobrescribe en una clase derivada, escribe la etiqueta de inicio especificada y la asocia con el espacio de nombres y el prefijo proporcionados.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | El prefijo del espacio de nombres del elemento. |
| localName | const [String](../../../system/string/)\& | El nombre local del elemento. |
| ns | const [String](../../../system/string/)\& | El URI del espacio de nombres que se asociará con el elemento. |

## XmlWriter::WriteStartElement(const String\&) método

Cuando se sobrescribe en una clase derivada, escribe una etiqueta de inicio con el nombre local especificado.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | El nombre local del elemento. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlWriter](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)