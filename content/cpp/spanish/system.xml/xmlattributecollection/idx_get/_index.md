---
title: idx_get()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el atributo con el índice especificado.
type: docs
weight: 1
url: /es/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) método

Devuelve el atributo con el índice especificado.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | **int32_t** | El índice del atributo. |

### Valor devuelto

El atributo en el índice especificado.

## XmlAttributeCollection::idx_get(const String\&) método

Devuelve el atributo con el nombre especificado.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | El nombre calificado del atributo. |

### Valor devuelto

El atributo con el nombre especificado. Si el atributo no existe, este método devuelve **nullptr**.

## XmlAttributeCollection::idx_get(const String\&, const String\&) método

Devuelve el atributo con el nombre local y el Identificador Uniforme de Recursos (URI) del espacio de nombres especificados.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | El nombre local del atributo. |
| namespaceURI | const [String](../../../system/string/)\& | El URI del espacio de nombres del atributo. |

### Valor devuelto

El atributo con el nombre local y el URI del espacio de nombres especificados. Si el atributo no existe, este método devuelve **nullptr**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlAttribute](../../xmlattribute/)
* Clase [XmlAttributeCollection](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)