---
title: GetParam()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Parameter zurück, der mit dem namespace-qualifizierten Namen verknüpft ist.
type: docs
weight: 14
url: /de/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) Methode

Gibt den Parameter zurück, der mit dem namespace-qualifizierten Namen verknüpft ist.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Der Name des Parameters. [XsltArgumentList](../) prüft nicht, ob der übergebene Name ein gültiger lokaler Name ist; der Name darf jedoch nicht **nullptr** sein. |
| namespaceUri | const [String](../../../system/string/)\& | Der mit dem Parameter verknüpfte Namespace-URI. |

### Rückgabewert

Das Parameterobjekt oder **nullptr**, falls keines gefunden wurde.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [String](../../../system/string/)
* Klasse [XsltArgumentList](../)
* Namensraum [System::Xml::Xsl](../../)
* Bibliothek [Aspose.Slides](../../../)