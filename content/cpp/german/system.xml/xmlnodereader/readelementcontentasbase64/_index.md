---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest das Element und dekodiert den Base64-Inhalt.
type: docs
weight: 469
url: /de/system.xml/xmlnodereader/readelementcontentasbase64/
---
## XmlNodeReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) Methode


Liest das Element und dekodiert den Base64-Inhalt.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Der Puffer, in den der resultierende Text kopiert werden soll. Dieser Wert darf nicht **nullptr** sein. |
| index | **int32_t** | Der Offset im Puffer, an dem das Kopieren des Ergebnisses beginnen soll. |
| count | **int32_t** | Die maximale Anzahl von Bytes, die in den Puffer kopiert werden sollen. Die tatsächliche Anzahl kopierter Bytes wird von dieser Methode zurückgegeben. |

### Rückgabewert

Die Anzahl der in den Puffer geschriebenen Bytes.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlNodeReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)