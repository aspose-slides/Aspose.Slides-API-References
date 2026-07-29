---
title: WriteState
second_title: Aspose.Slides för C++ API-referens
description: Anger tillståndet för XmlWriter.
type: docs
weight: 755
url: /sv/system.xml/writestate/
---
## WriteState enum


Anger tillståndet för [XmlWriter](../xmlwriter/).

```cpp
enum class WriteState
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Start | 0 | Indikerar att XmlWriter::Write-metoden ännu inte har anropats. |
| Prolog | 1 | Indikerar att prologen skrivs. |
| Element | 2 | Indikerar att en elementstarttagg skrivs. |
| Attribute | 3 | Indikerar att ett attributvärde skrivs. |
| Content | 4 | Indikerar att elementinnehåll skrivs. |
| Closed | 5 | Indikerar att [XmlWriter::Close](../xmlwriter/close/)-metoden har anropats. |
| Error | 6 | Ett undantag har kastats, vilket har lämnat [XmlWriter](../xmlwriter/) i ett ogiltigt tillstånd. Du kan anropa [XmlWriter::Close](../xmlwriter/close/)-metoden för att sätta [XmlWriter](../xmlwriter/) i [WriteState::Closed](./)-tillståndet. Alla andra anrop av [XmlWriter](../xmlwriter/)-metoden resulterar i ett InvalidOperationException. |

## Se även

* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)