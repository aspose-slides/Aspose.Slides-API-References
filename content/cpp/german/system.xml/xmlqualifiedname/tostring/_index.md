---
title: ToString()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Zeichenkettenwert des XmlQualifiedName zurück.
type: docs
weight: 79
url: /de/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const Methode

Gibt den Zeichenkettenwert von [XmlQualifiedName](../) zurück.

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```

### Rückgabewert

Der Zeichenkettenwert von [XmlQualifiedName](../) im Format **namespace:localname**. Wenn das Objekt keinen Namensraum definiert hat, gibt diese Methode nur den lokalen Namen zurück.

## XmlQualifiedName::ToString(const String\&, const String\&) Methode

Gibt den Zeichenkettenwert von [XmlQualifiedName](../) zurück.

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Der Name des Objekts. |
| ns | const [String](../../../system/string/)\& | Der Namensraum des Objekts. |

### Rückgabewert

Der Zeichenkettenwert von [XmlQualifiedName](../) im Format **namespace:localname**. Wenn das Objekt keinen Namensraum definiert hat, gibt diese Methode nur den lokalen Namen zurück.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlQualifiedName](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)