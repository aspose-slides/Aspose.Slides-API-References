---
title: Invoke()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Udostępnia metodę wywołania funkcji z podanymi argumentami w danym kontekście.
type: docs
weight: 53
url: /pl/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) metoda

Udostępnia metodę wywołania funkcji z podanymi argumentami w danym kontekście.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | The XSLT context for the function call. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | The arguments of the function call. Each argument is an element in the array. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | The context node for the function call. |

### Wartość zwracana

Obiekt [Object](../../../system/object/) reprezentujący wartość zwracaną funkcji.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [Object](../../../system/object/)
* Klasa [XsltContext](../../xsltcontext/)
* Klasa [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Klasa [IXsltContextFunction](../)
* Przestrzeń nazw [System::Xml::Xsl](../../)
* Biblioteka [Aspose.Slides](../../../)