---
title: WriteStartAttribute()
second_title: Referencia de la API de Aspose.Slides para C++
description: Escribe el inicio de un atributo con el nombre local y el URI del espacio de nombres especificados.
type: docs
weight: 144
url: /es/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String&, const String&) método

Escribe el inicio de un atributo con el nombre local y el URI del espacio de nombres especificados.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | El nombre local del atributo. |
| ns | const [String](../../../system/string/)\& | El URI del espacio de nombres del atributo. |

## XmlWriter::WriteStartAttribute(const String&, const String&, const String&) método

Cuando se sobrescribe en una clase derivada, escribe el inicio de un atributo con el prefijo, el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | El prefijo del espacio de nombres del atributo. |
| localName | const [String](../../../system/string/)\& | El nombre local del atributo. |
| ns | const [String](../../../system/string/)\& | El URI del espacio de nombres para el atributo. |

## XmlWriter::WriteStartAttribute(const String&) método

Escribe el inicio de un atributo con el nombre local especificado.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | El nombre local del atributo. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlWriter](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)