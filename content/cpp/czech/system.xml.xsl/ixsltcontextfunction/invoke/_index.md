---
title: Invoke()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Poskytuje metodu pro vyvolání funkce s danými argumenty v daném kontextu.
type: docs
weight: 53
url: /cs/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) metoda


Poskytuje metodu pro vyvolání funkce s danými argumenty v daném kontextu.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | XSLT kontext pro volání funkce. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Argumenty volání funkce. Každý argument je prvek v poli. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Kontextový uzel pro volání funkce. |

### Návratová hodnota

[Object](../../../system/object/) představující návratovou hodnotu funkce.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [Object](../../../system/object/)
* Třída [XsltContext](../../xsltcontext/)
* Třída [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Třída [IXsltContextFunction](../)
* Obor názvů [System::Xml::Xsl](../../)
* Knihovna [Aspose.Slides](../../../)