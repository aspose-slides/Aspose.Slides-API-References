---
title: ResolveFunction()
second_title: Aspose.Slides for C++ API Referenciája
description: Ha egy származtatott osztályban felül van írva, felold egy függvényhivatkozást, és visszaad egy IXsltContextFunction-t, amely a függvényt képviseli. Az IXsltContextFunction a végrehajtás során a függvény visszatérési értékének lekérésére szolgál.
type: docs
weight: 27
url: /hu/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) metódus

Ha egy származtatott osztályban felül van írva, egy függvényhivatkozást old meg, és visszaad egy [IXsltContextFunction](../../ixsltcontextfunction/)-t, amely a függvényt képviseli. A [IXsltContextFunction](../../ixsltcontextfunction/) a végrehajtás időpontjában a függvény visszatérési értékének lekérésére szolgál.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | A függvény előtagja, ahogy a [XPath](../../../system.xml.xpath/) kifejezésben megjelenik. |
| name | [String](../../../system/string/) | A függvény neve. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | A feloldandó függvény argumentumtípusainak tömbje. Ez lehetővé teszi, hogy a ugyanazt a név viselő metódusok (például túlterhelt metódusok) közül válassz. |

### Visszatérési érték

Egy [IXsltContextFunction](../../ixsltcontextfunction/) amely a függvényt képviseli.

## Lásd még

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [IXsltContextFunction](../../ixsltcontextfunction/)
* Osztály [String](../../../system/string/)
* Osztály [XsltContext](../)
* Névtér [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)