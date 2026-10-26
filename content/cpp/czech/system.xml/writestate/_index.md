---
title: WriteState
second_title: Aspose.Slides pro C++ API Reference
description: Určuje stav XmlWriteru.
type: docs
weight: 755
url: /cs/system.xml/writestate/
---
## WriteState výčet


Určuje stav [XmlWriter](../xmlwriter/).

```cpp
enum class WriteState
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Start | 0 | Indikuje, že metoda XmlWriter::Write dosud nebyla volána. |
| Prolog | 1 | Indikuje, že se zapisuje prolog. |
| Element | 2 | Indikuje, že se zapisuje počáteční značka elementu. |
| Attribute | 3 | Indikuje, že se zapisuje hodnota atributu. |
| Content | 4 | Indikuje, že se zapisuje obsah elementu. |
| Closed | 5 | Indikuje, že metoda [XmlWriter::Close](../xmlwriter/close/) byla volána. |
| Error | 6 | Byla vyvolána výjimka, která zanechala [XmlWriter](../xmlwriter/) v neplatném stavu. Můžete zavolat metodu [XmlWriter::Close](../xmlwriter/close/), aby se [XmlWriter](../xmlwriter/) dostal do stavu [WriteState::Closed](./). Jakékoli další volání metod [XmlWriter](../xmlwriter/) vede k InvalidOperationException. |

## Viz také

* Jmenný prostor [System::Xml](../)
* Knihovna [Aspose.Slides](../../)