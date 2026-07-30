---
title: WriteStartElement()
second_title: Aspose.Slides pro C++ API Reference
description: Zapíše zadaný úvodní tag a přiřadí jej k danému jmennému prostoru a předponě.
type: docs
weight: 235
url: /cs/system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement(const String\&, const String\&, const String\&) metoda

Zapisuje zadaný úvodní tag a přiřazuje jej k danému jmennému prostoru a předponě.

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Předpona jmenného prostoru elementu. |
| localName | const [String](../../../system/string/)\& | Místní název elementu. |
| ns | const [String](../../../system/string/)\& | URI jmenného prostoru, který se má přiřadit k elementu. Pokud je tento jmenný prostor již v dosahu a má přiřazenou předponu, pak zapisovač automaticky také zapíše tuto předponu. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlTextWriter](../)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)