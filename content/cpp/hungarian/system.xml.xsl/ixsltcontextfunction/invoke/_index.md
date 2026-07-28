---
title: Invoke()
second_title: Aspose.Slides C++ API hivatkozás
description: Biztosítja a metódust a függvény meghívásához a megadott argumentumokkal a megadott kontextusban.
type: docs
weight: 53
url: /hu/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) metódus


Biztosítja a metódust a függvény meghívásához a megadott argumentumokkal a megadott kontextusban.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | Az XSLT kontextus a függvényhíváshoz. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | A függvényhívás argumentumai. Minden argumentum egy elem a tömbben. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | A kontextus csomópont a függvényhíváshoz. |

### Visszatérési érték

Egy [Object](../../../system/object/) amely a függvény visszatérési értékét képviseli.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [Object](../../../system/object/)
* Osztály [XsltContext](../../xsltcontext/)
* Osztály [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Osztály [IXsltContextFunction](../)
* Névtér [System::Xml::Xsl](../../)
* Könyvtár [Aspose.Slides](../../../)