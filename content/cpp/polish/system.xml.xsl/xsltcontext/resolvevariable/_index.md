---
title: ResolveVariable()
second_title: Odwołanie API Aspose.Slides dla C++
description: Gdy zostanie przesłonięta w klasie pochodnej, rozwiązuje odwołanie do zmiennej i zwraca IXsltContextVariable reprezentujący zmienną.
type: docs
weight: 14
url: /pl/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) metoda

Gdy zostanie przesłonięta w klasie pochodnej, rozwiązuje odwołanie do zmiennej i zwraca [IXsltContextVariable](../../ixsltcontextvariable/) reprezentujący zmienną.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Prefiks zmiennej tak, jak pojawia się w wyrażeniu [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | Nazwa zmiennej. |

### Wartość zwracana

Obiekt [IXsltContextVariable](../../ixsltcontextvariable/) reprezentujący zmienną w czasie wykonywania.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IXsltContextVariable](../../ixsltcontextvariable/)
* Klasa [String](../../../system/string/)
* Klasa [XsltContext](../)
* Przestrzeń nazw [System::Xml::Xsl](../../)
* Biblioteka [Aspose.Slides](../../../)