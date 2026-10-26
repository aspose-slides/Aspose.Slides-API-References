---
title: RemoveParam()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt den Parameter aus der XsltArgumentList.
type: docs
weight: 66
url: /de/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String&, const String&) Methode

Entfernt den Parameter aus dem [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Der Name des zu entfernenden Parameters. [XsltArgumentList](../) prüft nicht, ob der übergebene Name ein gültiger lokaler Name ist; jedoch darf der Name nicht **nullptr** sein. |
| namespaceUri | const [String](../../../system/string/)\& | Der Namespace-URI des zu entfernenden Parameters. |

## Rückgabewert

Das Parameterobjekt oder **nullptr**, falls keines gefunden wurde.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [String](../../../system/string/)
* Klasse [XsltArgumentList](../)
* Namensraum [System::Xml::Xsl](../../)
* Bibliothek [Aspose.Slides](../../../)