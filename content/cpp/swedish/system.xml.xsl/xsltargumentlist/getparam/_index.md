---
title: GetParam()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar parametern som är associerad med det namnrymdskvalificerade namnet.
type: docs
weight: 14
url: /sv/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) metod

Returnerar parametern som är associerad med det namnrymdskvalificerade namnet.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Namnet på parametern. [XsltArgumentList](../) kontrollerar inte att namnet som skickas är ett giltigt lokalt namn; dock kan inte namnet vara **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | Den namnrymdens URI som är associerad med parametern. |

### Returvärde

Parameterobjektet eller **nullptr** om det inte hittades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [String](../../../system/string/)
* Klass [XsltArgumentList](../)
* Namnrymd [System::Xml::Xsl](../../)
* Bibliotek [Aspose.Slides](../../../)