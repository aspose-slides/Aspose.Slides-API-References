---
title: Evaluate()
second_title: Aspose.Slides C++ API referencia
description: Kiértékeli a változót futásidőben, és egy olyan objektumot ad vissza, amely a változó értékét képviseli.
type: docs
weight: 40
url: /hu/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate(SharedPtr\<XsltContext\>) metódus

A változót futásidőben értékeli ki, és visszaad egy objektumot, amely a változó értékét reprezentálja.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | Egy [XsltContext](../../xsltcontext/), amely a változó végrehajtási kontextusát képviseli. |

### Visszatérési érték

Egy [Object](../../../system/object/), amely a változó értékét képviseli. Lehetséges visszatérési típusok közé tartozik a szám, a karakterlánc, [Boolean](../../../system/boolean/), a dokumentum töredék vagy a csomópontkészlet.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [XsltContext](../../xsltcontext/)
* Osztály [IXsltContextVariable](../)
* Névtér [System::Xml::Xsl](../../)
* Könyvtár [Aspose.Slides](../../../)