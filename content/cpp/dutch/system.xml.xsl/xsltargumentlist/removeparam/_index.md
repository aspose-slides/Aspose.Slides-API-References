---
title: RemoveParam()
second_title: Aspose.Slides voor C++ API Referentie
description: Verwijdert de parameter uit de XsltArgumentList.
type: docs
weight: 66
url: /nl/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) methode

Verwijdert de parameter uit de [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | De naam van de te verwijderen parameter. [XsltArgumentList](../) controleert niet of de opgegeven naam een geldige lokale naam is; echter, de naam mag niet **nullptr** zijn. |
| namespaceUri | const [String](../../../system/string/)\& | De namespace-URI van de te verwijderen parameter. |

### Retourwaarde

Het parameterobject of **nullptr** als er geen werd gevonden.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [String](../../../system/string/)
* Klasse [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Bibliotheek [Aspose.Slides](../../../)