---
title: ResolveVariable()
second_title: Aspose.Slides C++ API referencia
description: Ha egy származtatott osztályban felül van írva, felold egy változó hivatkozást, és visszaad egy IXsltContextVariable objektumot, amely a változót képviseli.
type: docs
weight: 14
url: /hu/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) metódus

Ha egy származtatott osztályban felül van írva, felold egy változó hivatkozást, és visszaad egy [IXsltContextVariable](../../ixsltcontextvariable/) objektumot, amely a változót reprezentálja.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | A változó előtagja, ahogyan a [XPath](../../../system.xml.xpath/) kifejezésben jelenik meg. |
| name | [String](../../../system/string/) | A változó neve. |

### Visszatérési érték

Egy [IXsltContextVariable](../../ixsltcontextvariable/) amely a változót a futás időben reprezentálja.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IXsltContextVariable](../../ixsltcontextvariable/)
* Osztály [String](../../../system/string/)
* Osztály [XsltContext](../)
* Névtere [System::Xml::Xsl](../../)
* Könyvtár [Aspose.Slides](../../../)