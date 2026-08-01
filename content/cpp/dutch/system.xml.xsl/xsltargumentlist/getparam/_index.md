---
title: GetParam()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de parameter die is geassocieerd met de namespace-gekwalificeerde naam.
type: docs
weight: 14
url: /nl/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) method


Retourneert de parameter die is geassocieerd met de namespace-gekwalificeerde naam.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | De naam van de parameter. [XsltArgumentList](../) controleert niet of de opgegeven naam een geldige lokale naam is; echter, de naam mag niet **nullptr** zijn. |
| namespaceUri | const [String](../../../system/string/)\& | De namespace-URI die is geassocieerd met de parameter. |

### Retourwaarde

Het parameterobject of **nullptr** indien deze niet werd gevonden.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)