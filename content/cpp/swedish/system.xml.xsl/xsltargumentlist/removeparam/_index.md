---
title: RemoveParam()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort parametern från XsltArgumentList.
type: docs
weight: 66
url: /sv/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) metod


Tar bort parametern från [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Namnet på parametern som ska tas bort. [XsltArgumentList](../) kontrollerar inte att det angivna namnet är ett giltigt lokalt namn; dock kan inte namnet vara **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | Namnområdes-URI för parametern som ska tas bort. |

### Returvärde

Parameterobjektet eller **nullptr** om inget hittades.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [String](../../../system/string/)
* Klass [XsltArgumentList](../)
* Namnrymd [System::Xml::Xsl](../../)
* Bibliotek [Aspose.Slides](../../../)