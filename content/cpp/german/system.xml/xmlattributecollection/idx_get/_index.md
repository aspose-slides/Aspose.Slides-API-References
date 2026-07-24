---
title: idx_get()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt das Attribut mit dem angegebenen Index zurück.
type: docs
weight: 1
url: /de/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) Methode

Gibt das Attribut mit dem angegebenen Index zurück.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | **int32_t** | Der Index des Attributs. |

### Rückgabewert

Das Attribut am angegebenen Index.

## XmlAttributeCollection::idx_get(const String\&) Methode

Gibt das Attribut mit dem angegebenen Namen zurück.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Der qualifizierte Name des Attributs. |

### Rückgabewert

Das Attribut mit dem angegebenen Namen. Wenn das Attribut nicht existiert, gibt diese Methode **nullptr** zurück.

## XmlAttributeCollection::idx_get(const String\&, const String\&) Methode

Gibt das Attribut mit dem angegebenen lokalen Namen und dem Namespace-Uniform-Resource-Identifier (URI) zurück.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Der lokale Name des Attributs. |
| namespaceURI | const [String](../../../system/string/)\& | Der Namespace-URI des Attributs. |

### Rückgabewert

Das Attribut mit dem angegebenen lokalen Namen und Namespace-URI. Wenn das Attribut nicht existiert, gibt diese Methode **nullptr** zurück.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlAttribute](../../xmlattribute/)
* Klasse [XmlAttributeCollection](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)