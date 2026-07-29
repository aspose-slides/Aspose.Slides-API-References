---
title: AddParam()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en parameter i XsltArgumentList och associerar den med det namnrymdskvalificerade namnet.
type: docs
weight: 40
url: /sv/system.xml.xsl/xsltargumentlist/addparam/
---
## XsltArgumentList::AddParam(const String&, const String&, const SharedPtr\<Object\>\&) metod

Lägger till en parameter till [XsltArgumentList](../) och associerar den med det namnrymdskvalificerade namnet.

```cpp
void System::Xml::Xsl::XsltArgumentList::AddParam(const String &name, const String &namespaceUri, const SharedPtr<Object> &parameter)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Namnet att associera med parametern. |
| namespaceUri | const [String](../../../system/string/)\& | Namnrymdens URI att associera med parametern. För att använda standardnamnrymden, ange en tom sträng. |
| parameter | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Parametervärdet eller objektet att lägga till i listan. |

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [Object](../../../system/object/)
* Klass [XsltArgumentList](../)
* Namnrymd [System::Xml::Xsl](../../)
* Bibliotek [Aspose.Slides](../../../)