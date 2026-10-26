---
title: ConformanceLevel
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje míru kontrol vstupu nebo výstupu, které provádějí objekty XmlReader a XmlWriter.
type: docs
weight: 625
url: /cs/system.xml/conformancelevel/
---
## ConformanceLevel enum

Určuje míru kontrol vstupu nebo výstupu, které provádějí objekty [XmlReader](../xmlreader/) a [XmlWriter](../xmlwriter/).

```cpp
enum class ConformanceLevel
```

### Hodnoty

| Name | Value | Description |
| --- | --- | --- |
| Auto | 0 | Objekt [XmlReader](../xmlreader/) nebo [XmlWriter](../xmlwriter/) automaticky zjistí, zda má být provedena kontrola na úrovni dokumentu nebo fragmentu, a provede odpovídající kontrolu. Pokud obalujete jiný objekt [XmlReader](../xmlreader/) nebo [XmlWriter](../xmlwriter/), vnější objekt neprovádí žádnou další kontrolu shody. Kontrola shody je ponechána na podkladovém objektu. |
| Fragment | 1 | Data XML jsou [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) podle definice W3C. Tato úroveň shody představuje XML dokument, který nemusí mít kořenový prvek, ale je jinak dobře vytvořený. Tato úroveň kontroly zajišťuje, že stream čtený nebo zapisovaný může být spotřebován jakýmkoli procesorem jako [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities). |
| Document | 2 | Data XML splňují pravidla pro dobře vytvořený [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) podle definice W3C. Tato úroveň kontroly zajišťuje, že stream čtený nebo zapisovaný může být spotřebován jakýmkoli procesorem jako [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed). |

## Viz také

* Jmenný prostor [System::Xml](../)
* Knihovna [Aspose.Slides](../../)